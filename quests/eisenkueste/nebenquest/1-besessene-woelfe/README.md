# Besessene Wölfe

Issue #21

Im Camp steht [NPC Hauptmann Marduk](#hauptmann-marduk). Er möchte, dass der Spieler aggressive Wölfe für ihn tötet. 

## Übersicht

- [Voraussetzungen](#voraussetzungen)
- [Ablauf](#ablauf)
- [Questdialoge](#questdialoge)
   
- [NPCs](#npcs)
     - [Marduk](#marduk)
         - [Standartsätze](#standartsaetze)
            - [Vor der Quest](#vor-der-quest)
            - [Während der Quest](#waehrend-der-quest)
            - [Nach der Quest](#nach-der-quest)
         - [Ausrüstung](#ausruestung)
         - [Standort](#standort)
-  [Mobs](#mobs)
    - [Schimmerwolf](#schimmerwolf)
  
-  [Items](#items)
    - [Hose aus Schimmerwolfspelz](#hose-aus-schimmerwolfspelz)
    
- [Belohnung](#belohnung)


## Vorraussetzungen

[HQ Was ist passiert?](../1-was-ist-passiert/README.md) - Abgeschlossen

[HQ Reparaturarbeiten](../2-reparaturarbeiten/README.md) - Abgeschlossen


## Ablauf

1. Start: Spieler steht schon bei Hauptmann Marduk nach der [HQ Reparaturarbeiten](../2-reparaturarbeiten/README.md)
2. Der Spieler ist hilfsbereit/unwillig.
3. Hauptmann Marduk versucht, den Spieler zu gewinnen, ihm zu helfen.
4. Der Spieler stimmt zu/lehnt ab. 
5. Hauptmann Marduk schickt den Spieler in den Wald, um die Wölfe zu töten. 


## Dialoge


Der Spieler hat soeben mit Marduk geredet, die [HQ Reparaturarbeiten](../2-reparaturarbeiten/README.md) abgeschlossen und muss noch darauf warten, dass Elius den Ballon fertig repariert. 

```yml
Hauptmann Marduk: Was meinst du? 
```

> 1. Ach nein, Schimmerwölfe jagen ist nicht so meins, die sind doch schön anzusehen.

```yml
Hauptmann Marduk: Wenn du nicht auch noch beinahe gefressen werden willst, hörst du mir besser zu.
```

> 2.1. Worauf willst du hinaus?
 
> 2.2. Na gut, was willst du?
 
> 2.3 Ich komme schon klar, such dir wen anders. `[Ende]`

> 3. Schimmerwölfe? Ich tu es für dich, aber warum, sie sind doch schön anzusehen. 




**Weiter nach 1., 2.1., 2.2. und 3.:**

```yml
Hauptmann Marduk: Hörzu:Ich habe kein Problem mit Tieren, aber wenn sie eins mit mir haben, ist das sehr wohl ein Problem! Normalerweise halten sich fast alle Viecher von uns fern. Aber hier gibt es Wölfe, die nicht zögern jeden anzugreifen, der ihnen zu nahe kommt. Wer weiß ob da nicht Magie im Spiel ist.

Spieler: Und ich soll die Wölfe jetzt töten, natürlich. Wo finde ich sie?

Hauptmann Marduk: Ein Stück südwestlich von hier im Wald ist ein alter Schrein an einer eingestürzten Brücke. Dort in der Nähe haben sie mich schon einmal angegriffen. Schau am besten dort. 
```
> Na schön, ich werde mich um diese Biester kümmern.

```yml
Hauptmann Marduk: Du würdest dem Lager damit sehr helfen! Komm wieder zu mir, wenn du sie erledigt hast.
```

`[QUEST START]` [Besessenen Woelfe](#besessene-woelfe)

> **QuestLog:** Suche die Wölfe südwestlich des Lagers, die sich an der alten Brücke beim Schrein breitmachen, und töte sie.
- Töte [20] Wölfe

*Spieler hat 20 Wölfe getötet und muss dann zum Questgeber zurück kehren.*

> **Questlog:** *Geh zurück zu Hauptmann Marduk und berichte ihm von deinem Erfolg.*


Spieler geht zurück zu Hauptmann Marduk.


```yml
Hauptmann Marduk: Sind die Biester tot?
Spieler: Ja, sie hatten keine Chance.
Hauptmann Marduk: Gut gemacht! Hoffen wir, dass das die einzigen waren.... Nimm dies als Dank. [ENDE]
```



## NPCs

### Hauptmann Marduk

Er nennt sich zwar Hauptmann, es gibt aber eigentlich keine richtigen Truppen bei den Kaishi. Marduk ist ein sehr entspannter Typ, er hat keine Kampferfahrungen, soll sich aber um die Verteidigung kümmern.

#### Standardsätze

**Vor der Quest**  
1.  Keine

**Während der Quest**  
1. Marduk: Nun, sind schon alle Wölfe tot?
 
   1.1 Spieler: Eh..., noch nicht

   1.2 Nein, leider nicht, wo finde ich die Wölfe?
       Marduk: Ein Stück südwestlich von hier im Wald ist ein alter Schrein an einer eingestürzten Brücke. Dort in der Nähe. 
       
2. Marduk: Das ging aber schnell, gibt's heute Abend Wolfsbraten?
   
   2.1 Spieler: Eh..., noch nicht

   2.2 Nein, leider nicht, wo finde ich die Wölfe?
   
   Marduk: Ein Stück südwestlich von hier im Wald ist ein alter Schrein an einer eingestürzten Brücke. Dort in der Nähe.

**Nach der Quest**  
1. Noch nicht genug vom Wölfe jagen? *lacht laut*
2. Ah, sieh da, unser Wolfsjäger! 

#### Ausrüstung

Lederrüstung ohne Helm
Steinaxt in der Hand

#### Standort

```yml
x: 3645
y: 63
z: -2829
world: faldoria
```

## Items
### Hose aus Schimmerwolfspelz

```yml
ID: 
name: Hose aus Schimmerwolfspelz
type: QUEST
quality: COMMON
item: light-grey leather_leggings
lore: Diese Hose ist warm und wasserdicht
max-stack-size: 1
```

## Mobs

### Schimmerwolf

```yml
name: Schimmerwolf
type: wolf
min-level: 
max-level: 
min-health: 
max-health: 
min-damage: 
max-damage: 
spawn-chance: 
spawning-naturally: 
loot-table: light_grey_wool
aggro: true
```


## Belohnung

[Hose aus Schimmerwolfspelz](#hose-aus-schimmerwolfspelz)

[Besessene Wölfe](#besessene-woelfe)

> 10 Heller
> 10 XP




## Referenzen

## Issues  etc







