# Was ist passiert?

Der Spieler kommt auf die ein oder andere Weise an und bekommt nach einem inneren Monolog die Quest [Was ist passiert?](#1.-was-ist-passiert?). Hierbei soll der Spieler Hauptmann Marduk ansprechen um mehr zu erfahren.

* [Ablauf](#ablauf)
* [Vorrausetzungen](#vorrausetzungen)
* [Aufgaben](#aufgaben)
    * [1. Hilf dem Lagerarbeiter](#1-hilf-dem-lagerarbeiter)
    * [2. Bringe die Vorräte zu Kansa](#2-bringe-die-vorräte-zu-kansa)
* [NPCs](#npcs)
    * [Kansa](#kansa)
        * [Standartsätze](#standartsätze)
            * [Vor der Quest](#vor-der-quest)
            * [Während der Quest](#während-der-quest)
            * [Nach der Quest](#nach-der-quest)
        * [Ausrüstung](#ausrüstung)
        * [Standort](#standort)
* [Items](#items)
    * [Schwarzer Barsch](#schwarzer-barsch)
    * [Geschorene Wolle](#geschorene-wolle)
    * [Frischer Eimer Milch](#frischer-eimer-milch)
    * [Roter Apfel](#roter-apfel)
* [Mobs](#mobs)
    * [Skelett](#skelett)
* [Belohnung](#belohnung)
* [Referenzen](#referenzen)

## Vorrausetzungen

[HQ Weitere Ausbildung](../../ankanor/hauptquest/5-weitere-ausbildung/README.md) Abgeschlossen

## Aufgaben

### 1. Was ist passiert?

#### Möglichkeit 1 aus [HQ Weitere Ausbildung](../../ankanor/hauptquest/5-weitere-ausbildung/README.md)

Sobald Spieler an der Eisenküste auftaucht nach dem Schiffsbruch, folgt ein innerer Monolog.

```yml
Spieler: Warum sind wir an Land? Was ist passiert? Bin ich Tod?
Spieler: Nein, es muss was anderes sein. Das ist ein Camp. Was ist nur auf dem Meer passiert? Eben lag ich noch in meiner Koje und nun bin ich hier irgendwo an Land.
Spieler: Ist das dahinten Hauptmann Marduk? Der weiß sicher was passiert ist.
```

`[QUEST START]` [Was ist passiert](#1.-was-ist-passiert?)
> **QuestLog:** *Gehe zu Hauptmann Marduk und frage ihn was passiert ist, warum ihr nun an einer Küste seid.*

Marduk spricht den Spieler direkt an (5 Blöcke)

```yml
NPC: [Name des Spielers], bist du auch endlich wach, ja?
Spieler: Hauptmann Marduk hat uns dieser Aknetun erwischt oder warum sind wir plötzlich an einer Küste?
NPC: Du scheinst einen sehr festen Schlaf zu haben, letzte Nacht tobte ein übler Sturm der das Schiff zerstörte und uns hier angespült. Wir hatten dich einfach aus dem Schiffwrack geholt und dachten du wärst Ohnmächtig.
Spieler: Ist das dein ernst? Hmm... und was machen wir nun?
```

`[QUEST ENDE]` [Was ist passiert](#1.-was-ist-passiert?)

#### Möglichkeit 2 aus [HQ Weitere Ausbildung](../../ankanor/hauptquest/5-weitere-ausbildung/README.md)

Sobald Spieler an der Eisenküste auftaucht nach dem Schiffsbruch, folgt ein innerer Monolog.

```yml
Spieler: Wo bin ich? Der Angriff, was ist passiert?
Spieler: Moment mal, sind wir noch auf Ankanor? Sieht mir nicht so aus.
Spieler: Ist das dahinten Hauptmann Marduk? Der weiß sicher was passiert ist.
```

`[QUEST START]` [Was ist passiert](#1.-was-ist-passiert?)
> **QuestLog:** *Gehe zu Hauptmann Marduk und frage ihn was passiert ist, warum ihr nun an einer Küste seid.*

Marduk spricht den Spieler direkt an (5 Blöcke)

```yml
NPC: [Name des Spielers], bist du auch endlich wach, ja?
Spieler: Hauptmann Marduk hat uns dieser Aknetun erwischt? Sind wir alle Tod?
NPC: Nein, du wurdest ausgeknockt als du Agnatus Schergen bekämpft hast, man hat dich dann zum Schiff gebracht. Dort wurdest du versorgt.
Spieler: Und wo sind wir hier? Das sieht mir nicht nach Ankanor aus.
NPC: Wo genau wir sind weiß keiner, aber nein es ist nicht mehr Ankanor. Der Sturm letzte Nacht hat unser Schiff zerstört und wir wurden hier angespült.
Spieler: Ist das dein ernst? Hmm... und was machen wir nun?
```

`[QUEST ENDE]` [Was ist passiert](#1.-was-ist-passiert?)

Weiter bei [HQ Erkunde die Umgebung](../2-erkunde-die-umgebung/README.md)

## NPCs

### Hauptmann Marduk

Er schimpft sich zwar Hauptmann, es gibt aber eigentlich keine richtigen Truppen bei den Kaishi. Marduk ist ein sehr entspannter Typ, hat keine Kampferfahrungen, soll sich aber um die Verteidigung kümmern.

#### Standartsätze

##### Vor der Quest

1. Nicht vorhanden bzw. siehe Quest

##### Während der Quest

1. Nicht vorhanden bzw. siehe Quest

##### Nach der Quest

1. Nicht vorhanden bzw. siehe Folgequest

#### Ausrüstung

Lederrüstung ohne Helm
Steinaxt in der Hand

#### Standort

```yml
x: 3645
y: 63
z: -2829
world: faldoria
```

## Items

Keine

## Mobs

Keine

## Belohnung

Keine

## Referenzen
