# Ein neuer Start

Sobald der Spieler auf den Server kommt landet er in einem Haus mitten im Dorf, wenn er das Gebäude verlässt hält ihn Shicho auf und teilt dem Spieler mit sich in der Versammlungshalle beim Bürgermeister Roshik zu melden.

## Ablauf

1. Start: Spieler verlässt das Gebäude und trifft Shicho, Spieler wird eingefroren
2. [NPC Shicho](#Shicho) spricht Spieler an und gibt ihm die Info in die Versammlungshalle zu gehen und mit [NPC Roschik](#Roschik) zu sprechen
3. Spieler geht in die Versammlungshalle und spricht Roshik an.
3. Roshik erklärt die Lage und gibt eine neue Aufgabe an den Spieler.

## Vorraussetzungen

> nicht vorhanden

## NPCs

### Shicho

Dieser Kaishi ist die Rechtehand des Bürgermeisters, er ist ein Besserwisser und mischt sich ständig in andere Angelegenheiten ein.

### Dialoge

#### Standartsätze  

**Vor der Quest**
1. Nicht vorhanden

**Während der Quest**  
1. Beweg dich jetzt zur Versammlungshalle, es ist sehr wichtig.

**Nach der Quest**
1. Enttäusche uns nicht, jetzt muss jeder anpacken bevor die Katastrophe beginnt. Auch du!
2. Wenn ich mich nicht irre hast du was zu tun!
    
#### Quest Dialog

##### Ein neuer Start

```yml
Shicho: Hey [Spielername], was machst du noch hier, der Bürgermeister hat zu einer Versammlung gerufen. [Klick auf die Antwort]
Spieler: Wieso, was ist los? Gab es wieder Ärger im Lager?
Shicho: Schön wär’s, folge dem Weg links zur Versammlungshalle, du kannst es nicht verfehlen. Mach schnell die anderen warten schon. 
Spieler: Und was mache ich dann?
Shicho: Nimm Junnar mit, sie müsste auch schon längst los. Wenn ihr angekommen seid, sprecht sofort mit unserem Bürgermeister Roshik. 
> Grauer Text: Du kannst mit einem NPC per Rechtsklick sprechen
Spieler: Ok, ich mache mich gleich auf den Weg.
Shicho: Bevor du gehst, vergiss nicht das du deine Aufgaben im Journal notiert hast. Wenn du es weggesteckt hast, kannst du es wieder mit /journal in dein Inventar holen. Und nun los geh zur Versammlungshalle.
```
> 1. Ich bin ja schon unterwegs. [Klick auf die Antwort] `[QUEST START]` [Ein neuer Start](#ein-neuer-start)  
**QuestLog:** *Begib dich zur Versammlungshalle und sprich mit Roschik*

...


Weiter bei [NPC Roschik](#Roschik)

#### Ausrüstung

#### Standort

```yml
x: 52
y: 82
z: -40
world: Ankanor
```

### Roschik

Er ist der Bürgermeister des Dorfes in dem die Kaishi wohnen. Roschik ist ein sehr gütiger Kaishi und wird von allen Respektiert.

### Dialoge

#### Standartsätze  

**Vor der Quest**
1. Nicht vorhanden

**Während der Quest**  
1. nicht vorhanden

**Nach der Quest**
1. Es ist sehr wichtig das du keinen Unsinn machst im Moment, wir brauchen jeden jetzt um uns vorzubereiten.
2. Ich hoffe du verstehst das ich gerade keine Zeit habe für dich.
    
#### Quest Dialog

##### Ein neuer Start

```yml
Roschik: Endlich hast du es auch geschafft.
Spieler: Was ist los? Warum sind alle so aufgeregt? Hat Kozas wieder einmal einen Riesenfisch gefangen? Wenn ja, lasst mich damit in Ruhe.
Roschik: Nein! Wir haben erfahren, dass Agnatus auf dem Weg hierher sein könnte. Berichten zufolge hat er Schiffe in unsere Richtung entsandt.
Spieler: Agnatus? Wer ist das nun wieder?
Roschik: Hast du die letzten Monate geschlafen? Agnatus der Nekromant, er terrorisiert das Festland mit seinen Untoten und Schergen.
Spieler: Ach der, und was machen wir jetzt?
```
> `[QUEST ENDE]` [Ein neuer Start](#ein-neuer-start)  

Weiter bei [Vorräte für das Schiff](../2-vorraete-fuer-das-schiff/README.md)

#### Ausrüstung

#### Standort

```yml
x: 100
y: 82
z: -85
world: Ankanor
```

## Items

nicht vorhanden

## Mobs

nicht vorhanden

## Belohnung

[Ein neuer Start](#ein-neuer-start)  
> 2 Heller  


## Referenzen

Folgequest [Vorräte für das Schiff](../2-vorraete-fuer-das-schiff/README.md)