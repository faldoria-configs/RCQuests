# Vorräte für das Schiff

Nachdem der Spieler mit Shicho und Roschik gesprochen hat soll er nun den Kapitän suchen und ihm beim Schiff klar machen helfen.

## Ablauf

1. Start: Spieler bekommt von [NPC Roschik](#Roschik) die Aufgabe [Kapitän Mafei](#kapitän-mafei) zu finden und ihm zu helfen.
2. Spieler geht zum Steg beim Schiff und Spricht Mafei an.
3. Dieser gibt ihm die Aufgabe Vorräte aus dem Lager bei der Versammlunghalle zu holen.
4. Spieler geht ins Lager und durchwühlt die Kisten und sammelt 10 Getreide, 1 Fass Wasser, 10 Holzbretter und 10 Wolle.
5. Spieler kehrt zurück und erhält eine [Belohnung](#Belohnung)

## Vorraussetzungen

> 1. Erledigen der [HQ Ein neuer Start](../1-ein-neuer-start/README.md)

## NPCs

### Roschik

Er ist der Bürgermeister des Dorfes in dem die Kaishi wohnen. Roschik ist ein sehr gütiger Kaishi und wird von allen Respektiert.

### Dialoge

#### Standartsätze  

**Vor der Quest**
1. Nicht vorhanden

**Während der Quest**  
1. Hast du Mafei gefunden? Er ist sicher am Steg beim Schiff.

**Nach der Quest**
1. Es ist sehr wichtig das du keinen Unsinn machst im Moment, wir brauchen jeden jetzt um uns vorzubereiten.
2. Ich hoffe du verstehst das ich gerade keine Zeit habe für dich.
    
#### Quest Dialog

##### Vorräte für das Schiff 1

```yml
Roschik: Wir werden Vorbereitungen treffen müssen und du musst dabei helfen.
Spieler: Was soll ich tun? 
Roschik: Zuerst müssen wir das Schiff klar machen. Geh und suche den Kapitän, er ist bestimmt an der Küste und angelt.
```
> 1. Spieler: Ich mache mich sofort auf den Weg. `[QUEST START]` [Vorräte für das Schiff](#vorräte-für-das-schiff)  
**Questlog**: *Finde Kapitän Mafei, du wirst ihn an der Küste beim Schiff finden.*

> Weiter bei [NPC Kapitän Mafei](#kapitän-mafei)

##### Vorräte für das Schiff 3

```yml
Roschik: Hast du Kapitän Mafei über die Situation informiert?
Spieler: Ja, auch wenn er mir anfangs nicht glauben wollte, ich habe sogar Vorräte für das Schiff besorgt.
```
`[QUEST ENDE]` [Vorräte für das Schiff](#vorräte-für-das-schiff)


> Weiter bei [Aufstieg zum Tianbaum](../3-aufstieg-zum-tianbaum/README.md)

#### Ausrüstung

#### Standort

```yml
x: 100
y: 82
z: -85
world: Ankanor
```

### Kapitän Mafei

Der Kapitän ist ein ambitionierter Angler der ziemlich schnell genervt ist.

### Dialoge

#### Standartsätze  

**Vor der Quest**
1. Stör mich nicht, siehst du nicht das ich angel. Dafür benötige ich absolute Ruhe, vorallem vor dir.

**Während der Quest**  
1. siehe Quest Dialog

**Nach der Quest**
1. Auch wenn du mir geholfen hast, LASS MICH IN RUHE!
2. Verdammt nochmal nerv wen anders!
    
#### Quest Dialog 

##### Vorräte für das Schiff 2

```yml
Mafei: Und der Tag ist perfekt.
Spieler: Was hast du gesagt Mafei?
Mafei: Nichts, sag mir schnell was du willst und geh dann wieder. 
Spieler: Der Bürgermeister schickt mich, du sollst das Schiff klar machen. Irgendwas von Weltuntergang oder so.
Mafei: Wie bitte? Verarsch mich nicht. 
Spieler: Nein, nein ehrlich, Agmagnum der Nekromant, hat Schiffe in unsere Richtung geschickt.
Mafei: Du meinst Agnatus? Wenn das einer deiner Späße wird, werde ich dich verprügeln.
Spieler: So glaub mir doch, du sollst das Schiff klar machen.
Mafei: Ok, dann kannst du mir behilflich sein. Du musst ein paar Vorräte für das Schiff zusammen suchen. Hier ist die Liste
```

> 1. Ok werde ich machen. `[QUEST UPDATE]`  
**Questlog** *Hole die Vorräte von der Liste aus den Kisten um Lager bei der Versammlungshalle und bringe es zu Kapitän Mafei.*  
Spieler erhält [Item Liste für Vorräte](#liste-für-vorräte)

...

`Mafei: Hast du die Vorräte?`

> 1. Ja hier hast du sie. `QUEST UPDATE` [Vorräte für das Schiff](#vorräte-für-das-schiff)  
**Questlog** *Gehe zurück zu Bürgermeister Roshik in der Versammlungshalle*  

`Mafei: Vielen Dank. Nun geh zurück zum Bürgermeister, er hat bestimmt noch mehr Aufgaben für dich.`

> 2. Mir fehlen noch ein paar Vorräte.

`Mafei: Dann solltest du dich beeilen.`

> Weiter bei [NPC Roschik](#vorräte-für-das-schiff-3)

#### Ausrüstung

> Hält eine Angel in der Hand

#### Standort

```yml
x: 5
y: 65
z: -92
world: Ankanor
```

## Items

### Liste für Vorräte

Ein Pergament worauf die Liste der Vorräte geschrieben ist, die der Spieler für die Quest [Vorräte für das Schiff](#vorräte-für-das-schiff) benötigt.

```yml
name: Liste für Vorräte
type: Quest
quality: COMMON
item: PAPER
lore: Als Vorräte für das Schiff benötige ich 10 Getreide, 1 Fass Wasser, 10 Holzbretter und 10 Wolle. Gezeichnet Kapitän Mafei
max-stack-size: 1
```

### Getreide

Gewöhnliches Getreide so wie es fast überall auf den Feldern zu finden ist.

```yml
name: Getreide
type: Rohstoff
quality: COMMON
item: WHEAT
lore: Gewöhnliches Getreide so wie es fast überall auf den Feldern zu finden ist.
max-stack-size: 64
```

### Wolle

Diese Wolle ist schon verarbeitet, ist überall als Rohstoff zu finden.

```yml
name: Wolle
type: Rohstoff
quality: COMMON
item: WOOL
lore: Diese weiche, verarbeitete Wolle hat diverse Einsatzmöglichkeiten. Und sie ist ultra weich.
max-stack-size: 64
```

### Fass Wasser

Dieses klare Wasser wurde in einem Fass gesammelt für den Transport.

```yml
name: Fass Wasser
type: Rohstoff
quality: COMMON
item: WATER BUCKET
lore: Klares Wasser in einem Fass, sehr schwer, aber sehr erfrischend.
max-stack-size: 1
```

### Holzbrett

Dieses Holzbrett ist verarbeitet, aber gewöhnlich und überall zu finden.

```yml
name: Holzbrett
type: Rohstoff
quality: COMMON
item: SPRUCE WOOD PLANK
lore: Ein gewöhnliches Holzbrett.
max-stack-size: 64
```

## Mobs

nicht vorhanden

## Belohnung

[Vorräte für das Schiff](#vorräte-für-das-schiff)  
> 5 Heller  


## Referenzen

Vorquest: [Ein neuer Start](../1-ein-neuer-start/README.md)
Folgequest: [Aufstieg zum Tianbaum](../3-aufstieg-zum-tianbaum/README.md)