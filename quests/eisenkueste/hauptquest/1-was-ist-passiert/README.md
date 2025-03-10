# Was ist passiert? <!-- omit in toc -->

issue #27

Spawn des Spielers

```yml
x: 3609
y: 71
z: -2793
world: faldoria.eisenküste
```

ODER

```yml
x: 3603
y: 70
z: -2795
world: faldoria.eisenküste
```


Der Spieler kommt auf die ein oder andere Weise an und bekommt nach einem inneren Monolog die Quest [Was ist passiert?](#1.-was-ist-passiert?). Hierbei soll der Spieler Hauptmann Marduk ansprechen um mehr zu erfahren.
Nachdem der Spieler das erste Mal mit Marduk in der HQ - Was ist passiert gesprochen hat, bekommt er von ihm den Auftrag die Gegend zu erkunden insbesondere das Licht, das Marduk sah. Er findet Elius und spricht mit ihm.

## Noch zu tun

Koord - versetzen

## Übersicht <!-- omit in toc -->
- [Noch zu tun](#noch-zu-tun)
- [Vorrausetzungen](#vorrausetzungen)
  - [TAG-1](#tag-1)
  - [TAG-2](#tag-2)
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
    - [Standartsätze](#standarts%C3%A4tze-1)
      - [Vor der Quest](#vor-der-quest-1)
      - [Während der Quest](#w%C3%A4hrend-der-quest-1)
      - [Nach der Quest](#nach-der-quest-1)
    - [Ausrüstung](#ausr%C3%BCstung-1)
    - [Standort](#standort-1)
- [Items](#items)
- [Mobs](#mobs)
- [Belohnung](#belohnung)
- [Referenzen](#referenzen)

## Vorrausetzungen

[HQ Weitere Ausbildung](../../ankanor/hauptquest/5-weitere-ausbildung/README.md) Abgeschlossen

### TAG-1
> ankanor.event.survivor - 
Bekommt der Spieler wenn er den [Ankanor Event](../../../ankanor/hauptquest/5-weitere-ausbildung#2-verteidige-ankanor) ohne zu sterben überlebt.

### TAG-2
> eisenkueste.duty-start - Bekommt der Spieler wenn er `Elius` sagt er will nochmal zum Camp zurückkehren und dort aushelfen.

> eisenkueste.duty - Bekommt der Spieler wenn er anstatt `Elius` zu helfen tatsächlich nochmal zum Camp zurückkehrt und dort aushilft.

## Aufgaben

### 1. Was ist passiert?

**Sobald Spieler nach dem Schiffsbruch an der Eisenküste auftaucht, folgt ein innerer Monolog. Er wacht in einem provisorischem Bett im Lager auf**


#### Möglichkeit 1 aus [HQ Weitere Ausbildung](../../ankanor/hauptquest/5-weitere-ausbildung/README.md)
> Abfrage true [TAG-1](#tag-1)

*Du starrst an eine Decke aus Stein*   
Wo bin ich? Was ist passiert? Bin ich tot?   
Nein, es muss was anderes sein. Das ist ein Camp. Was ist nur auf dem Meer passiert? Eben lag ich noch in meiner Koje und nun bin ich hier irgendwo an Land.   
Höre ich da draußen Hauptmann Marduk? Der weiß sicher was passiert ist.   


`[QUEST START]` [Was ist passiert](#1.-was-ist-passiert?)
> **QuestLog:** *Gehe zu Hauptmann Marduk und frage ihn was passiert ist, warum ihr nun an einer Küste seid.*

Marduk spricht den Spieler direkt an (5 Blöcke)


**Marduk:** ` [Name des Spielers], bist du auch endlich wach, ja?`  
Hauptmann Marduk, hat uns dieser Aknetun erwischt oder warum sind wir plötzlich an einer Küste?   
**Marduk:** ` Agnatus hat dich nicht erwischt, aber der Mast auf unserem kenternden Schiff. Letzte Nacht tobte ein übler Sturm, der das Schiff zerstörte und uns hier angespült hat. Wir haben dich glücklicherweise bemerkt und mit abgeschleppt, obwohl das ziemlich haarig war in dem kalten Wasser.`  
Ist das dein Ernst? Hmm... und was machen wir nun?


`[QUEST ENDE]` [Was ist passiert](#1.-was-ist-passiert?)

#### Möglichkeit 2 aus [HQ Weitere Ausbildung](../../ankanor/hauptquest/5-weitere-ausbildung/README.md)
> Abfrage false [TAG-1](#tag-1)

**Sobald Spieler an der Eisenküste auftaucht nach dem Schiffsbruch, folgt ein innerer Monolog.**

*Du starrst an eine Decke aus Stein*
Wo bin ich? Der Angriff, was ist passiert?
Moment mal, sind wir noch auf Ankanor? Sieht mir nicht so aus.
Höre ich da draußen Hauptmann Marduk? Der weiß sicher was passiert ist.


`[QUEST START]` [Was ist passiert](#1.-was-ist-passiert?)
> **QuestLog:** *Gehe zu Hauptmann Marduk und frage ihn was passiert ist, warum ihr nun an einer Küste seid.*

Marduk spricht den Spieler direkt an (5 Blöcke)


**Marduk:** ` [Name des Spielers], bist du auch endlich wach, ja?`  
Hauptmann Marduk hat uns dieser Aknetun erwischt? Sind wir alle tot?   
**Marduk:** ` Nein, du wurdest ausgeknockt als du Agnatus Schergen bekämpft hast, man hat dich dann zum Schiff gebracht. Dort wurdest du versorgt.`  
Und wo sind wir hier? Das sieht mir nicht nach Ankanor aus.   
**Marduk:** ` Wo genau wir sind weiß keiner, aber nein es ist nicht mehr Ankanor. Der Sturm letzte Nacht hat unser Schiff zerstört und wir wurden hier angespült.`  
Ist das dein Ernst? Hmm... und was machen wir nun?

`[QUEST ENDE]` [Was ist passiert](#1.-was-ist-passiert?)

### 2. Erkunde die Umgebung


**Marduk:** ` Ich habe zwar schon die Gegend ein wenig erkundet und sie scheint weitgehend unbewohnt zu sein. Aber ich habe ein Licht auf dem Hügel gesehen, ich kann hier nicht weg, ich muss das Camp beschützen. Schau dir das mal an und berichte mir dann.`   
**Marduk** ` Es würde auch nicht schaden, wenn du dich etwas umhörst, wo du sonst noch mit anpacken könntest. `

Jawohl! 

`[QUEST UPDATE]` [Was ist passiert](#1.-was-ist-passiert?)
> **QuestLog:** *Erkunde die Gegend und schau dir das Licht am Berg im Westen an. Finde heraus ob dort jemand lebt.*

**Spieler findet [Elius](#elius) und spricht ihn an.**


Hallo du, ich bin [Spielername], wer bist du?   
**Elius:** ` Oh ein Fremder, was macht ihr denn hier in der Wildnis? Ich bin Elius und ich bin hier notgelandet.`   
Notgelandet? Ach, seid ihr auch schiffbrüchig so wie ich und meine Leute?   
**Elius:** ` Kann man so sagen. Mein Ballon hat einen Riss, aber vielleicht könntet ihr mir helfen. Ich bin alt und nicht mehr so fit.`   
Wie kann ich euch denn helfen?   
**Elius:** ` Ich brauche ein paar Materialien, ich erkläre Euch genau was ich brauche und wo Ihr es wahrscheinlich finden könnt.`  


   1. Ok, ich helfe gerne. 
    
   2. Ich muss aber erst mal Hauptmann Marduk Bericht erstatten.   
      **Elius:** Ok, dann hoffe ich, dass ihr bald wieder hier seid.


> Vergabe [TAG-2:](#tag-2) eisenkueste.duty-start

**Weiter nach #1:**

Weiter bei [HQ Reparaturarbeiten](../2-reparaturarbeiten/README.md)

Spieler erledigt also erst die Reparaturarbeiten Quest bevor er [Was ist passiert](#was-ist-passiert) abschließt.

Nach dem Erledigen von [HQ Reparaturarbeiten](../2-reparaturarbeiten/README.md)  geht es bei Marduk weiter


**Marduk:** ` Da bist du ja wieder! Hast du die Quelle des Lichts gefunden?`  
Das habe ich. Es handelt sich dabei um einen abgestürzten Ballon. Der Pilot und ich haben ihn wieder repariert.    
**Marduk:** ` Was ist ein Ballon? `  
Ein Schiff, das in der Luft fährt. Er hat mir auch angeboten, da wir ja mehr über dieses Land herausfinden wollen, dass er mich mitnimmt. Das wäre phantastisch, bitte lasst mich mit.   
**Marduk:** ` Ein Schiff, das in der Luft fährt, das klingt so als würden wir echt mehr erfahren müssen. Es ist ein großzügiges Angebot, dich mitzunehmen. `   
Also kann ich mit ihm mit?   
**Marduk:** `Nun denn, grundsätzlich hast du meine Erlaubnis. Ziehe als Botschafter unseres Volkes los und finde mehr über dieses Land heraus. Aber..`    
Spieler: Danke, Hauptmann!   
**Marduk** `Ich wäre dir aber trotzdem dankbar, wenn du hier im Lager auch noch aushelfen würdest, bevor du wegfliegst. So wichtig die Erkundung dieser neuen Welt ist, erst Mal müssen wir überleben.`


`[QUEST ENDE]` [Was ist passiert](#1.-was-ist-passiert?)
Weiter bei [HQ Die Erlaubnis](../3-die-erlaubnis/README.md)

**Weiter nach #2:**

> Vergabe [TAG-2:](#tag-2) eisenkueste.duty


**Marduk:** ` Da bist du ja wieder! Hast du die Quelle des Lichts gefunden?`  
Das habe ich. Es handelte sich dabei um einen abgestürzten Ballon und jemand namens Elius.   
**Marduk:** ` Was ist ein Ballon?`
Ein Schiff, das in der Luft fährt.   
**Marduk:** ` Ah, wir müssen viel mehr über dieses Land herausfinden. Weißt du denn noch mehr?`
Nein, aber dieser Elius möchte das ich ihm helfe, vielleicht erfahre ich dann mehr.   
**Marduk:** `Das klingt gar nicht so dumm, also hilf ihm.`  


> 1. Ok ich mache mich auf den Weg und erzähle später mehr.

`[QUEST ENDE]` [Was ist passiert](#1.-was-ist-passiert?)
Weiter bei [HQ Reparaturarbeiten](../2-reparaturarbeiten/README.md)

## NPCs

### Hauptmann Marduk

ID 29

Er schimpft sich zwar Hauptmann, es gibt aber eigentlich keine richtigen Truppen bei den Kaishi. Marduk ist ein sehr entspannter Typ, er hat keine Kampferfahrungen, soll sich aber um die Verteidigung kümmern.



#### Standartsätze

##### Vor der Quest

1. Nicht vorhanden bzw. siehe Quest

##### Während der Quest 

1. Wir sind hier erstmal gestrandet und müssen so viel wie möglich erfahren, also finde alles heraus was du kannst.

##### Nach der Quest

1. Ich hoffe, dass man diesem Elius vertrauen kann.

#### Ausrüstung

Skin: ID 29

Lederrüstung ohne Helm
Steinaxt in der Hand

#### Standort

```yml
x: 3612
y: 67
z: -2804
world: faldoria
```

### Elius

Er ist ein älterer Jorgendder und der eigentliche Großmeister der Gamos Historia. Mehr zu ihm im [Lore Dokument](https://onedrive.live.com/view.aspx?resid=D0C59DCD5578741F!1923&ithint=file%2cdocx&app=Word&authkey=!AAKBdECuqapbsOM).

#### Standartsätze

##### Vor der Quest

1. Ihr solltet nicht hier sein, dies ist ein verlassener Ort.
2. Im Moment kann ich nichts für Euch tun, vielleicht später.

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
world: faldoria.eisenküste
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


