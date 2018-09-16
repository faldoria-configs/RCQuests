# Die Höhle der Skelette

Die Höhle befindet sich am südwestlichen teil des Tianbaumes und wird von Genam bewacht. Sie wird heimgesucht von Skeletten die eines Tages dort auftauchten. In der Höhle sind Ressourcen zu finden die der Schmied benötigt.

## Ablauf

1. Start: Spieler nähert sich Genam aufgrund der Quest von Sakros [dem Schmied](../2-der-schmied)
2. Spieler spricht [NPC Genam](#Genam) an dieser lässt Spieler zunächst nicht weiter gehen.
3. Nach eienem kurzen Dialog, in welcher der Spieler erklärt das er für den Schmied in die Höhle muss
4. Gibt Genam ihm auch noch eine Aufgabe `Questbeginn` [Skelette in der Höhle](#skelette-in-der-hoehle)
5. Spieler tötet die geforderten 10 Skelette und erledigt im besten Fall auch noch die Quests des Schmieds.
6. Ende: Beim verlassen der Höhle und dem Ansprechen von Genam schließt der Spieler die Quest ab. `Questende` [Skelette in der Höhle](#skelette-in-der-hoehle) und erhält eine [Belohung](#Belohung)

## NPCs

### Genam

Er bewacht die Höhle auf der südwestlichen Seite der Insel, sodass keiner dort hineingeht bevor er nicht bereit ist.

Wenn Spieler die benötigte Quest noch nicht hat und sich der Höhle nähert passiert folgendens
```yml
Genam: Halt, in dieser lauern böse Skelette du solltest dort nicht hinein!
```
Spieler wird außerdem nach (x: -16, y: 91, z: 54, world: Ankanor) teleportiert

#### Dialoge

##### Quest Dialoge

```yml
Genam: Halt, kein Zutritt!
Spieler: Aber ich habe die Genehmigung des Schmiedes.
Genam: Des Schmiedes? Er braucht wohl die alten, rostigen Schwerder von da unten. Nin, dort unten warten Skelette auf Unglückliche, die in die Höhle müssen.
Spieler: Oha, und jetzt?
Genam: Wenn der SChmied seine Schwerter will, musst du sie wohl oder übel da unten rausholen. Töte doch bitte ein paar von diesen Skeletten für mich, während du da bist.
```

> 1. Muss ich ja wohl, wenn ich da runter muss...
`[QUEST START]` [Skelette in der Höhle](#skelette-in-der-hoehle)
**QuestLog:** *Töte in der Höhle für die Wache Genam 10 Skelette.*

> Spieler erledigt die Aufgabe und kehrt zum Questgeber zurück

```yml
NPC: Aus der Tatsache, dass du noch lebst, und aus der, dass du die Schwerter hast, nehme ich an, dass die Skelette Tot sind?
Spieler: Ja, sie sind tot… oder was auch immer.
NPC: Vielen Dank, dass du dich darum gekümmert hast.
Spieler: Musste ich ja wohl…
```
> 1. `[QUEST ENDE]` [Skelette in der Höhle](#skelette-in-der-hoehle) und erhält [Belohnung](#Belohnung)

> Spieler kann zu [Sakros](../2-der-schmied) zurückkehren

#### Ausrüstung

#### Standort

```yml
x: 90
y: 83
z: -2
world: Ankanor
```

## Items

### Rostiges Schwert

Dropt von den Skeletten nach dem töten, ist nur für die Quest.

```yml
name: Rostiges Schwert
type: QUEST
quality: COMMON
item: IRON SWORD
lore: Ein vom Meersalz angerostetes Schwert.
max-stack-size: 1
```

### Eisenbarren

Dropt von den Verwitterten Skeletten nach dem töten, soll später möglich sein zu kochen.

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

## Belohnungen

[Skelette in der Höhle](#skelette-in-der-hoehle)
> 5 Heller
> 5 exp

## Referenzen

Verbunden mit [Sakros](../2-der-schmied/README.md)