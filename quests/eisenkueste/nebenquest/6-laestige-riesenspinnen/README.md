# Lästige Riesenspinnen

Issue 17

> Relativ stark im Text verändert

Questgeber **Alrix** Er ist ein junger Kaishi, der Bergmann werden möchte. Dem steht jedoch entgegen, dass er Spinnen fürchtet - und die sind oft in Minen anzufinden. 


## Übersicht
* [Übersicht](#Übersicht)
* [Noch zu klären](#noch-zu-klären)
* [Ablauf](#ablauf)
* [Voraussetzungen](#voraussetzungen)
* [Questdialog](#questdialog)
  * [Dialog 1](#dialog-1)
  * [`[Quest START]` 1. Lästige Riesenspinnen](#quest-start-1-lästige-riesenspinnen)
  * [`[HIDDEN Objective]` [2.Spinnenmutter]](#hidden-objective-2spinnenmutter)
  * [`[Objective START]` [3. Kehre zu Alrix zurück]](#objective-start-3-kehre-zu-alrix-zurück)
* [Npc](#npc)
  * [Alrix](#alrix)
    * [Standartsätze](#standartsätze)
      * [Vor der Quest](#vor-der-quest)
      * [Während der Quest](#während-der-quest)
      * [Nach der Quest:](#nach-der-quest)
    * [Ausrüstung](#ausrüstung)
    * [Standort](#standort)
* [Items:](#items)
  * [Drops](#drops)
    * [Spinnenfleisch](#spinnenfleisch)
    * [Fäden von den Spinnen](#fäden-von-den-spinnen)
    * [Die Spinnenmutter dropt einen Stack Fäden](#die-spinnenmutter-dropt-einen-stack-fäden)
    * [Spinnenseide](#spinnenseide)
  * [Belohnung](#belohnung)
    * [Alriks Geschenk](#alriks-geschenk)
* [Referenzen](#referenzen)

## Noch zu klären

Koords müssen noch neu esetzt werden

## Ablauf

1. Spieler spricht Alrix an
2. Alrix bittet den spieler, Spinnen in der Mine zu töten
3. Der Spieler geht zum Spinnen töten
4. Eine weitere Quest wird angeboten: Spinnenmutter suchen und töten
5. Der Spieler kehrt zu Alrix zurück


## Voraussetzungen

HQuest [was ist passiert](.../1-was-ist-passiert/README.md) angenommen

Ausrüstung

Waffe



## Questdialog

### Dialog 1

---> bei 5 Block Entfernung

*Du läufst an einem jungen Kaishi vorbei, der recht bekümmert aussieht*   
Alrix, was schaust du denn so bekümmert?
**Alrix:** ` <Name des Spielers>, findest du Spinnen genau so widerlich und schrecklich wie ich?`

1.  Ja, ich kann sie auch nicht leiden. Von mir aus können sie ruhig als Vogelfutter dienen.   
    **Alrix:** ` Gut, dann kannst du mir ja einen kleinen Gefallen tun und ein paar Spinnen für mich entfernen.`

2.   Ne, ich finde Spinnen interessant und würde auch gerne eine als Haustier haben! Manche sind so schön gefärbt.  
**Alrix:** ` Ahh...nunja….egal... aber bitte hilf mir bei ...du musst für mich etwas erledigen. Bitte!`   
Ja rück raus damit!  
**Alrix:** ` Du musst für mich Spinnen.. entfernen. `



***************

**Weiter mit #1 und #2:**

Spinnen entfernen? Du meinst töten! Reden wir von normalen kleinen Spinnen?  
**Alrix:** ` Nein nein...ich rede von Riesenspinnen. Diese sind viel, viel größer und abscheulicher als die kleinen mickrigen da.`   
Aber warum stören die Spinnen dich? Ich habe in der Umgebuung des Lagers keine gesehen.        
**Alrix:** ` Die sind auch nicht in der Nähe des Lagers, sondern in der Mine dahinten`  
**Alrix** `* zeigt in Richtung Süden*`           
**Alrix:** ` Da ist ein kleines, verlassenens Dörfchen, und dahinter eine Mine, und du weißt ja vielleicht, dass ich Bergmann werden will. Und ich soll nachsehen, ob es dort noch Eisen gibt, oder ob die Mine erschöpft ist. Aber die Spinnen...` 

1. Oh Alrix, das tut mir leid für dich, aber an die Riesenspinnen traue ich mich auch nicht  
  `[Ende]`
2. In Ordnung, ich helfe dir!  Ich werde mich auf den Weg machen und die Plage beseitigen.  
  **Alrix:** `Danke, du bist ein guter Freund.`

### `[Quest START]` [1. Lästige Riesenspinnen](#laestige-riesenspinnen)

`**QuestLog:**` *Gehe zur Mine hinter dem Dorf, suche das Nest und töte die Spinnen.*

* Töte [20] Spinnen

** Der Spieler tötet Spinnen, kommt er jedoch in der Höhle zu den Koordinaten [3283, 108, -2577] erhält der Spieler die Mitteilung: **

*Vielleicht gibt es hier eine Spinnenkönigin die all diese wiederlichen Riesenspinnen produziert.*

### `[HIDDEN Objective]` [2.Spinnenmutter]

`**Questlog:**`  *Töte die Brutmutter*

> Während der Quest hat der Spieler auch noch die Möglichkeit die Brutmutter zu töten.

Wenn 20 der normalen Spinnen auch getötet wurden endet auch  
`[Quest Ende]` [1. Lästige Riesenspinnen](#laestige-riesenspinnen)

### `[Objective START]` [3. Kehre zu Alrix zurück]

`Questlog'` *Kehre zu Alrix zurück*

Spieler kehrt zu Alrix zurück.

**Alrix:** `Hast du die Plage beseitigt?`  
Ja, das habe ich gemacht.  
**Alrix:** `Danke, ich bin so froh, jetzt kann ich meine Arbeit erledigen.`

`[Quest Ende]` [1. Lästige Riesenspinnen](#1-laestige-riesenspinnen)

**Je nach dem, ob die Quest [Spinnenmutter](#spinnenmutter) auch erledigt wurde oder nicht**

Sei froh, dass du da nicht hineingegangen bist, da waren nicht nur die großen Spinnen, sondern eine riesige dazu. Die habe ich auch gleich mit platt gemacht.
**Alrix:** `Was hast du? Du hast die Brutmutter getötet?`

1. Ja, es schien mir logisch diese auch zu töten.. wenn schon, denn schon...
  **Alrix:** `Da bin ich aber froh....`  
2. Nein, ich wollte sie nicht ganz ausrotten, aber wenn du Probleme bekommen solltest, dann helfe ich dir wieder.  
  **Alrisk:** `Wenn du meinst..`

**Weiter für #1 und #2**

**Alrisk:** `Danke nochmals für deine Hilfe, ich kann dir leider nur eine Kleinigkeit als Dank geben, ich hoffe, es gefällt dir.`

**Der Spieler erhält einen Smaragdblock als Belohnung.**

`[Quest Ende]` [3. Kehre zu Alrix zurück](#3-kehre-zu-alrix-zurueck)

## Npc

### Alrix

**Alrix**  ist ein junger Kaishi, der Bergmann werden möchte. Dem steht jedoch entgegen, dass er Spinnen fürchtet - und die sind oft in Minen anzufinden. Er ist ein eher schmächtiger Typ, jedoch voller Ergeiz, was seinen gewünschten Beruf anbelangt. Er ist ein netter Kerl, der jedem gerne hilft, der ihn fragt.

#### Standartsätze

##### Vor der Quest

keine

##### Während der Quest

>1.  Quest 1 : Lästige Spinnen   

**Alrix:** ` <Name des Spielers>, hast du die Spinnen schon alle erledigt?`   
Nein, das waren zu viele für einmal, aber ich gehe nochmals hin. 

> 2. Quest 2 : Spinnenmutter

**Alrix:**  ` <Name des Spielers>, hast du die Spinnen schon alle erledigt?`   
Nein, da gibt es noch einetwas größeres Problem, aber von dem erzähle ich dir später. 


##### Nach der Quest:
**Alrix:** ` Hallo <Name des Spielers>, wie geht es dir? Hast du inzwischen noch weitere von diesen schrecklichen Gefahren hier an der Eisenküste beseitigt?`   
Naja, schon, es kommt mir aber selbst komisch vor, dass ich jetzt so gut mit meiner Waffe umgehen kann, aber ich bin noch lange kein Meister.    
*+Alrix:** ` Das wird schon noch, ich bin froh, dass du da bist.`  


#### Ausrüstung 

Eisenspitzhacke in der Hand

Skin fertig
ID 35

#### Standort

```yml
x: 3631
y: 65
z: -2807
world: Faldoria, Eisenküste

``` 

## Items:

keine Questspezifischen

### Drops

#### Spinnenfleisch

```yml
name: Spinnenfleisch
type: QUEST
quality: COMMON
item: chicken
lore: Schmeckt wie Hühnchenfleisch
max-stack-size: 64
```

#### Fäden von den Spinnen

```yml
name: Spinnenfaden
type: QUEST
quality: COMMON
item: string
lore: Diese Seidenfäden sind besonders dick.
max-stack-size: 64
```

#### Die Spinnenmutter dropt einen Stack Fäden

#### Spinnenseide

```yml
name: Spinnenseide
type: QUEST
quality: COMMON
item: cobweb
lore: Diese Seidenfäden sind besonders dick.
max-stack-size: 64
```
### Belohnung

#### Alriks Geschenk

```yml
name: Alriks Geschenk
type: QUEST
quality: COMMON
item: emerald_block 
lore: Von Alrik abgebaut.
max-stack-size: 64
```

## Referenzen



    


     


