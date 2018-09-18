# Quest Config

Jede Quest benötigt mindestens eine Quest Config Datei die mit `.quest.yml` endet. In dieser Config wird folgendes definiert:

* **Start der Quest** - Was führt dazu, dass die Quest startet/gestartet werden kann.
* **Aufgaben** - Was muss der Spieler für Aufgaben erfüllen, damit die Quest abgeschlossen wird.
* **Ende der Quest** - Was führt dazu, dass die Quest beendet wird.
* **Belohnungen** - Was für Belohnungen erhält der Spieler für das Beenden der Quest.

In den anschließenden Erklärungen wird folgende [Beispiel Quest](./example-quest/) verwendet. Die dort verwendete `README.md` sollte bei allen Quests von den Quest Schreibern als Vorlage verwendet werden.

Die gesamte Config der Beispiel Quest befindet sich im [example-quest/](./example-quest) Ordner.

> Bei allen folgenden Beispielen sind immer, bis auf wenige Ausnahmen, die Default Werte gesetzt.

- [Quest Beschreibung](#quest-beschreibung)
- [Allgemeine Config](#allgemeine-config)
- [Quest Core](#quest-core)
  - [Start Requirements](#start-requirements)
  - [Start Trigger](#start-trigger)
  - [Start Actions](#start-actions)
  - [Active Trigger](#active-trigger)
  - [Complete Actions](#complete-actions)
  - [Complete Trigger](#complete-trigger)
- [Objectives](#objectives)

## Quest Beschreibung

Folgender Config Teil ist in jeder Quest enthalten. Er definiert grundlegende Parameter der Quest, wie z.B. den Namen und die Welten in der die Quest spielt.

```yml
# Der Name der Quest wie er beim Spieler angezeigt wird.
name: Beispiel Quest
# Optional kann eine Beschreibung der Quest angegeben werden.
# Die Beschreibung wird über den Aufgaben im Quest Buch angezeigt.
desc: Eine kurze Beschreibung der Quest.
# Diese Quest kann nur von Spielern mit dem Recht rcquests.quest.start-locked angenommen werden
locked: true
# Zeigt die Seite im Questlog verzaubert an.
glow: false
# Personen die an der Quest arbeiten/gearbeitet haben
authors: 
  - TheFum (QS) # QS steht für Quest Schreiber
  - Silthus (QD) # QD steht für Quest Developer
# Die Welten in denen die Quest geladen wird
# Spielt die Quest sowohl in der Hauptwelt 
# und z.B. im Nether müssen beide Welten angegeben werden.
worlds:
- ankanor
```

## Allgemeine Config

Nach den informellen Angaben folgt ein Block mit globalen Config Parametern für die Quest.

```yml
# Die Quest wird automatisch beendet,
# sobald die mindestens benötigte Anzahl an objectives erledigt wurde.
auto-complete: false
# Definiert ob die objectives nacheinander abgearbeitet werden
ordered: false
# Definiert wie viele der objectives erledigt werden müssen damit die Quest automatisch abgeschlossen wird.
# Ein Wert von <= 0 bedeutet, dass alle Aufgaben erfüllt werden müssen.
# Der Wert spielt keine Rolle wenn auto-complete: false gesetzt ist.
required: 0
# Wenn auf false gesetzt wird der Abschluss der Quest auf dem Server gebroadcasted.
silent: true
# Der Cooldown in Sekunden bis die Quest nach Abschluss wieder angenommen werden kann.
cooldown: 0
# Wenn Cooldown > 0 wird repeatable automatisch true gesetzt.
# Wenn repeatable: true ist und cooldown: 0 kann eine Quest sofort nach Abschluss wieder angenommen werden.
repeatable: false
```

## Quest Core

Im nachfolgenden kommen einzelne Config Sektionen die das Herzstück einer Quest bilden. Diese Config Abschnitte basieren fast alle auf der [ART API]https://git.faldoria.de/raidcraft/raidcraft-api/blob/master/docs/ART-API.md) und machen massiven Gebrauch von [Actions](https://git.faldoria.de/raidcraft/raidcraft-api/blob/master/docs/ART-API.md#actions), [Actions](https://git.faldoria.de/raidcraft/raidcraft-api/blob/master/docs/ART-API.md#actions) und [Triggern](https://git.faldoria.de/raidcraft/raidcraft-api/blob/master/docs/ART-API.md#trigger). Außerdem wird in den ganzen Quest Beispielen der einfachheit halber die [Flow Syntax](https://git.faldoria.de/raidcraft/raidcraft-api/docs/blob/master/ART-API.md#flow) verwendet. Die Grundkonzepte von `ART` und der `Flow Syntax` sollten daher bekannt sein um Quests zu schreiben.

### Start Requirements

Jede Quest kann beliebig viele Start Bedingungen enthalten. Sind die Bedingungen nicht erfüllt werden die [Start Trigger](#start-trigger) gar nicht erst geprüft.

```yml
# Alle Bedingungen in einem Requirement Block werden automatisch in einer UND Bedingung zusammengefasst.
start-requirements:
  - '?player.tag quest.completed-der_anfang'
```

### Start Trigger

Jede Quest muss irgendwie gestartet werden, daher gibt es die Möglichkeit in Quests `start-trigger` zu definieren. Diese Trigger werden registriert und überprüft sobald alle [Start Bedingungen](#start-requirements) erfüllt sind.

> Nicht jede Quest benötigt Start Trigger.
> Eine Quest kann z.B. auch durch eine andere Quest oder Unterhaltung direkt gestartet werden.

```yml
start-trigger:
  - '@player.location x,y,z radius:5'
  - '!conversation.start conv:beispiel-conversation'
```

Die Start Trigger werden registriert sobald alle start-requirements erfüllt wurden. Alle Actions unterhalb eines Triggers werden ausgeführt sobald der Trigger ausgelöst wird. Wenn mehrere Trigger definiert sind, werden alle gleichzeitig abgehört und führen jeweils die darunterliegenden Actions aus.

### Start Actions

Nachdem eine Quest gestartet wurde gibt es die Möglichkeit Actions im `start-actions` Block auszuführen.

```yml
start-actions:
  - '!player.give.item this.zauberstab'
```

### Active Trigger

Während eine Quest aktiv ist gibt es die Möglichkeit Trigger zu registrieren um auf Events zu reagieren.

```yml
active-trigger:
  - '@player.death'
  - '!quest.abort this.foobar'
```

### Complete Actions

Sobald eine Quest beendet wurde kann man, z.B. durch die `complete-actions` eine Belohung an den Spieler verteilen und EXP vergeben.

```yml
complete-actions:
  - '!player.give.money 1g2s'
  - '!rcskills.hero.addxp 500'
```

### Complete Trigger

Wenn eine Quest beendet wurde hat man die Möglichkeit durchgehend Trigger zu registrieren die auch nach dem Ende der Quest weiter registriert sind. Dadurch kann die Umwelt auf das Erledigen von Quests reagieren.

```yml
complete-trigger:
  - '@player.location x,y,z'
  - '!player.kill'
```

## Objectives

Der letzte und wichtigste Block in der Config sind die `objectives`. Jede Quest benötigt mindestens ein Objective (Aufgabe) damit sie gültig ist. Die Aufgaben sind das was der Spieler in seinem Quest Log sieht und nach und nach erledigen muss um die Quest abzuschließen.