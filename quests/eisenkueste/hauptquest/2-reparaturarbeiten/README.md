# Reparaturarbeiten <!-- omit in toc -->

Elius bittet den Spieler ihm dabei zu helfen den Ballon zu reparieren mit dem Elius notlanden musste. Hierzu muss er einige Materialien an der Eisenküste sammeln.

- [Vorrausetzungen](#vorrausetzungen)
    - [TAG-1](#tag-1)
- [Aufgaben](#aufgaben)
    - [1.1 Materialien sammeln](#11-materialien-sammeln)
    - [1.2 Materialien sammeln](#12-materialien-sammeln)
- [NPCs](#npcs)
    - [Elius](#elius)
        - [Standartsätze](#standartsätze)
            - [Vor der Quest](#vor-der-quest)
            - [Während der Quest](#während-der-quest)
            - [Nach der Quest](#nach-der-quest)
        - [Ausrüstung](#ausrüstung)
        - [Standort](#standort)
- [Items](#items)
    - [Klebstoff](#klebstoff)
    - [Holzbrett](#holzbrett)
    - [Spinnenseide](#spinnenseide)
    - [Stoff](#stoff)
    - [Feuerstein](#feuerstein)
    - [Angerostetes Kettenhemd](#angerostetes-kettenhemd)
    - [Zerrissener Lederwams](#zerrissener-lederwams)
    - [Zerschlissene Robe](#zerschlissene-robe)
- [Mobs](#mobs)
- [Belohnung](#belohnung)
- [Referenzen](#referenzen)

## Vorrausetzungen

[HQ Was ist passiert?](../1-was-ist-passiert/README.md) - Angenommen/Abgeschlossen

### TAG-1
eisenkueste.duty - Bekommt der Spieler wenn er anstatt `Elius` zu helfen nochmal zum Camp zurückkehrt und dort aushilft.

## Aufgaben

> Abrfrage true [TAG-1](#tag-1)
### 1.1 Materialien sammeln

Spieler spricht NPC an.

```yml
Spieler: Ich bin zurück, Elius, nun kann ich Euch helfen.
Elius: Schön das Ihr zurückgekommen seid. Seid gewarnt, es sind einige Dinge die ich brauche.
Spieler: Dann sollten wir keine Zeit verlieren.
Elius: Wunderbar! Ich brauche [1 Klebstoff], [5 Holzbretter], [5 Spinnenseide], [1 Feuerstein] und [5 Stoffe]. 
Spieler: Und wo finde ich das alles?
Elius: Auf alles weiß ich auch keine Antwort, aber einige Tipps kann ich Euch geben.
Elius: Hinter dem Hügel im Süden gibt es eine Mine, ich bin mir sicher da sind Spinnen, gut für Spinnenseide.
Spieler: Ok und weiter?
Elius: Ich schätze, dass sich hier irgendwo Schmuggler niedergelassen haben, vielleicht am Strand, die haben sicher Stoffe und Holzbretter.
Spieler: Und das geben die mir einfach? 
Elius: Ich schätze nicht, ihr müsst sie überzeugen. Klebstoff ist schwierig, es kann von bestimmten Monstern gewonnen werden. Aber in der Schifffahrt hat man auch oft welches dabei.
Spieler: Ich werde schon einen Weg finden. Feuerstein kann ich sicher irgendwo am Strand finden.
Elius: Das ist sehr gut möglich.
```

> Ich werde loslegen und versuchen, so schnell wie möglich alles zu besorgen.
`[QUEST START]` [Reparaturarbeiten](#1.1-Materialien-sammeln)  
> **QuestLog:** *Sammle [1 Klebstoff], [5 Holzbretter], [5 Spinnenseide], [1 Feuerstein] und [5 Stoffe] für Elius*

> Abrfrage false [TAG-1](#tag-1)
### 1.2 Materialien sammeln

Spieler spricht NPC an.

```yml
Elius: Wunderbar! Ich brauche [1 Klebstoff], [5 Holzbretter], [5 Spinnenseide], [1 Feuerstein] und [5 Stoffe]. 
Spieler: Und wo finde ich das alles?
Elius: Auf alles weiß ich auch keine Antwort, aber einige Tipps kann ich Euch geben.
Elius: Hinter dem Hügel im Süden gibt es eine Mine, ich bin mir sicher da sind Spinnen, gut für Spinnenseide.
Spieler: Ok und weiter?
Elius: Ich schätze, dass sich hier irgendwo Schmuggler niedergelassen haben, vielleicht am Strand, die haben sicher Stoffe und Holzbretter.
Spieler: Und das geben die mir einfach? 
Elius: Ich schätze nicht, ihr müsst sie überzeugen. Klebstoff ist schwierig, es kann aus bestimmten Monstern gewonnen werden. Aber in der Schifffahrt hat man auch oft welches dabei.
Spieler: Ich werde schon einen Weg finden. Feuerstein kann ich sicher irgendwo am Strand finden.
Elius: Das ist sehr gut möglich.
```

> Ich werde loslegen und versuchen so schnell wie möglich alles zu besorgen.
`[QUEST START]` [Reparaturarbeiten](#1.2-Materialien-sammeln)  
> **QuestLog:** *Sammle [1 Klebstoff], [5 Holzbretter], [5 Spinnenseide], [1 Feuerstein] und [5 Stoffe] für Elius*

...

```yml
Elius: Seid ihr schon zurück? Das ging aber schnell.
Spieler: Ich habe mein Bestes gegeben, es war nicht einfach, aber ich habe es geschafft.
Elius: Dann gebt mir die Sachen und ich werde mich dran machen den Ballon zu reparieren. Kommt später einfach wieder wenn Ihr mitfliegen wollt.
Spieler: Das werde ich machen, ich glaube das könnte ein spannendes Abenteuer werden!
Elius: Sprich doch nochmal mit deinen Leuten in der Zwischenzeit.
```

> Spieler: Ich werden Hauptmann Marduk von meinem Erfolg hier berichten.

`[QUEST UPDATE]` [Reparaturarbeiten](#reparaturarbeiten)
> **QuestLog:** *Gehe zurück ins Camp am Strand und sprich mit Marduk.*

```yml
Spieler: Hauptmann ich habe es geschafft, Elius ist gerade dabei den Ballon zu reparieren. Das dauert aber ein bisschen. 
Marduk: Das erfreut mich, wenn er fertig ist gehst du also mit ihm.
```

> Ja, das wird aufregend.

`[QUEST ENDE]` [Reparaturarbeiten](#reparaturarbeiten) und erhält [Belohnung](#belohunung) 

Weiter bei [HQ Die Erlaubnis](../3-die-erlaubnis/README.md)

## NPCs

### Elius

Er ist ein älterer Jorgendder und der eigentliche Großmeister der Gamos Historia. Mehr zu ihm im [Lore Dokument](https://onedrive.live.com/view.aspx?resid=D0C59DCD5578741F!1923&ithint=file%2cdocx&app=Word&authkey=!AAKBdECuqapbsOM).

#### Standartsätze

##### Vor der Quest

1. Ihr solltet nicht hier sein, dies ist ein verlassener Ort.
2. Im Moment kann ich nichts für Euch tun, vielleicht später.

##### Während der Quest

1. Elius: Soll ich Euch noch einmal sagen, wo ihr die benötigten Sachen vielleicht finden könnt?
    1. Spieler: Wo finde ich die Holzbretter und die Stoffe.
        1. Elius: Irgendwo haben sich Schmuggler eingenistet, wahrscheinlich am Strand. Die haben so etwas bestimmt. Aber es gibt sicher noch andere Möglichkeiten.
    2. Spieler: Die Spinnen für die Seide waren nochmal wo?
        1. Elius: Hinter dem südlichen Hügel ist eine Mine, da sind sicher auch Spinnen zu finden.
    3. Spieler: Der Klebstoff macht mir Probleme, wo kann ich den finden?
        1. Elius: Der ist von einigen Monstern zu bekommen oder frag deine Leute, die mit dir den Schiffbruch überlebten, ob sie noch etwas haben.
    4. Spieler: Ich finde keinen Feuerstein.
        1. Elius: Hast du es im Steinbruch im Süden versucht? Ich hörte aber, dass dort die Untoten wandeln.

>Ich danke euch Elius.

##### Nach der Quest

1. Ich bin noch nicht soweit, komm bitte später wieder. 

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

### Klebstoff

Gewöhnlicher Klebstoff, der aus unterschiedlichen Quellen gewonnen werden kann.

```yml
ID: 5
name: Klebstoff
type: ROHSTOFF
quality: COMMON
item: SLIMEBALL
lore: Dieser gewöhnliche Klebstoff hat viele Verwendungszwecke. 
max-stack-size: 64
```

### Holzbrett

Dieses Holzbrett ist verarbeitet, aber gewöhnlich und überall zu finden.

```yml
ID: 6
name: Holzbrett
type: Rohstoff
quality: COMMON
item: OAK WOOD PLANK
lore: Ein gewöhnliches Holzbrett.
max-stack-size: 64
```

### Spinnenseide

Diese Spinnenseide ist bei jeder Spinnenart zu finden, meist droppt es beim Töten.

```yml
ID: 7
name: Spinnenseide
type: Rohstoff
quality: COMMON
item: STRING
lore: Spinnenseide ist zwar für manche ekelig, seine Anwendungsmöglichkeiten sind aber groß.
max-stack-size: 64
```

### Stoff

Dieser Stoff kann aus diversen, unterschiedlich gewonnenen Fasern bestehen. Die Farbgebung wird durch die Faserart bestimmt, ist meist eher gräulich, kann aber gefärbt werden.

```yml
ID: 8
name: Stoff
type: Rohstoff
quality: COMMON
item: LIGHT GREY CARPET
lore: Dieser verarbeitete Stoff ist noch in seiner Naturfarbe und kann für diverse Dinge verwendet werden.
max-stack-size: 64
```

### Feuerstein

Mit diesem Feuerstein können leicht Feuer entzündet werden.

```yml
ID: 9
name: Feuerstein
type: QUEST
quality: COMMON
item: FLINT
lore: Dieser Feuerstein kann helfen ein Feuer zu entzünden.
max-stack-size: 64
```

### Angerostetes Kettenhemd

Ein gewöhnliches Brustteil, das seine besten Tage schon hinter sich hat.  
Belohnung für Krieger.

```yml
ID: 
name: Angerostetes Kettenhemd
type: Rüstung
quality: COMMON
item: CHAINMAIL CHESTPLATE
lore: Das Kettenhemd scheint seine besten Zeiten hinter sich zu haben, aber besser als nichts.
max-stack-size: 1
attributes: +1 ausdauer / +1 Stärke
```

### Zerrissener Lederwams

Ein gewöhnliches Brustteil, das seine besten Tage schon hinter sich hat.  
Belohnung für Waldläufer und Assassine.

```yml
ID: 
name: Zerrissener Lederwams
type: Rüstung
quality: COMMON
item: LEATHER TUNIC
lore: Dieser Lederwams scheint seine besten Zeiten hinter sich zu haben, aber besser als nichts.
max-stack-size: 1
attributes: +1 ausdauer / +1 Geschick
```

### Zerschlissene Robe

Ein gewöhnliches Brustteil, das seine besten Tage schon hinter sich hat.  
Belohnung für Kleriker und Magier.

```yml
ID: 
name: Zerschlissene Robe
type: Rüstung
quality: COMMON
item: LEATHER TUNIC
lore: Diese Robe scheint ihre besten Zeiten hinter sich zu haben, aber besser als nichts.
max-stack-size: 1
attributes: +1 ausdauer / +1 Int
```

## Mobs

Keine

## Belohnung

[Reparaturarbeiten](#repararurarbeiten)
> 20 Heller  
> 30 exp  
> Krieger [Angerostetes Kettenhemd](#angerostetes-kettenhemd)  
> Assassine/Waldläufer [Zerrissener Lederwams](#zerrissener-lederwams)  
> Magier/Kleriker [Zerschlissene Robe](#zerschlissene-robe)  

## Referenzen


