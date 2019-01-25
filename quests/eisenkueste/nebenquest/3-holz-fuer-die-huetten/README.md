# Holz für die Hütten <!-- omit in toc -->

Issue 13

## Noch zu tun


>  Belohnung mit anderen Quests abstimmen

Zimmermann [Akisk](#akisk) steht im Lager, das die schiffbrüchigen Ankanorer aufgebaut haben. 


## Übersicht <!-- omit in toc -->

- [Noch zu tun](#noch-zu-tun)
- [Ablauf](#ablauf)
- [Vorraussetzungen](#vorraussetzungen)
- [Aufgaben](#aufgaben)
- [Questdialoge](#questdialoge)
  - [1.Sammle Holz für die Hütten](#1sammle-holz-f%C3%BCr-die-h%C3%BCtten)
   
- [NPCs](#npcs)
     - [Akisk](#akisk)
         - [Standartsätze](#standartsaetze)
            - [Vor der Quest](#vor-der-quest)
            - [Während der Quest](#waehrend-der-quest)
            - [Nach der Quest](#nach-der-quest)
         - [Ausrüstung](#ausruestung)
         - [Standort](#standort)
-  [Mobs](#mobs)
   
   keine
  
-  [Items](#items)
  
     - [Schiffsplanken](#schiffsplanken)
     - [Rotes Segeltuch](#rotes-segeltuch)
     - [Kiesflohfleisch](#kiesflohfleisch)
- [Belohnung](#belohnung)

## Ablauf

1. Der Spieler spricht Akisk an und redet mit ihm.
2. Akisk schickt ihn an den Strand um Holz, Teile des Wracks zu holen, die angeschwemmt wurden. Zusätzlich noch anderes Material.
3. Der Spieler sammelt sie Sachen und bekommt eine kleine Belohnung

## Vorraussetzungen

HQ [Was ist passiert](#1.-was-ist-passiert?)  abgeschlossen
HQ `[QUEST UPDATE]` [Was ist passiert](#1.-was-ist-passiert?)
> **QuestLog:** *Erkunde die Gegend und schau dir das Licht am Berg im Westen an. Finde heraus ob dort jemand lebt.*  angenommen

- lvl ?
- Waffe aus Ankanor

## Aufgaben

1. Sammle Holz und Wolle für die Hütten
2. Kehre zu Zimmermann Akisk zurück


## Questdialoge

### 1.Sammle Holz für die Hütten

 Hey Akisk, schön, dich zu sehen.
**Akisk:** ` Du hast also auch überlebt. Freu dich aber nicht zu früh darüber.`  
Warum sollte ich das nicht tun, dem Baum sei Dank, dass ich dem Meer entkommen bin. 
Akisk: Der Baum, als wenn der irgendetwas damit zu tun hat. Aber wie dem auch sei, der Hauptmann hat mir etwas befohlen und dafür brauche ich deine Hilfe.
Spieler: Was kann ich für dich tun?
Akisk: Wir brauchen Material, damit ich unser Lager weiter befestigen kann und du sollst es für mich besorgen.
Spieler: Klingt als könnte das etwas Abwechslung in meinen Tag bringen.
Akisk: Ist aber ganz einfach, am Strand findest du angeschwemmte Teile des Schiffes, die können wir brauchen. Suche nach Holz, aber auch anderen Materialien, Wolle vom Segel oder sowas. 
```

> 1. Vielleicht später. `[Ende]`

> 2. Ok, ich werde das Material besorgen.

**Weiter mit #2**

`[Quest START]` [1. Holz für die Hütten](#holz-fuer-die-huetten)

`**QuestLog:**`  *Sammle am Strand 10 Holzbretter und 10 Wolle.*

Der Spieler sammelt die erforderlichen Materialien.

`[Ende]`



`[Quest START]` [2. Kehre zu Zimmermann Akisk zurück](#kehre-zu-zimmerman-akisk-zurueck)

`**QuestLog:**`   *Kehre zu Zimmermann Akisk zurück.*

Spieler kehrt mit dem Material zu Akisk zurück.
Akisk spricht den Spieler an, sobald er in Reichweite von 2 Blocks ist. 


```yml
Akisk: Da bist du ja wieder, hast du die Sachen, die ich brauche? Der Hauptmann schaut mich schon zornig an.
Spieler: Ich habe was du brauchst.
NPC: Ich danke dir. 
NPC: Endlich können wir mit der Arbeit beginnen. Hier ist eine kleine Belohnung.
Spieler: War kaum der Rede wert. Dank dir!
```
`[Ende]`


## NPC

### Zimmermann Akisk

Beschreibung: Akisk ist ein einfacher Mann, der gut mit einer Axt umgehen kann und geschickt ist im Bauen von Hütten und groben Möbeln. 

#### Standartsätze

##### Vor der Quest

Akisk: Solltest du nicht erst mit dem Hauptmann reden?

##### Während der Quest/Aufgabe #1

> 1. 
```yml
Akisk: Hast du schon alles zusammen?
Spieler: Ich hoffe der Hauptmann wird nicht noch zorniger, denn ich habe das Material noch nicht.
Akisk: Dann beeil dich bitte.
```

> 2. Schon fertig? Nein, das reicht nicht, such noch weiter!

> 3. Kannst du nicht zählen? Du hast viel zu wenig!

##### Nach der Quest (#2)

> 1. Brauchst du was von mir? Ich habe nichts übrig.
   
> 2. Wie gut, dass du soviel Holz gebracht hast, jetzt wird uns bald nicht mehr frieren. 

#### Ausrüstung

Skin hat er (neu machen mit 'Holzfällerhemd', ohne Schulterklappen)
Holzaxt in der Haupthand, Holzblock in der Nebenhand


#### Standort

```yml
x: 3663
y: 65
z: -2823
world: Faldoria, Eisenküste
``` 

## Items

### Rotes Segeltuch

Wolle, die vielleicht einmal Teil des Segels war.

```yml
name: Rotes Segeltuch
type: QUEST
quality: COMMON
item: red_wool
lore: Dieser rote Wollstoff gehörte mal zu einem Segel
max-stack-size: 64
```

### Schiffsplanken


```yml
name: Schiffsplanken
type: ROHSTOFF
quality: COMMON
item: spruce_wood
lore: Dieses Holz ist etwas feucht.
max-stack-size: 64
```

### Kiesflohfleisch

```yml
name: Gebratenes Kiesflohfleisch
type: ROHSTOFF
quality: COMMON
item: rotten_flesh   
lore: Man kann es essen, wenn es sein muss.
max-stack-size: 64
```



## Belohnung: 

Gebratenes Kiesflohfleisch (32 Stück)
Weitere Belohnung überprüfen (Vervollständigen einer Rüstung)
