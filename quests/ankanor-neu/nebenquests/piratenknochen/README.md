# Piratenknochen <!-- omit in toc -->
Issue #98

## Noch zu tun/Probleme

Koordinaten des Wegtelportierens neu setzen
Skin überprüfen und hochladen

## Ablauf

1. Start: Spieler nähert sich Genam aufgrund der Quest von Sakros [Schmied Sakros](../schmied-sakros/README.md)
2. Spieler spricht NPC [Genam](#Genam) an dieser lässt Spieler zunächst nicht weiter gehen.
3. Nach eienem kurzen Dialog, in welcher der Spieler erklärt, dass er für den Schmied in die Höhle muss
4. Gibt Genam ihm auch noch eine Aufgabe `Questbeginn` [Piratenknochen](#piratenknochen)
5. Spieler tötet die geforderten 10 Skelette und erledigt im besten Fall auch noch die Quests des Schmieds.
6. Ende: Beim Verlassen der Höhle und dem Ansprechen von Genam schließt der Spieler die Quest ab. `Questende` [Piratenknochen](#piratenknochen) und erhält eine [Belohnung](#Belohnung)
 
## Übersicht

## Vorraussetzungen

NQ: [Schmied Sakros](../schmied-sakros/README.md)
insbesondere die 1. Quest: [Eisen für die Schmiede](../eisen-fuer-die-schmiede/README.md)

## Aufgaben

### `Dialog 1`

**Genam:** `Halt, kein Zutritt!`   
Aber ich habe die Genehmigung des Schmiedes. Ich soll in die alten Kisten dort drunten schauen.   
**Genam:** `Des Schmiedes? Er braucht wohl Eisen, braucht die alten, rostigen Schwerter von da unten. Nun, dort warten aber Skelette auf Unglückliche, die in die Höhle müssen.`   
Oje, ich habe schon davon gehört, aber nicht gedacht, dass dies diese höhle ist..und jetzt?   
**Genam:** ` Wenn der Schmied seine Schwerter will, musst du sie wohl oder übel da unten rausholen. Dann könntest du auch gleich, wenn du schon da bist ein paar von diesen Skeletten für mich zu Knochenmehl verarbeiten, wie wäre das?`   

1. Muss ich ja wohl, wenn ich da runter muss...
2. Ich glaube, ich muss erst noch mal hintern Busch.   
   **Genam:** `*lacht laut auf* Mach das, aber ich kann mich darauf verlassen, dass du gehst?`   
   Klar doch, was bleibt mir anderes übrig?

`[QUEST START]` Piratenknochen](#piratenknochen)   
**QuestLog:** *Töte in der Höhle für die Wache Genam 10 Skelette.*

**Der Spieler erledigt die Aufgabe und kehrt zum Questgeber zurück.**

### `Dialog 2`

**Genam:** ` Aus der Tatsache, dass du noch lebst, und aus der, dass du die Schwerter hast, nehme ich an, dass die Skelette tot sind?`   
Ja, sie sind tot… oder was auch immer. Knochenstaub, wie du es gewünscht hast.   
**Genam:** ` Vielen Dank, dass du dich darum gekümmert hast.`   
Musste ich ja wohl…

`[QUEST ENDE]` Piratenknochen](#piratenknochen)

> Spieler kann zu [NPC Sakros](../schmied-sakros/README.md) zurückkehren

   
  



## NPCs

## `Genam`

Er bewacht die Höhle auf der südwestlichen Seite der Insel, so dass keiner dort hineingeht bevor er nicht bereit ist.


### Standartsätze  
#### Vor der Quest
Wenn Spieler die benötigte Quest noch nicht hat und sich der Höhle nähert passiert Folgendes:

**Genam:** ` Halt, in dieser Höhle lauern böse Skelette, du solltest dort nicht hinein!`

** Der Spieler wird außerdem nach folgenden Koordinaten teleportiert: **

```yml
x: 
y: 
z: 
world: Ankanor
``` 

#### Während der Quest

**Genam:** `Beeile dich etwas, dieses Geklapper nervt langsam.`   
*du murmelst:*  Und ich dachte wegen dem Adlatus...

### Nach der Quest

1. **Genam:** `Ich frage mich noch immer wie diese Skelette hierher gekommen sind und vorallem warum? Ob das eine Prüfung ist?`   
   Die Ältesten meinen, das hängt mit der Ankunft von A.. du weißt schon wer.. zusammen.   
   **Genam:** `Agnatus? Würde mich nicht wundern.`   

2.  **Genam:** `Vielen Dank nochmal das du diese Ausgeburten von Skeletten getötet hast.

### Ausrüstung

Schwert in der Hand

skin ID
### Standort

```yml
x: 
y: 
z: 
world: ankanor
```

## Items

### Rostiges Schwert

In Kisten zu finden, dropt aber auch von den Skeletten

```yml
name: Rostiges Schwert
type: QUEST
quality: COMMON
item: IRON SWORD
lore: Ein vom Meersalz angerostetes Schwert.
max-stack-size: 1
```

### Eisenbarren

In Kisten zu finden, dropt aber auch von den Skeletten

```yml
name: Eisenbarren
type: QUEST
quality: COMMON
item: IRON INGOT
lore: Dieser Eisenbarren ist völlig angerostet, ob der noch verwendet werden kann ist fraglich.
max-stack-size: 64
```


## Mobs
### Skelett

```yml
name: Verwittertes Skelett
type: skeleton
min-level: 1
max-level: 2
min-health: 80
max-health: 88
min-damage: 3
max-damage: 5
spawn-chance: 1.0
spawning-naturally: false
loot-table: 
aggro: true
```

```yml
x: 
y: 
z:
world: ankanor
radius: 
```
#### Ausrüstung
?



## Belohnung

[Piratenknochen](#piratenknochen)
> 5 Heller  
> 5 exp


## Referenzen

[Schmied Sakros](../schmied-sakros/README.md)
insbesondere die 1. Quest: [Eisen für die Schmiede](../eisen-fuer-die-schmiede/README.md)

## Issues


