# Spitzhacken für Harun

Issue 18

## Was noch fehlt:

Nachschaun, wie die Zombies heißen
Koords nachsehen
Loot etc

 
## Veränderungen

Google Doc:
https://docs.google.com/document/d/1M2QfHDNB8vB3BLgaS0qX0tLFawQeyMduP8s1IUYLwTc/edit

Schlußpart gefällt mir nicht, ist unlogisch, 

`Aus dem google doc:`
QuestName: Spitzhacken für Harun 
QuestNPCAuslöser: Harun (nähe des Steinbruchs)
Level: 2
Schwierigkeit/Aufwand: 2/2
Monster: Toter Steinmetz (Skelette mit Spitzhacken, Schwerter, Bögen)
Quest Items: Spitzhacken: Drop  10 % Skelette / Kisten zu 15 %
QuestBelohnung: 15 Kupfer  <-- weniger! fast nichts!

## Übersicht  

- [Spitzhacken für Harun](#spitzhacken-f%C3%BCr-harun)
  - [Was noch fehlt:](#was-noch-fehlt)
  - [Veränderungen](#ver%C3%A4nderungen)
  - [Übersicht](#%C3%BCbersicht)
  - [Voraussetzungen](#voraussetzungen)
  - [Ablauf](#ablauf)
  - [Questdialoge](#questdialoge)
    - [Dialog 1](#dialog-1)
    - [Dialog 2](#dialog-2)
    - [Dialog 3](#dialog-3)
    - [NPC](#npc)
      - [Harun](#harun)
        - [Standartsätze](#standarts%C3%A4tze)
          - [Vor der Quest](#vor-der-quest)
          - [Während der Quest](#w%C3%A4hrend-der-quest)
          - [Nach der Quest:](#nach-der-quest)
      - [Ausrüstung](#ausr%C3%BCstung)
      - [Standort](#standort)
    - [Items:](#items)
    - [Drops](#drops)
      - [Spitzhacken](#spitzhacken)
      - [Standort ??](#standort)
    - [Mobs](#mobs)
      - [Toter Steinmetz](#toter-steinmetz)
  - [Belohnung](#belohnung)



## Voraussetzungen

HQ [Was ist passiert](#was-ist-passiert)

HQ [Reparaturarbeiten](#reparaturarbeiten)

NQ [Angriff ist die beste Verteidigung](#angriff-ist-die-beste-verteidigung)


## Ablauf


1. Harun ruft den spieler, sobald er in seine nähe kommt.
2. Er biete ihm an. etwas Geld zu verdienen
3. Der Spieler soll für ihn Spitzhacken aus dem Steinbruhc holen, weil es zu alt ist.
4. 

……

## Questdialoge

### Dialog 1

[Harun](#harun) spricht den Spieler an, sobald er 15 Blöcke entfernt ist

```yml
Harun: Heh Ihr, kommt mal her. 
```  
Wenn Spieler den NPC anspricht beginnt folgende Konversation:

```yml
Harun: Ihr seht kräftig aus, wollt Ihr euch ein paar Münzen verdienen?
```
> 1. Spieler: Ich weiß nicht recht, Ihr seht mir nicht vertrauenswürdig aus. 
> 

```yml
Harun: Was, wie kommst du denn darauf? Nur weil ich etwas älter bin und einen        Bart habe? Du wirst doch keine Vorurteile gegenüber Bartträgern haben?
Spieler: Nein das nicht, aber...
Harun: Papperlapap, willst du jetzt einen Heller haben oder nicht?
```

> 1.1  Spieler: Nein, mein Bauchgefühl sagt mir, dass mich lieber fern halten sollte.

```Harun: Wie du meinst, du Hasenpfote.```

`[Ende]`

> 1.2 Na gut, was soll ich tun?


>> 2. Ein paar Münzen in der Geldkatze wären nicht schlecht, was soll ich denn für Euch tun?


Nach 1.2 und 2 weiter mit 


### Dialog 2
```yml
Harun: Die Aufgabe ist ganz einfach, seht Ihr da unten den Steinbruch? Ihr müsst dort nur 5 Spitzhacken aus den Kisten holen.
Spieler: Warum machst Ihr es nicht selbst, das klingt doch recht einfach.
Harun: Ach, Ihr seht doch, ich bin nicht mehr der Jüngste, mir tun die Gelenke weh und der Pfad da runter ist steil, aber für Euch ist das sicherlich ein Kinderspiel.
```
> 1

`Spieler: *Du schaust den Mann kritisch an und glaubst ihm nicht, da ist etwas faul!*`

```yml
Spieler: Tut mir leid, ich muss wieder zum Lager zurück, Ihr schafft das bestimmt alleine. 

Harun: Faulpelz! Die Kiesflöhe sollen dich in den Arsch beißen!
```
`[Ende]`

> 2. 
```yml
Spieler: Na gut, das leuchtet mir ein und klingt auch ganz einfach, ich mache es.

Harun: Gut dann macht euch auf den Weg, ich werde euch dann entlohnen. 
```

`[Queststart]` [Spitzhacken für Harun](#spitzhacken-fuer-harun)

**QuestLog:** *Finde und sammle 5 Spitzhacken in den Ruinen des Steinbruchs*

>> **Spieler erledigt die Quest, trifft auf Mobs**

`[Ende]`

`[Queststart]` [Kehre mit den Spitzhacken zu Harun zurück](#kehre-mit-spitzhacken-zu-harun-zurueck)

>> **Der Spieler kehrt zu Harun zurück**

### Dialog 3

Harun spricht den Spieler an, sobald er 5 Blocks entfernt ist:

```yml
Harun: Da seid Ihr ja wieder, an einem Stück, wie erfreulich. Habt ihr die Spitzhacken?
Spieler: Ja, aber ich hoffe, Eure Belohnung fällt hoch genug aus - Ihr habt mich reingelegt. 
Harun: Ach was, ich habe dir nur nicht alle Gründe gesagt, warum ich da nicht runter will. 
Spieler: Und wozu braucht Ihr die Spitzhacken?
Harun: Na, für die Mine
Spieler: Für die Mine? Seid Ihr am Ende....  kann ich jetzt meine Belohnung haben?
Harun: Belohnung? Ach ja!  *lacht laut und reicht dir einige Münzen* Hier, dein Lohn.
Spieler: *du schaust die wenigen Münzen in deiner Hand an* Was, soll das alles sein?
Harun: Haben wir ausgemacht, wieviel es sein sollen?
Spieler: Nein, aber
Harun: Nun verzieh dich, Grünschnabel *nimmt seine große Axt drohend in die Hand*

```
`[Ende]`
### NPC

#### Harun

Harun ist einer der Banditen, die der Spieler vorher bekämpft hat in der HQ [Reparaturarbeiten](#reparaturarbeiten) und eventuell in der NQ [Angriff ist die beste Verteidigung](#angriff-ist-die-beste-verteidigung)

##### Standartsätze

###### Vor der Quest

Harun: Verpiß dich, Grünschnabel

###### Während der Quest

Harun: Na, hast du schaon alle Spitzhacken?

> 1. Spieler: Nein, aber ich weiß jetzt, warum du da nicht runter wolltest, aber ich hole sie schon noch.


> 2. Spieler: Nein, und den Rest kannst du selber holen, du Lügner.

Abbruch der Quest, keine Belohnung: 

`[Ende]`

###### Nach der Quest:

Harun: Was willst du hier noch, nochmals runter? Verschwinde oder.... *hebt seine Axt*


#### Ausrüstung 

Skin soll bedrohlihc aussehen - Bandit!


#### Standort

```yml
x: 
y:
z: 
world: Faldoria, Eisenküste

``` 

### Items:



### Drops

#### Spitzhacken

```yml
name: Alte Spitzhacke
type: QUEST
quality: COMMON
item: iron_pickaxe
lore: Liegt gut in der Hand, ist aber nicht mehr die neuste 
max-stack-size: 1
```
>> Spitzhacken: Drop  10 % Skelette / Kisten zu 15 %


#### Standort ??

```yml
x: 
y:
z: 
world: Faldoria, Eisenküste

``` 

### Mobs

#### Toter Steinmetz

```yml
name: Toter Steinmetz
type: sceleton
min-level: 
max-level: 
min-health: 
max-health: 
min-damage: 
max-damage: 
spawn-chance: 
spawning-naturally: 
loot-table: iron_pickaxe, wooden_sword, bow
aggro: true
```
>>  Das laufen auch noch Zombies rum!

## Belohnung

sehr wenig Geld und XP











