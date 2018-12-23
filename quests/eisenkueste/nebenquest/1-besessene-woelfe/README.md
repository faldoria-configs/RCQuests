# Besessene Wölfe

Issue #21

## Noch zu tun

> Wölfe Werte geben
> Belohnung XP und Gold festsetzen

Im Camp steht [NPC Hauptmann Marduk](#hauptmann-marduk). Er möchte, dass der Spieler aggressive Wölfe für ihn tötet. 

## Übersicht

- [Besessene Wölfe](#besessene-w%C3%B6lfe)
  - [Noch zu tun](#noch-zu-tun)
  - [Übersicht](#%C3%BCbersicht)
  - [Vorraussetzungen](#vorraussetzungen)
  - [Ablauf](#ablauf)
  - [Dialoge](#dialoge)
  - [NPCs](#npcs)
    - [Hauptmann Marduk](#hauptmann-marduk)
      - [Standardsätze](#standards%C3%A4tze)
      - [Ausrüstung](#ausr%C3%BCstung)
      - [Standort](#standort)
  - [Items](#items)
    - [Hose aus Schimmerwolfspelz](#hose-aus-schimmerwolfspelz)
  - [Mobs](#mobs)
    - [Schimmerwolf](#schimmerwolf)
  - [Belohnung](#belohnung)
  - [Referenzen](#referenzen)
  - [Issues etc](#issues-etc)



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

> 1. Spieler: Ach nein, Schimmerwölfe jagen ist nicht so meins, die sind doch schön anzusehen.

```yml
Hauptmann Marduk: Wenn du nicht auch noch beinahe gefressen werden willst, hörst du mir besser zu.
```

> 2.1. Spieler: Worauf willst du hinaus?
 
> 2.2. Spieler: Na gut, was willst du?
 
> 2.3 Spieler: Ich komme schon klar, such dir wen anders. `[Ende]`

> 3. Spieler: Schimmerwölfe? Ich tu es für dich, aber warum, sie sind doch schön anzusehen. 




**Weiter nach 1., 2.1., 2.2. und 3.:**

```yml
Hauptmann Marduk: Hörzu: Ich habe kein Problem mit Tieren, aber wenn sie eins mit mir haben, ist das sehr wohl ein Problem! Normalerweise halten sich fast alle Viecher von uns fern. Aber hier gibt es Wölfe, die nicht zögern jeden anzugreifen, der ihnen zu nahe kommt. Wer weiß, ob da nicht Magie im Spiel ist.

Spieler: Und ich soll die Wölfe jetzt töten, natürlich. Wo finde ich sie?

Hauptmann Marduk: Ein Stück südwestlich von hier im Wald ist ein alter Schrein an einer eingestürzten Brücke. Dort in der Nähe haben sie mich schon einmal angegriffen. Schau am besten dort. 
```
> Na schön, ich werde mich um diese Biester kümmern.

```yml
Hauptmann Marduk: Du würdest dem Lager damit sehr helfen! Komm wieder zu mir, wenn du sie erledigt hast.
```

`[QUEST START]` [Besessenen Woelfe](#besessene-woelfe)

> **QuestLog:** Suche die Wölfe südwestlich des Lagers, die sich an der alten Brücke beim Schrein breitmachen und töte sie.
- Töte [20] Wölfe

Spieler tötet 20 Wölfe.

`[Ende]`

>> **Belohnung**   XP?

`[QUEST START]` [Kehre zu Marduk zurück](#kehre-zu-marduk-zurueck)


> **Questlog:** *Geh zurück zu Hauptmann Marduk und berichte ihm von deinem Erfolg.*


Spieler geht zurück zu Hauptmann Marduk.


```yml
Hauptmann Marduk: Sind die Biester tot?
Spieler: Ja, sie hatten keine Chance.
Hauptmann Marduk: Gut gemacht! Hoffen wir, dass das die einzigen waren.... Nimm dies als Dank. 

```

`[ENDE]`



## NPCs

### Hauptmann Marduk

Er nennt sich zwar Hauptmann, es gibt aber eigentlich keine richtigen Truppen bei den Kaishi. Marduk ist ein sehr entspannter Typ, er hat keine Kampferfahrungen, soll sich aber um die Verteidigung kümmern.

#### Standardsätze

**Vor der Quest**  
1.  Keine

**Während der Quest**  
1. Marduk: Nun, sind schon alle Wölfe tot?
 
   1.1 Spieler: Eh..., noch nicht

   1.2 Spieler: Nein, leider nicht, wo finde ich die Wölfe?
       Marduk: Ein Stück südwestlich von hier im Wald ist ein alter Schrein an einer eingestürzten Brücke. Dort in der Nähe. 
       
2. Marduk: Das ging aber schnell, gibt's heute Abend Wolfsbraten?
   
   2.1 Spieler: Eh..., noch nicht

   2.2 Spieler: Nein, leider nicht, wo finde ich die Wölfe?

> Marduk: Ein Stück südwestlich von hier im Wald ist ein alter Schrein an einer eingestürzten Brücke. Dort in der Nähe.

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


> 10 Heller
> 10 XP




## Referenzen

## Issues  etc







