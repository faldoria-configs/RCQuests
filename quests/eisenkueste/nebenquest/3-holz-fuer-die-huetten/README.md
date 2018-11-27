# Holz für die Hütten


> **Anmerkung:** Items überprüfen, Holz/Wolle Farbe? Kiesflohfleisch?

Zimmermann Akisk steht im Lager, das die schiffbrüchigen Ankanorer aufgebaut haben. 

## Ablauf

1. Der Spieler spricht Akisk an und redet mit ihm.
2. Akisk schickt ihn an den Strand um Holz, Teile des Wracks zu holen, die angeschwemmt wurden. Zusätzlich noch anderes Material.
3. Der Spieler sammelt sie Sachen und bekommt eine kleine Belohnung

## Vorraussetzungen

 - lvl 2
 - Waffe aus Ankanor

## Aufgaben

1. Sammle Holz und Wolle für die Hütten
2. Kehre zu Zimmermann Akisk zurück


## Questdialoge

### 1.Sammle Holz für die Hütten

```yml
Spieler: Wo sind wir hier, was machen wir hier?
Akisk: Du hast also auch überlebt. Freu dich aber nicht zu früh darüber.
Spieler: Warum sollte ich das nicht tun, Najtiss sei Dank, dass ich dem Meer entkommen bin. 
Akisk: Najtiss, als wenn der irgendetwas damit zu tun hat. Aber wie dem auch sei, der Hauptmann hat mir etwas befohlen und dafür brauche ich deine Hilfe.
Spieler: Was kann ich für dich tun?
Akisk: Wir brauchen Material, damit ich unser Lager weiter befestigen kann und du sollst es für mich besorgen.
Spieler: Klingt als könnte das etwas Abwechslung in meinen Tag bringen.
Akisk: Ist aber ganz einfach, am Strand findest du angeschwemmte Teile des Schiffes, die können wir brauchen. Suche nach Holz, aber auch anderen Materialien, Wolle vom Segel oder sowas. 
```

> 1. Vielleicht später. [Ende]
> 2. Ok, ich werde das Material besorgen.

Weiter mit #2

`[Quest START]` [1. Holz für die Hütten](#holz-fuer-die-huetten)

`**QuestLog:**`  *Sammle am Strand 10 Holzbretter und 10 Wolle.*

Der Spieler sammelt die erforderlichen Materialien.


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

1. Brauchst du was von mir? Ich habe nichts übrig.
2. Wie gut, dass du soviel Holz gebracht hast, jetzt wird uns bald nicht mehr frieren. 

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

### Ausgebleichte Wolle

Wolle, die vielleicht einmal Teil des Segels war.

```yml
name: Ausgebleichte Wolle
type: QUEST
quality: COMMON
item: light_gray_wool
lore: Ausgebleichte Wollfetzen.
max-stack-size: 64
```

### Treibholz

Angeschwemmt und weiß, trotzdem kann man's brauchen!

```yml
name: Treibholz
type: ROHSTOFF
quality: COMMON
item: birch_planks, stripped_birch_wood (1.13)
lore: Dieses Holz ist etwas feucht.
max-stack-size: 64
```

### Kiesflohfleisch

```yml
name: Gebratenes Kiesflohfleisch
type: ROHSTOFF
quality: COMMON
item: rotten_flesh   <----- Checken, ob das nicht schon was anderes ist
lore: Man kann es essen.
max-stack-size: 64
```



## Belohnung: 

Gebratenes Kiesflohfleisch (32 Stück)
Weitere Belohnung überprüfen (Vervollständigen einer Rüstung)
