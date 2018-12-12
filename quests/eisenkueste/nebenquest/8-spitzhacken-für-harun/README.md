# Spitzhacken für Harun

Issue 18

## Was noch fehlt:



 
## Veränderungen

Viele?

Aus dem google doc:
QuestName: Spitzhacken für Harun 
QuestNPCAuslöser: Harun (nähe des Steinbruchs)
Level: 2
Schwierigkeit/Aufwand: 2/2
Monster: Toter Steinmetz (Skelette mit Spitzhacken, Schwerter, Bögen)
Quest Items: Spitzhacken: Drop  10 % Skelette / Kisten zu 15 %
QuestBelohnung: 15 Kupfer

## Übersicht  



## Voraussetzungen

HQ [Was ist passiert](#was-ist-passiert)

HQ [Reparaturarbeiten](#reparaturarbeiten)

Vorraussetzung Banditenquest?  -> wäre logisch, hmm


## Ablauf

Grobe Beschreibung was in der Quest basiert.

1.
2.
3.
……

## Questdialoge

### Dialog 1

[Harun](#harun) spricht den Spieler an, sobald er 15 Blöcke entfernt ist

```yml
NPC: Heh Ihr, kommt mal her. 
```  
Wenn Spieler den NPC anspricht beginnt folgende Konversation

```yml
Harun: Ihr seht kräftig aus, wollt Ihr euch ein paar Münzen verdienen?
```
> 1. Spieler: Ich weiß nicht recht, Ihr seht mir nicht vertrauenswürdig aus. 

Harun: Was, wie kommst du denn darauf? Nur weil ich etwas älter bin und einen        Bart habe? Du wirst doch keine Vorurteile gegenüber Bartträgern haben?

Spieler: Nein das nicht, aber...

Harun: Papperlapap, willst du jetzt einen Heller haben oder nicht?

    1.1 Spieler: Nein, mein Bauchgefühl sagt mir, dass mich lieber fern halten sollte.
        Harun: Wie du meinst, du Hasenpfote.
 `[Ende]`

    1.2 Na gut, was soll ich tun?

> 2. Ein paar Münzen in der Geldkatze wären nicht schlecht, was soll ich denn für Euch tun?

Nach 1.2 und 2 weiter mit 


### Dialog 2
```yml
Harun: Die Aufgabe ist ganz einfach, seht Ihr da unten den Steinbruch? Ihr müsst dort nur 5 Spitzhacken aus den Kisten holen.
Spieler: Warum machst Ihr es nicht selbst, das klingt doch recht einfach.
Harun: Ach, Ihr seht doch, ich bin nicht mehr der Jüngste, mir tun die Gelenke weh und der Pfad da runter ist steil, aber für Euch ist das sicherlich ein Kinderspiel.
```

> 1.  *Du schaust den Mann kritisch an und glaubst ihm nicht, da ist etwas faul!*

Spieler: Tut mir leid, ich muss wieder zum Lager zurück, Ihr schafft das bestimmt alleine. 

Harun: Faulpelz! Die Kiesflöhe sollen dich in den Arsch beißen!

`[Ende]`

> 2. Spieler: Na gut, das leuchtet mir ein und klingt auch ganz einfach, ich mache es.

Harun: Gut dann macht euch auf den Weg ich werde euch dann entlohnen. 

`[Queststart]` [Spitzhacken für Harun](#spitzhacken-fuer-harun)

**QuestLog:** *Finde und sammle 5 Spitzhacken in den Ruinen des Steinbruchs*

>> **Spieler erledigt die Quest**

`[Ende]`

`[Queststart]` [Kehre mit den Spitzhacken zu Harun zurück](#kehre-mit-spitzhacken-zu-harun-zurueck)

>> **Der Spieler kehrt zu Harun zurück**

Harun spricht den Spiler an, wenn er 5 Blocks entfernt ist:

```yml
Harun: Da seid Ihr ja wieder, an einem Stück, wie erfreulich. Habt ihr die Spitzhacken?
```





Spieler: 
S1 - Nun verstehe ich warum ihr das nicht gemacht habt! Aber ja hier.
S2 -  War wirklich einfach, aber ihr seid ein Feigling. Hier sind die Spitzhacken
S3 -  Leider habe ich noch nicht genug finden können.
NPC:
S1 - So musste ich mir wenigstens nicht die Hände schmutzig machen, hier ist eure Belohnung. (Konversation beendet)
S2 - Ja, mein Boss, er… er hat verlangt das ich das mache, wir brauchen sie für die Mine.
S3 - Ich brauche sie dringend. (Konversation beendet)
Spieler:
S2 - Für die Mine, ihr seid also einer dieser fiesen Banditen. Gebt mir meine Belohnung aber sofort!
NPC: S2 - Sicher hier habt ihr sie!