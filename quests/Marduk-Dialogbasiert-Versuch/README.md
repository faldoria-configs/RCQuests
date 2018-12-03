# NPC-basierter Dialog Marduk


## [Was ist passiert](#1.-was-ist-passiert?)


### 1. Was ist passiert?
> Mögl. 1

**QuestLog:** *Gehe zu Hauptmann Marduk und frage ihn was passiert ist, warum ihr nun an einer Küste seid.*

```yml
Marduk: [Name des Spielers], bist du auch endlich wach, ja?
Spieler: Hauptmann Marduk hat uns dieser Aknetun erwischt oder warum sind wir plötzlich an einer Küste?
Marduk: Du scheinst einen sehr festen Schlaf zu haben, letzte Nacht tobte ein übler Sturm, der das Schiff zerstörte und uns hier angespült hat. Wir haben dich einfach aus dem Schiffwrack geholt und dachten du wärst ohnmächtig.
Spieler: Ist das dein Ernst? Hmm... und was machen wir nun?

```
>  Mögl. 2
> 
**QuestLog:** *Gehe zu Hauptmann Marduk und frage ihn was passiert ist, warum ihr nun an einer Küste seid.*

```yml
Marduk: [Name des Spielers], bist du auch endlich wach, ja?
Spieler: Hauptmann Marduk hat uns dieser Aknetun erwischt? Sind wir alle tot?
Marduk: Nein, du wurdest ausgeknockt als du Agnatus Schergen bekämpft hast, man hat dich dann zum Schiff gebracht. Dort wurdest du versorgt.
Spieler: Und wo sind wir hier? Das sieht mir nicht nach Ankanor aus.
Marduk: Wo genau wir sind weiß keiner, aber nein es ist nicht mehr Ankanor. Der Sturm letzte Nacht hat unser Schiff zerstört und wir wurden hier angespült.
Spieler: Ist das dein Ernst? Hmm... und was machen wir nun?


`[QUEST ENDE]` [Was ist passiert](#1.-was-ist-passiert?)

### 2. Erkunde die Umgebung

```yml
Marduk: Ich habe zwar schon die Gegend ein wenig erkundet und sie scheint weitgehend unbewohnt zu sein. Aber ich habe ein Licht auf dem Hügel gesehen, ich kann hier nicht weg, ich muss das Camp beschützen. Schau dir das mal an und berichte mir dann.
```
> Spieler: Jawohl! 

`[QUEST UPDATE]` [Was ist passiert](#1.-was-ist-passiert?)
> **QuestLog:** *Erkunde die Gegend und schau dir das Licht am Berg im Westen an. Finde heraus ob dort jemand lebt.*

Spieler erledigt also erst die Reparaturarbeiten Quest bevor er [Was ist passiert]abschließt.

Nach dem Erledigen folgt geht es bei Marduk weiter

```yml
Marduk: Da bist du ja wieder! Hast du die Quelle des Lichts gefunden?
Spieler: Das habe ich. Es handelte sich dabei um einen abgestürzten Ballon. Der Pilot und ich haben ihn wieder repariert. 
Marduk: Was ist ein Ballon? 
Spieler: Ein Schiff, das in der Luft fährt. Er hat mir auch angeboten, da wir ja mehr über dieses Land herausfinden wollen, dass er mich mitnimmt. Das wäre phantastisch, bitte lasst mich mit.
Marduk: Ein Schiff, das in der Luft fährt, das klingt so als würden wir echt mehr erfahren müssen. Es ist ein großzügiges Angebot, dich mitzunehmen. 
Spieler: Also kann ich mit ihm mit?
Marduk: Nun denn, du hast meine Erlaubnis. Ziehe als Botschafter unseres Volkes los und finde mehr über dieses Land heraus. 
Spieler: Danke, Hauptmann!
```

`[QUEST ENDE]` [Was ist passiert](#1.-was-ist-passiert?)
Weiter bei [HQ Die Erlaubnis](../3-die-erlaubnis/README.md)

**Weiter nach #2:**

> Vergabe [TAG-2:](#tag-2) eisenkueste.duty

```yml
Marduk: Da bist du ja wieder! Hast du die Quelle des Lichts gefunden?
Spieler: Das habe ich. Es handelte sich dabei um einen abgestürzten Ballon und jemand namens Elius.
Marduk: Was ist ein Ballon?
Spieler: Ein Schiff, das in der Luft fährt.
Marduk: Ah, wir müssen viel mehr über dieses Land herausfinden. Weißt du denn noch mehr?
Spieler: Nein, aber dieser Elius möchte das ich ihm helfe, vielleicht erfahre ich dann mehr.
Marduk: Das klingt gar nicht so dumm, also hilf ihm.
```

> 1. Ok ich mache mich auf den Weg und erzähle später mehr.

`[QUEST ENDE]` [Was ist passiert](#1.-was-ist-passiert?)
Weiter bei [HQ Reparaturarbeiten](../2-reparaturarbeiten/README.md)