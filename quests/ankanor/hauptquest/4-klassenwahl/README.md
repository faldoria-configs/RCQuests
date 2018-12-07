# Klassenwahl

Oben auf dem Tianbaum angekommen trifft er Lious, einen verstorbenen einstigen Helden. Lious lässt den Spieler nach ein paar kurzen Texten seine Klasse wählen und gleich ausprobieren.

## Ablauf

1. Start: Der Spieler hat durch die [HQ Aufstieg zum Tianbaum](../3-aufstieg-zum-tianbaum/README.md) Lious schon angesprochen.
2. Zunächst soll der Spieler die 5 Ritualsteine anklicken und deren Worte lauschen. 
3. Darauffolgend soll er seinen Pfad (Klasse) wählen.
4. Sobald er das getan hat soll er seine Fähigkeiten an Spinnen ausprobieren, dort wird er hinteleportiert.
5. Nachdem töten der Spinnen soll der Spieler zu Jamos.
6. Erhält [Belohnung](#Belohnung)

## Vorraussetzungen

> 1. Erledigen der [HQ Aufstieg zum Tianbaum](../3-aufstieg-zum-tianbaum/README.md)

## NPCs

### Lious

Lious ist der Geist eines Verstorbenen Helden, er ist eine Art Schutzpatron für die Kaishi geworden.

### Dialoge

#### Standartsätze  

**Vor der Quest**
1. nicht vorhanden

**Während der Quest**  
1. Habt ihr schon den Worten der Ritualsteine gelauscht? Es ist wichtig das ihr genau zuhört.

**Nach der Quest**
1. Jamos wird euch weiterleiten auf eurem Pfad, verschwendet also keine Zeit.
2. Aus großer Macht folgt große Verantwortung!
    
#### Quest Dialog

##### Klassenwahl

```yml
Lious: Denn du wirst die Wahl zwischen 5 Pfaden des Kampfes haben. Jeder Pfad bestimmt eine Klasse. Eine Lebensweise!
Lious: Du wirst die Wahl haben zwischen dem Weg des Kriegers,  Assassinen,  Elementaristen, Klerikers oder dem des Waldläufers. Jeder Pfad ist einzigartig, wählt also weise. 
Spieler: Was muss ich tun? Wie wähle ich meinen Pfad?
Lious: Gehe hinüber zu den Ritualsteinen, diese werden dir die einzelnen Pfade weiter erläutern, sobald du alle fünf Steine berührt hast, komme zu mir zurück.
```
> `[QUEST START]` [Klassenwahl](#klassenwahl)  
**Questlog**: *Berühre die 5 Ritualsteine und höre dir genau an was sie zu sagen haben.*

> In der Krone sind 5 Ritualsteine (Wolleblöcke) verteilt. Wenn der Spieler diese für die Quest anklickt soll folgendes ausgegeben werden.  


| Ritualstein | Beschreibung |
| ------ | ------------ |
|Krieger (Rot):| Krieger sind Bollwerke aus Muskeln und Stahl, ihre wuchtigen Schwerthiebe lehren Gegnern das Fürchten. Sie stellen sich oft zwischen den Feind und die eigene Gruppe.  |
| Kleriker (Weiß):| Kleriker sind die gute Seele einer Gruppe, sie achten auf das Wohlbefinden jedes Einzelnen. Die Stärkung und Segnung der Gruppe gehören ebenso zu ihren Aufgaben, wie das Versorgen von Wunden während des Gefechts. | 
| Elementarist (Lila):| Elementaristen gebieten, wie ihr Name schon sagt, über die Magie. Ihre Fernkampfangriffe sind stark und sie verfügen über Fähigkeiten, andere in ihrem Tun zu kontrollieren.  |
| Assassine (Gelb):| Assassinen nutzen den Schatten, um ihrem Gegner ihre Waffen im Nahkampf in den Körper zu schlagen. Gifte und Tarnung sind ihr Spezialgebiet.  |
| Waldläufer (Braun):| Waldläufer leben im Einklang mit der Natur, ihre Angriffe mit dem Bogen sind meist tödlich. In Wäldern fühlen sie sich heimisch und ihre Kraft ist dort um ein vielfaches erhöht.|

```yml
Lious: Hast du dich entschieden welchen Pfad du folgen möchtest?
```
> 1. Nein, ich bin mir noch unsicher.  
`Lious: Dies ist eine wichtige Entscheidung, also lass dir Zeit...aber nicht zu viel.` `[Ende]`
> 2. Ja das habe ich!  
`Lious: Bist du dir ganz sicher?`

> 1. Ja ich bin mir ganz sicher.   
`Lious: Dann sage mir,  welchen Pfad du wählst. Den des mutigen Kriegers, des listigen Assassinen, des selbstlosen Klerikers, des naturverbundenen Waldläufers oder gar den Pfad des wissbegierigen Elementaristen.`
> 2. Vielleicht sollte ich nochmal überlegen. `[Ende]`

Nun kann der Spieler wählen.
> 1. Spieler: Ich wähle den Pfad des Kleriker
> 2. Spieler: Ich wähle den Pfad des Krieger 
> 3. Spieler: Ich wähle den Pfad des Waldläufer
> 4. Spieler: Ich wähle den Pfad des Elementaristen 
> 5. Spieler: Ich wähle den Pfad des Assassinen]  

`Lious: So sei es!`

> Spieler erhält nach der Wahl ersten Skill und die Klassenwaffe

| Klasse | Erhält |
| ------ | ------------ |
|Krieger:| [Stumpfes Schwert](#stumpfes-schwert) + |
|Assassine:| [Stumpfer Dolch](#stumpfer-dolch) + |
|Elementarist:| [Verwitterter Stab](#verwitterter-stab) + |
|Kleriker:| [Verwitterter Stab](#verwitterter-stab) + |
|Waldläufer:| [Verwitterter Bogen](#verwitterter-bogen) + |

```yml
Lious: Mache dich nun mit deiner neuen Fähigkeit vertraut und kehre dann zu mir zurück, damit du sie testen kannst.
``` 

> Tipps-Plugin:  
Öffne mit einem Rechtsklick und dem Item "Hotbar Menu" auf Slot 9 deiner Actionbar, in der Hand das Menü und ziehe den gewünschten Skill in die Actionbar auf Slot 3-8. Wenn du diesen Skill ausführen möchtest Wähle eine deiner Waffen, Slot 1+2 und drücke dann auf den gewünschten Skill in der Actionbar.

> `[QUEST UPDATE]` [Klassenwahl](#klassenwahl)  
**Questlog**: *Binde deine erste Fähigkeit auf deine Aktionsleiste, kehre dann zu Lious zurück*

> Nachdem der Spieler die Fähigkeit gebunden hat.

```yml
Lious: Ich freue mich für dich, nun testen wir deine neuen Fähigkeiten.
Spieler: Soll ich dich jetzt verprügeln?
Lious: Wie kommst du da drauf? Nein, ich hetze dir Spinnen auf den Hals.
Spieler: Iih nein, alles nur nicht das.
Lious: Du hast keine Wahl!
```
> `[QUEST UPDATE]` [Klassenwahl](#klassenwahl)  
**Questlog**: *Töte 3 freundliche Spinnen.*

> Spieler wird nach folgenden Koordinaten Teleportiert.

```yml
x: 17
y: 155
z: 13
world: Ankanor
```

> Dort tötet er die 3 [Mob Freundliche Spinne](#freundliche-spinne) und wird zurück zu Lious geportet.

```yml
x: 8
y: 183
z: 23
world: Ankanor
```

> Spieler muss Lious ansprechen

```yml
NPC: Sehr schön hast du das gemacht.
Spieler: Danke, war einfach. 
```

`[QUEST ENDE]` [Klassenwahl](#klassenwahl)  

> Weiter bei [HQ Weitere Ausbildung](../5-weitere-ausbildung/README.md)

<<<<<<< HEAD
## NPC
=======
## NPCs
>>>>>>> 7171580ff272d8c93e9b9a8101fc3f2547d6bf81

### Lious

#### Ausrüstung

#### Standort

```yml
x: 9
y: 183
z: 21
world: Ankanor
```

## Items

### Stumpfes Schwert

Dieses Stumpfe Schwert ist  für Krieger Anfänger.

```yml
name: Stumpfes Schwert
type: WEAPON
quality: COMMON
item: WOODEN SWORD
lore: Man könnte meinen es ist aus Holz so stumpf wie es ist.
max-stack-size: 1
```
```yml
binding: Bind on pickup
slot: onehanded
durability: 100
weeapon-type: Sword
damage: 1-2
attributes: none
```

### Stumpfer Dolch

Dieser Dolch ist für Assassinen Anfänger.

```yml
name: Stumpfer Dolch
type: WEAPON
quality: COMMON
item: WOODEN SWORD
lore: Man könnte meinen das es einem Zahnstocher gleicht, so stumpf wie es ist.
max-stack-size: 1
```
```yml
binding: Bind on pickup
slot: onehanded
durability: 100
weapon-type: Dagger
damage: 1-2
attributes: none
```

### Verwitterter Stab

Dieser Stab ist für Kleriker und Elementaristen Anfänger.

```yml
name: Verwitterter Stab
type: WEAPON
quality: COMMON
item: STICK
lore: Man könnte meinen das es ein einfacher Ast von einem Baum ist, so verwittert wie es ist.
max-stack-size: 1
```
```yml
binding: Bind on pickup
slot: twohanded
durability: 100
weapon-type: Staff
damage: 1-2
attributes: none
```

### Verwitterter Bogen

Dieser Bogen ist für Waldläufer Anfänger.

```yml
name: Verwitterter Bogen
type: WEAPON
quality: COMMON
item: BOW
lore: Man könnte meinen das es ein einfacher Ast mit einer Schnur, so verwittert wie es ist.
max-stack-size: 1
```
```yml
binding: Bind on pickup
slot: twohanded
durability: 100
weapon-type: Bow
damage: 1-2
attributes: none
```

## Mobs

### Freundliche Spinne (Worldspawn)

```yml
name: Freundliche Spinne
type: spider
min-level: 1
max-level: 2
min-health: 80
max-health: 88
min-damage: 3
max-damage: 5
spawn-chance: 1.0
spawning-naturally: false
loot-table: 
aggro: false
```

## Belohnung

[Klassenwahl](#klassenwahl)  
> 10 EXP  



## Referenzen

Vorquest: [Ein neuer Start](../3-aufstieg-zum-tianbaum/README.md)  
Folgequest: 