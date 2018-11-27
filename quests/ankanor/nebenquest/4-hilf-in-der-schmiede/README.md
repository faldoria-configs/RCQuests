# Hilf in der Schmiede

Am südöstlichen Rand des Dorfes steht [NPC Sakros](#Sakros) der Schmied. Der Spieler hat schon für den Schmied Materialien in der [Quest Material für die Schmiede](../2-der-schmied/README.md) besorgt. Nun soll er noch in der Schmiede helfen die Schwerter herzustellen indem er einige Hebel bedient.

## Ablauf

1. Start: Spieler nähert sich Sakros
2. Spieler spricht [NPC Sakros](#Sakros) an und fordert den Spieler auf die Schwerter herzustellen `Questbeginn` [Hilf in der Schmiede](#Hilf-in-der-Schmiede)
3. Spieler muss eine gewisse Reihenfolge einhalten. Hebel ziehen, Knopf drücken, Hebel ziehen.
4. Ende: Nach erfolgreichen betätigen schließt der Spieler die Quest ab und erhält eine [Belohnung](#Belohnung) `Questende` [Hilf in der Schmiede](#Hilf-in-der-Schmiede)

## Vorrausetzungen

> 1. Erledigen der [Quest Material für die Schmiede](../2-der-schmied/REAMDE.md) 

## NPCs

### Sakros

Ist der Schmied von Ankanor. Ein sehr rauer und ungeduldiger Geselle.

##### Standartsätze  

**Vor der Quest**  
1. Nicht vorhanden bzw. Questdialog [Quest Material für die Schmiede](../2-der-schmied/REAMDE.md) 

**Während der Quest**  
1. Hebel ziehen, Knopf drücken und wieder den Hebel ziehen, so schwer kann das doch nicht sein!

**Nacht der Quest**  
1. Deine Faust muss stark sein, selbst Genam konnte es nicht so einfach mit den Skeletten in der Höhle aufnehmen.  
2. Wenn ich nicht wüsste das es Jahrelange Erfrahrung bräuchte um Schmied zu sein, müsste ich Angst haben das du mir meinen Job nimmst. Deine Arbeit mit den Schwertern war klasse.
    
#### Dialoge

##### Quest Dialoge

##### Hilf in der Schmiede

> 2. `[Quest START]` [Hilf in der Schmiede](#Hilf-in-der-Schmiede)  
**QuestLog:** *Stelle 3 Schwerter her, indem du den Hebel ziehst, den Knopf drückst und nochmal den Hebel betätigst.*

> Spieler macht die gegebene Aufgabe, bis Sakros nach dem dritten Schwert sagt:

```yml
NPC: Gut, das soll reichen.
Spieler: Und? Bist du zufrieden mit der Arbeit?
NPC: Hab schon besseres gesehen, aber für den ersten Versuch ist das schon recht gut.
Spieler: Und warum konntest du das selbst nicht machen?
NPC: Hab mir 'nen Nagel eingerissen. Und jetzt hau ab!
```

> 1. `[QUEST ENDE]` [Hilf in der Schmiede](#Hilf-in-der-Schmiede) und erhält [Belohnung](#Belohnung)


#### Ausrüstung

#### Standort

```yml
x: 90
y: 83
z: -2
world: Ankanor
```

## Items

### Verbrannte Steaks

Ist ein Nahrungsmittel was auch von Händlern verkauft wird.

```yml
name: Verbranntes Steak
type: FOOD
quality: COMMON
item: STEAK
lore: Dieses Steak war wohl zu lange auf der Feuerstelle.
max-stack-size: 64
```

## Mobs

> Nicht vorhanden

## Belohnung

[Hilf in der Schmiede](#Hilf-in-der-Schmiede)
> 5 Heller  
> 10 [verbrannte Steaks](#Verbrannte-Steaks)  
> 5 exp

## Referenzen

> Verbunden mit [Quest Material für die Schmiede](../2-der-schmied/README.md) und [Genam](../3-skelette-in-der-hoehle/README.md)