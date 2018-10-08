# Quest Config

Jede Quest benötigt mindestens eine Quest Config Datei die mit `.quest.yml` endet. In dieser Config wird folgendes definiert:

* **Start der Quest** - Was führt dazu, dass die Quest startet/gestartet werden kann.
* **Aufgaben** - Was muss der Spieler für Aufgaben erfüllen, damit die Quest abgeschlossen wird.
* **Ende der Quest** - Was führt dazu, dass die Quest beendet wird.
* **Belohnungen** - Was für Belohnungen erhält der Spieler für das Beenden der Quest.

In den anschließenden Erklärungen wird folgende [Beispiel Quest](./example-quest/) verwendet. Die dort verwendete `README.md` sollte bei allen Quests von den Quest Schreibern als Vorlage verwendet werden.

Die gesamte Config der Beispiel Quest befindet sich im [example-quest/](./example-quest) Ordner.

> Bei allen folgenden Beispielen sind immer, bis auf wenige Ausnahmen, die Default Werte gesetzt.

- [Referenzen](#referenzen)
- [Quest Beschreibung](#quest-beschreibung)
- [Allgemeine Config](#allgemeine-config)
  - [Default Conversations](#default-conversations)
- [Quest Core](#quest-core)
  - [Start Requirements](#start-requirements)
  - [Start Trigger](#start-trigger)
  - [Start Actions](#start-actions)
  - [Active Trigger](#active-trigger)
  - [Complete Actions](#complete-actions)
  - [Complete Trigger](#complete-trigger)
- [Objectives](#objectives)
  - [Tasks](#tasks)

## Referenzen

Folgende Links helfen beim Schreiben einer Quest.

* [Actions](https://git.faldoria.de/tof/plugins/raidcraft/raidcraft-api/blob/master/docs/ART-API.md#verwendung-von-actions) Dokumentation
* [Requirements](https://git.faldoria.de/tof/plugins/raidcraft/raidcraft-api/blob/master/docs/ART-API.md#verwendung-von-requirements) Dokumentation
* [Trigger](https://git.faldoria.de/tof/plugins/raidcraft/raidcraft-api/blob/master/docs/ART-API.md#verwendung-von-triggern) Dokumentation
* Übersicht von [Quest Dateiendungen](QUEST-DEVELOPER.md)
* [Conversations](https://git.faldoria.de/tof/plugins/raidcraft/conversations/blob/master/docs/ADMIN.md)
* Web Interface für das [Erstellen von Items](https://app.faldoria.de/items)
* Durchsuchbare [Liste von **A**actions**R**equirements**T**rigger](https://app.faldoria.de/art)

## Quest Beschreibung

Folgender Config Teil ist in jeder Quest enthalten. Er definiert grundlegende Parameter der Quest, wie z.B. den Namen und die Welten in der die Quest spielt.

> Bei einer neuen Quest darf **auf keinen Fall** das ID Feld in der Config stehen.
> Die ID wird beim ersten Start automatisch generiert.

```yml
# Die ID wird beim ersten Start der Quest automatisch vom Server generiert.
# Damit beim Verschieben der Dateien die Quests der Spieler nicht zurückgesetzt werden muss die ID konstant bleiben.
# NICHT KOPIEREN ODER MANUELL EINSETZEN --- WIRD AUTOMATISCH GENERIERT!!!
# Wenn man weiß was man tut kann man hier auch selber eine eindeutige ID (String) für die Quest vergeben.doc
# id: 3a98240d-9985-42d1-8d34-8d771014cd4f
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

### Default Conversations

Jede Quest hat die Möglichkeit je nach Phase spezielle Default Conversations pro Conversation Host festzulegen. Diese Conversations werden dann automatisch dem Host zugewiesen sobald sich der Spieler in der entsprechenden Quest Phase befindet.

| Phase                  | Beschreibung                                                                                                       |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------ |
| `not-started`          | Die Quest wurde noch nicht begonnen. Hierfür kann auch die `default-conv` im Host verwendet werden.                |
| `active`               | Die Quest wurde angenommen und ist aktiv.                                                                          |
| `objectives-completed` | Alle nicht optionalen Aufgaben in der Quest wurden abgeschlossen.                                                  |
| `completed`            | Die Quest wurde abgeschlossen. Kann gut dazu verwendet werden NPCs nach Ende der Quest anders reagieren zu lassen. |
| `aborted`              | Die Quest wurde abgebrochen.                                                                                       |

```yml
default-convs:
  # Unterhalb der Phase können beliebig viele NPCs mit der jeweiligen Unterhaltung angegeben werden.
  not-started:
    # Die ID des Hosts MUSS unbedingt in Anführungszeichen ' ' stehen.
    'this.my-host': 'this.foobar-conv'
  active:
    'this.my-host': 'this.foobar-conv'
    'this.my-other-host': 'this.fooconv'
  objectives-completed:
    # Beim Wechsel der Phasen gibt es die Möglichkeit alle in den anderen Phasen gesetzten
    # Default Conversations zu löschen.
    # Um das zu unterbinden clear: false (default: true) angeben.
    # Wenn nichts angegeben wird werden alle Conversations in einer neuen Phase gelöscht.
    clear: true
    'this.my-host': 'this.foobar-conv'
  completed:
    'this.my-host': 'this.foobar-conv'
  aborted:
    'this.my-host': 'this.foobar-conv'
```


## Quest Core

Im nachfolgenden kommen einzelne Config Sektionen die das Herzstück einer Quest bilden. Diese Config Abschnitte basieren fast alle auf der [ART API]https://git.faldoria.de/tof/plugins/raidcraft/raidcraft-api/blob/master/docs/ART-API.md) und machen massiven Gebrauch von [Actions](https://git.faldoria.de/tof/plugins/raidcraft/raidcraft-api/blob/master/docs/ART-API.md#actions), [Actions](https://git.faldoria.de/tof/plugins/raidcraft/raidcraft-api/blob/master/docs/ART-API.md#actions) und [Triggern](https://git.faldoria.de/tof/plugins/raidcraft/raidcraft-api/blob/master/docs/ART-API.md#trigger). Außerdem wird in den ganzen Quest Beispielen der einfachheit halber die [Flow Syntax](https://git.faldoria.de/tof/plugins/raidcraft/raidcraft-api/docs/blob/master/ART-API.md#flow) verwendet. Die Grundkonzepte von `ART` und der `Flow Syntax` sollten daher bekannt sein um Quests zu schreiben.

### Start Requirements

Jede Quest kann beliebig viele Start Bedingungen enthalten. Sind die Bedingungen nicht erfüllt werden die [Start Trigger](#start-trigger) gar nicht erst geprüft.

```yml
# Alle Bedingungen in einem Requirement Block werden automatisch in einer UND Bedingung zusammengefasst.
start-requirements:
  flow:
    - '?player.tag quest.completed-der_anfang' 
```

### Start Trigger

Jede Quest muss irgendwie gestartet werden, daher gibt es die Möglichkeit in Quests `start-trigger` zu definieren. Diese Trigger werden registriert und überprüft sobald alle [Start Bedingungen](#start-requirements) erfüllt sind.

> Nicht jede Quest benötigt Start Trigger.
> Eine Quest kann z.B. auch durch eine andere Quest oder Unterhaltung direkt gestartet werden.

```yml
start-trigger:
  flow:
    - '@player.location x,y,z radius:5'
    - '!conversation.start conv:beispiel-conversation'
```

Die Start Trigger werden registriert sobald alle start-requirements erfüllt wurden. Alle Actions unterhalb eines Triggers werden ausgeführt sobald der Trigger ausgelöst wird. Wenn mehrere Trigger definiert sind, werden alle gleichzeitig abgehört und führen jeweils die darunterliegenden Actions aus.

### Start Actions

Nachdem eine Quest gestartet wurde gibt es die Möglichkeit Actions im `start-actions` Block auszuführen.

```yml
start-actions:
  flow:
    - '!player.give.item this.zauberstab'
```

### Active Trigger

Während eine Quest aktiv ist gibt es die Möglichkeit Trigger zu registrieren um auf Events zu reagieren.

```yml
active-trigger:
  flow:
    - '@player.death'
    - '!quest.abort this.foobar'
```

### Complete Actions

Sobald eine Quest beendet wurde kann man, z.B. durch die `complete-actions` eine Belohung an den Spieler verteilen und EXP vergeben.

```yml
complete-actions:
  flow:
    - '!player.give.money 1g2s'
    - '!rcskills.hero.addxp 500'
```

### Complete Trigger

Wenn eine Quest beendet wurde hat man die Möglichkeit durchgehend Trigger zu registrieren die auch nach dem Ende der Quest weiter registriert sind. Dadurch kann die Umwelt auf das Erledigen von Quests reagieren.

```yml
complete-trigger:
  flow:
    - '@player.location x,y,z'
    - '!player.kill'
```

## Objectives

Der letzte und wichtigste Block in der Config sind die `objectives`. Jede Quest benötigt mindestens ein Objective (Aufgabe) damit sie gültig ist. Die Aufgaben sind das was der Spieler in seinem Quest Log sieht und nach und nach erledigen muss um die Quest abzuschließen.

Wie bei den `start-trigger` und `start-requirements` der Quest wird bei jeder Auslösung eines Objective [Triggers](https://git.faldoria.de/tof/plugins/raidcraft/raidcraft-api/blob/master/docs/ART-API.md#trigger) alle `requirements` des Objectives geprüft. Vorrausgesetzt die Requirements des Triggers sind erfüllt. Steht das Objective auf `auto-complete: true` (default) wird es automatisch abgeschlossen.

```yml
objectives:
  # Alle objectives müssen der Reihenfolge nach nummeriert werden.
  # Da in YAML Zahlen keine gültigen Keys sind müssen sie in ' ' geschrieben werden.
  '1':
    # Kurze prägnante Beschreibung der Aufgabe.
    # Steht so im Questlog.
    name: "Deine erste Aufgabe"
    # Ausführlichere Beschreibung für das erweiterte Questlog (optional).
    desc: "Mache einen Handstand mit einer Rolle rückwärts."
    # Markiert die Aufgabe als optional, d.h. sie muss nicht erfüllt werden um die Quest abzuschließen.
    optional: false
    # Zeigt die Aufgabe nicht im Questlog an.
    hidden: false
    # Zeigt keine Benachrichtigungen zur Aufgabe im Chat an.
    # Zusammen mit hidden: true kann so eine Aufgabe komplett vom Spieler verborgen bleiben.
    silent: false
    # Wenn ein Trigger der Aufgabe ausgeführt wird werden alle Requirements geprüft.
    # Sind alle Requirements erfüllt wird die Aufgabe automatisch abgeschlossen.
    auto-complete: true
    # Die Anzahl an Tasks die erfüllt sein müssen damit das Objective abgeschlossen werden kann.
    # 0 ist der Default Wert und bedeutet, dass alle (falls vorhanden) erfüllt sein müssen.
    required-tasks: 0
    # Bedingungen die erfüllt sein müssen um die Aufgabe abzuschließen.
    requirements:
      flow:
        - '?player.has-item this.holzschwert'
    # Die Trigger einer Aufgabe werden erst aktiv wenn die Aufgabe aktiv wird.
    trigger:
      flow:
        - '@host.interact this.kansa'
    # Folgende Actions werden beim Abschluss der Aufgabe ausgeführt.
    complete-actions:
      flow:
        - '!text "Gut gemacht!"'
    # Jedes Objective kann Tasks haben die sich im Prinzip genau wie Objectives verhalten.
    # Details zur Konfiguration von Tasks gibt es weiter unten.
    tasks:
      ...
  '2':
    name: ...
    ...
```

> `Tipp:` Wenn man eine Quest mit zwei Objectives, `required: 1` setzt und die beiden Objectives als `optional: true` markiert, kann man eine Quest mit zwei unterschiedlichen Ausgängen scripten.

### Tasks

Jedes Objective kann zusätzlich noch Unteraufgaben in Form von `tasks` haben. Im Gegensatz zu den Objectives sind jedoch alle Tasks paralell aktiv. Wenn das Objective aktiv wird werden auch gleichzeitig alle `trigger` der Tasks aktiviert. Sobald ein Task abgeschlossen wurde wird dessen Trigger deaktiviert. Die Tasks werden unterhalb ihres Objectives im Questlog angezeigt.

```yml
objectives:
  '1':
    name: "Objective mit Unteraufgaben"
    tasks:
      # Auch Tasks müssen mit Nummern deklariert werden.
      '1':
          # Kurze prägnante Beschreibung des Tasks.
          # Steht so im Questlog unterhalb des Objectives.
          name: "Dein erster Task"
          # Ausführlichere Beschreibung für das erweiterte Questlog (optional).
          desc: "Mache einen Handstand mit einer Rolle rückwärts."
          # Markiert den Task als optional, d.h. er muss nicht erfüllt werden damit das Objective erfüllt wird.
          optional: false
          # Zeigt den Task nicht im Questlog an.
          hidden: false
          # Zeigt keine Benachrichtigungen zum Task im Chat an.
          # Zusammen mit hidden: true kann so ein Task komplett vom Spieler verborgen bleiben.
          silent: false
          # Wenn ein Trigger des Tasks ausgeführt wird werden alle Requirements geprüft.
          # Sind alle Requirements erfüllt wird der Task automatisch abgeschlossen.
          auto-complete: true
          # Bedingungen die erfüllt sein müssen um den Task abzuschließen.
          requirements:
            flow:
              - '?player.has-item this.holzschwert'
          # Die Trigger eines Tasks werden erst aktiv wenn das dazugehörige Objective aktiv wird.
          trigger:
            flow:
              - '@host.interact this.kansa'
          # Folgende Actions werden beim Abschluss des Tasks ausgeführt.
          complete-actions:
            flow:
              - '!text "Gut gemacht!"'
```

### Objective Default Conversations

Auch in Objectives können für jede Phase [Default Conversations](#default-conversations) definiert werden. Dabei kann analog die Konfiguration wie bei der Quest Konfiguration verwendet werden. Der einzige Unterschied ist die `objectives-completed` Phase. Diese bezieht sich bei Objectives auf alle abgeschlossenen Tasks.