# Was ist passiert? <!-- omit in toc -->

Der Spieler kommt auf die ein oder andere Weise an und bekommt nach einem inneren Monolog die Quest [Was ist passiert?](#1.-was-ist-passiert?). Hierbei soll der Spieler Hauptmann Marduk ansprechen um mehr zu erfahren.
Nachdem der Spieler das erste Mal mit Marduk in der HQ - Was ist passiert gesprochen hat, bekommt er von ihm den Auftrag die Gegend zu erkunden insbesondere das Licht was Marduk sah. Er findet Elius und spricht mit ihm.

- [Vorrausetzungen](#vorrausetzungen)
    - [Tags](#tags)
- [Aufgaben](#aufgaben)
    - [1. Was ist passiert?](#1-was-ist-passiert)
        - [Möglichkeit 1 aus HQ Weitere Ausbildung](#m%C3%B6glichkeit-1-aus-hq-weitere-ausbildung)
        - [Möglichkeit 2 aus HQ Weitere Ausbildung](#m%C3%B6glichkeit-2-aus-hq-weitere-ausbildung)
    - [2. Erkunde die Umgebung](#2-erkunde-die-umgebung)
- [NPCs](#npcs)
    - [Hauptmann Marduk](#hauptmann-marduk)
        - [Standartsätze](#standarts%C3%A4tze)
            - [Vor der Quest](#vor-der-quest)
            - [Während der Quest](#w%C3%A4hrend-der-quest)
            - [Nach der Quest](#nach-der-quest)
        - [Ausrüstung](#ausr%C3%BCstung)
        - [Standort](#standort)
    - [Elius](#elius)
        - [Standartsätze](#standarts%C3%A4tze)
            - [Vor der Quest](#vor-der-quest)
            - [Während der Quest](#w%C3%A4hrend-der-quest)
            - [Nach der Quest](#nach-der-quest)
        - [Ausrüstung](#ausr%C3%BCstung)
        - [Standort](#standort)
- [Items](#items)
- [Mobs](#mobs)
- [Belohnung](#belohnung)
- [Referenzen](#referenzen)

## Vorrausetzungen

[HQ Weitere Ausbildung](../../ankanor/hauptquest/5-weitere-ausbildung/README.md) Abgeschlossen

### Tags

> TAG-1: ankanor.event.survivor

## Aufgaben

### 1. Was ist passiert?

#### Möglichkeit 1 aus [HQ Weitere Ausbildung](../../ankanor/hauptquest/5-weitere-ausbildung/README.md)
> Abfrage true *TAG-1*

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
Marduk: [Name des Spielers], bist du auch endlich wach, ja?
Spieler: Hauptmann Marduk hat uns dieser Aknetun erwischt oder warum sind wir plötzlich an einer Küste?
Marduk: Du scheinst einen sehr festen Schlaf zu haben, letzte Nacht tobte ein übler Sturm, der das Schiff zerstörte und uns hier angespült. Wir hatten dich einfach aus dem Schiffwrack geholt und dachten du wärst ohnmächtig.
Spieler: Ist das dein Ernst? Hmm... und was machen wir nun?
```

`[QUEST ENDE]` [Was ist passiert](#1.-was-ist-passiert?)

#### Möglichkeit 2 aus [HQ Weitere Ausbildung](../../ankanor/hauptquest/5-weitere-ausbildung/README.md)
> Abfrage false *TAG-1*

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
Marduk: [Name des Spielers], bist du auch endlich wach, ja?
Spieler: Hauptmann Marduk hat uns dieser Aknetun erwischt? Sind wir alle Tod?
Marduk: Nein, du wurdest ausgeknockt als du Agnatus Schergen bekämpft hast, man hat dich dann zum Schiff gebracht. Dort wurdest du versorgt.
Spieler: Und wo sind wir hier? Das sieht mir nicht nach Ankanor aus.
Marduk: Wo genau wir sind weiß keiner, aber nein es ist nicht mehr Ankanor. Der Sturm letzte Nacht hat unser Schiff zerstört und wir wurden hier angespült.
Spieler: Ist das dein Ernst? Hmm... und was machen wir nun?
```

`[QUEST ENDE]` [Was ist passiert](#1.-was-ist-passiert?)

### 2. Erkunde die Umgebung

```yml
Marduk: Ich habe zwar schon die Gegend ein wenig erkundet und sie scheint weitgehend unbewohnt zu sein. Aber ich habe ein Licht auf dem Hügel gesehen, ich kann hier nicht weg ich muss das Camp beschützen. Schau dir das mal an und berichte mir dann.
```
> Spieler: Jawohl! 

`[QUEST UPDATE]` [Was ist passiert](#1.-was-ist-passiert?)
> **QuestLog:** *Erkunde die Gegend und schau dir das Licht am Berg im Westen an. Finde heraus ob dort jemand lebt.*

Spieler findet [Elius](#elius) und spricht ihn an.

```yml
Spieler: Hallo du, ich bin [Spielername], wer bist du?
Elius: Oh ein Fremder, was macht ihr denn hier in der Wildnis? Ich bin Elius und ich bin hier notgelandet.
Spieler: Notgelandet? Ach, seid ihr auch schiffbrüchig so wie ich und meine Leute?
Elius: Kann man so sagen. Mein Ballon hat einen Riss, aber vielleicht könntet ihr mir helfen. Ich bin alt und nicht mehr so Fit. 
Spieler: Wie kann ich euch denn helfen?
Elius: Ich brauche ein paar Materialien, ich erkläre euch genau was ich brauche und wo ihr es wahrscheinlich finden könnt.
```

> 1. Ok, ich helfe gerne.
> 2. Ich muss aber erst mal Hauptmann Marduk Bericht erstatten.

```yml
Elius: Ok, dann hoffe ich das ihr bald wieder hier seid.
```

**Weiter nach #1:**

Weiter bei [HQ Reparaturarbeiten](../2-reparaturarbeiten/README.md)

Spieler erledigt also erst die Reparaturarbeiten Quest bevor er [Was ist passiert]abschließt.

Nach dem erledigen folgt geht es bei Marduk weiter

```yml
Marduk: Da bist du ja wieder! Hast du die Quelle des Lichts gefunden?
Spieler: Das habe ich. Es handelte sich dabei um einen abgestürzten Ballon. Der Pilot und ich haben ihn wieder repariert. 
Marduk: Was ist ein Ballon? 
Spieler: Ein Schiff was in der Luft fährt. Er hat mir auch Angeboten, da wir ja mehr über dieses Land herausfinden wollen, das er mich mitnimmt. Das wäre super, bitte lasst mich mit.
Marduk: Ein Schiff, das in der Luft fährt, das klingt so als würden wir echt mehr erfahren müssen. Es ist ein großzügiges Angebot dich mitzunehmen. 
Spieler: Also kann ich mit ihm mit?
Marduk: Nun denn, du hast meine Erlaubnis. Ziehe als Botschafter unseres Volkes los und finde mehr über dieses Land heraus. 
Spieler: Danke, Hauptmann!
```

`[QUEST ENDE]` [Was ist passiert](#1.-was-ist-passiert?)
Weiter bei [HQ Die Erlaubnis](../3-die-erlaubnis/README.md)

**Weiter nach #2:**

```yml
Marduk: Da bist du ja wieder! Hast du die Quelle des Lichts gefunden?
Spieler: Das habe ich. Es handelte sich dabei um einen abgestürzten Ballon und jemand namens Elius.
Marduk: Was ist ein Ballon?
Spieler: Ein Schiff was in der Luft fährt.
Marduk: Ah, wir müssen viel mehr über dieses Land herausfinden. Weißt du denn noch mehr?
Spieler: Nein, aber dieser Elius möchte das ich ihm helfe, vielleicht erfahre ich dann mehr.
Marduk: Das klingt gar nicht so dumm, also hilf ihm.
```

> 1. Ok ich mache mich auf den Weg und erzähle später mehr.

`[QUEST ENDE]` [Was ist passiert](#1.-was-ist-passiert?)
Weiter bei [HQ Reparaturarbeiten](../2-reparaturarbeiten/README.md)

## NPCs

### Hauptmann Marduk

Er schimpft sich zwar Hauptmann, es gibt aber eigentlich keine richtigen Truppen bei den Kaishi. Marduk ist ein sehr entspannter Typ, er hat keine Kampferfahrungen, soll sich aber um die Verteidigung kümmern.

#### Standartsätze

##### Vor der Quest

1. Nicht vorhanden bzw. siehe Quest

##### Während der Quest 

1. Wir sind hier erstmal gestrandet und müssen so viel wie möglich erfahren, also finde alles heraus was du kannst.

##### Nach der Quest

1. Ich hoffe das man diesem Elius vertrauen kann.

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

### Elius

Er ist älterer Jorgendder und der eigentliche Großmeister der Gamos Historia. Mehr zu ihm im [Lore Dokument](https://onedrive.live.com/view.aspx?resid=D0C59DCD5578741F!1923&ithint=file%2cdocx&app=Word&authkey=!AAKBdECuqapbsOM).

#### Standartsätze

##### Vor der Quest

1. Ihr solltet nicht hier sein, dies ist ein verlassener Ort.
2. Im Moment kann ich nichts für euch tun, vielleicht später.

##### Während der Quest

1. Nicht vorhanden bzw. siehe Quest

##### Nach der Quest

1. Nicht vorhanden bzw. siehe Folgequest

#### Ausrüstung

Buch in der Hand

#### Standort

```yml
x: 3381
y: 125
z: -2664
world: faldoria
```

## Items

Keine

## Mobs

Keine

## Belohnung

[Was ist passiert](#was-ist-passiert)
> 8 Heller  
> 10 exp  

## Referenzen


