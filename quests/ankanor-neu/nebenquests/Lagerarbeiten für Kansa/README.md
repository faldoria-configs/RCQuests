# Lagerarbeiten für Kansa <!-- omit in toc -->

Issue #90

## Noch zu tun/Probleme

## Ablauf
1. Der Spieler kommt ins Lager, mit Quest [Segel für das Schiff](../segel-fuer-das-schiff.md) (Möglichkeit ohne Quest s.u.)
2. Kansa fragt, was er will.
3. Spieler erzählt ihm von seinem Auftrag, Kansa lässt ihn gewähren.
4. Danach fragt kansa ihn, ob der Spieler für ihn auch etwas erledigen könnte - Vorräte für das Schiff besorgen.
5. Der Spieler erfüllt die Aufgaben. 


## Übersicht

## Vorraussetzungen

keine

## Dialoge

### `Dialog 1`
**Spieler stürmt herein und will das Lager plündern.**

**Kansa:** `Halt, was willst du hier?`   
1. *Du kümmerst dich nicht um Kansa, den Lagerverwalter und suchst dir deine Sachen einfach zusammen.*    
   **Kansa:** `Das werde ich Roschik melden, der wird nicht erfreut sein!`   

> Nachdem der Spieler den Eimer Klebstoff und die Segelschnur eingesammelt hat: 
 
1. Ach Kansa, ich soll fragen, wie es mit den Essensvorräten steht. Du weißt doch, wir müssen weg, hast du genug?   
   **Kansa:** Nein, und ich könnte jemand gebrauchen, der mir das Nötigste besorgt. Willst du das machen?

**Weiter mit [Dialog 2](#dialog-2) 

2. Hey Kansa, ich soll Materialien für Kapitän Mafei holen, Segelschnur und einen Eimer Kleber, zur Reparatur des Schiffes, wir brauchen es ja jetzt bald, wegen dem Amamus, weißt du, wo die sind?   
   **Kansa:** `Klar, da oben in der Kiste links oben. Wegen wem? `   
   Oh, danke, und nochwas, ich soll auch fragen, wie es mit den Lebensmittel und anderen Vorräten steht, die wir für unsere Flucht benötigen.   
   **Kansa:** `Da könnte ich durchaus noch etwas brauchen! Hast du nicht Lust, die mir zu besorgen, ich habe eine Menge anderer Dinge zu tun.`    

   2.1. Oh, jetzt grade nicht, ich möchte erst die Aufgaben für Mafei erledigen. `[Ende]`      
   **Kansa:** `Schade, na dann nicht.*schaut frustirert*`   
   2.2. Klar, die erledige ich gleich mit, soweit es geht.

   ### `[Quest Ende]` [Segel für das Schiff](../segel-fuer-das-schiff.md)    falls der Segelstoffballen auch schon im Inventar ist.   
   ### `[Quest Start]` [Zurück zu Mafei]   
   **Questlog:** *Kehre zu Mafei zurück*   

   ### [Dialog 2]

   **Kansa:** `Prima, du bist doch ein netter Zeitgenosse! Ich denke, es wäre gut, wenn wir einige geräucherte Fische mitnehmen könnten. Fang einige schwarze Barsche. Dann könnte ich noch einen Käse machen, dazu brauche ich einen Eimer Milch, Äpfel sind immer gut, da bringst du auch einige mit und dann scherst du bitte noch 5 Schafe, daraus können wir Decken machen. Hast du dir alles gemerkt?`   
   Eh, nein....   
   **Kansa:** Nun gut, hier hast du eine Liste.
   Oh, sehr gut, wer lesen kann ist klar im Vorteil!   

   > Spieler erhält Liste, Eimer, Angel und Schere


###  `[Quest Start]` [Lagerarbeiten für Kansa]
**Questlog** *Angle 3 Schwarze Barsche, schere 5 Schafe, melke eine Kuh und sammle 10 Äpfel. Bringe alles dann zu Kansa zurück.*



   

## NPCs

## `Name des NPCs`
## Standartsätze  
#### Vor der Quest
#### Während der Quest  
#### Nach der Quest
### Ausrüstung
### Standort



```yml
x: 
y: 
z: 
world: faldoria.eisenküste
```

## Items

### Itemname

```yml
ID: ?
name: 
type: QUEST
quality: RARE /COMMON
item: 
lore: max-stack-size: 1
```


## Mobs
### Mobname

```yml
name: 
type: wolf
aggro: true
passive: false
elite: true
min-level: 8
max-level: 8
```
```yml
x: 535
y: 101
z: -2121
world: faldoria.jarmundshain
radius: 5
```


#### Ausrüstung
## Belohnung
## Referenzen
## Issues


