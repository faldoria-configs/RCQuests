# Der Schmied

Am südöstlichen Rand des Dorfes steht [NPC Sakros](#Sakros) der Schmied. Er benötigt Materialien für Schwerter, er erklärt dem Spieler das er Eisen und rostige Schwerter aus einer Höhle auf der anderen Seite holen soll.

## Ablauf

1. Start: Spieler nähert sich Sakros
2. Spieler spricht [NPC Sakros](#Sakros) an welcher ihm die Aufgabe gibt 1 Eisen und 10 rostige Schwerter zu holen. `Questbeginn:`[Material für die Schmiede](#Material-für-die-Schmiede)
3. Auf der anderen Seite der Insel in der Höhle findet der Spieler einen Genam vor der ihn nur hineinlässt wenn der Spieler die Quest hat.
4. In der Höhle selbst findet der Spieler Skelette welche die geforderten Items droppen, diese sind aber auch in den Kisten dort zu finden.
5. Spieler kehrt zurück und erhält eine [Belohnung](#Belohnung) `Questende:`[Material für die Schmiede](#Material-für-die-Schmiede)

## Vorrausetzungen

> 1. Erledigen der [HQ Klassenwahl](../../hauptquest/4-klassenwahl/README.md) bzw. es ist das Kämpfen / eine Klasse nötig.

> Folgequest siehe
> Spieler trifft [Genam](../3-skelette-in-der-hoehle/README.md) und
> [Hilf in der Schmiede](../4-hilf-in-der-schmiede/README.md)
> Spieler erledigt die Aufgabe und kehrt zum Questgeben zurück

## NPCs

### Sakros

Ist der Schmied von Ankanor. Ein sehr rauer und ungeduldiger Geselle.

Standartsätze:
    1. Nur mit einer starken Faust kann man etwas in seinem Leben erreichen.
    2. Puh, ich hasse diese Hitze am Schmelzofen.
    
#### Dialoge

##### Quest Dialoge

##### Material für die Schmiede

```yml
Sakros: Guten Tag, [Name des Spielers]. Könntest du vielleicht etwas für mich erledigen?
Spieler: Ja, was denn?
Sakros: : Ich würde gerne neue Schwerter machen. Könntest du mir die Materialien bringen?
Spieler: Warum das denn?
Sakros: Weil ich keine Lust habe. Außerdem habe ich ein gutes Argument: Eine Faust. 
Spieler: Na gut, Was brauchst du?
Sakros: Eisen und Rostige Schwerter aus der Höhle auf der anderen Seite des Dorfes.
Spieler: Was? Ich muss so weit laufen??
Sakros: Ja, und jetzt los, sonst setzt´s was!
```
> 1. Ok, ich habe ja sonst nichts zu tun. 
`[QUEST START]` [Material für die Schmiede](#Material-für-die-Schmiede)
**QuestLog:** *Besorge für den Schmied Eisen und 10 rostige Schwerter*

> 2. Nein vergiss es!`[Ende]`


> Spieler trifft [Genam](../3-skelette-in-der-hoehle/README.md)
> Spieler erledigt die Aufgabe und kehrt zum Questgeben zurück


```yml
Sakros: Wieso hat das so lange gedauert??
Spieler: Ich musste einmal um die ganze Insel rum, also beschwer dich nicht!
Sakros: Dann los, mach mir die Schwerter!
Spieler: Äh, Was?!?
Sakros: Irgendwann musst du es schließlich lernen. Also los, es ist einfach. Zieh den Hebel, drück den Knopf und betätige den Hebel erneut.
Spieler: Na gut.
```
> 1. `[QUEST ENDE]` [Material für die Schmiede](#Material-für-die-Schmiede) und erhält [Belohnung](#Belohnung)

> Folgequest [Hilf in der Schmiede](../4-hilf-in-der-schmiede/README.md)

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

## Belohnung

[Material für die Schmiede](#Material-für-die-Schmiede)
> 8 Heller  
> 5 exp



## Referenzen

> Verbunden mit [Genam](../3-skelette-in-der-hoehle/README.md) und [Hilf in der Schmiede](../4-hilf-in-der-schmiede/README.md)