# Hungriges Faultier <!-- omit in toc -->

Issue #69

## Übersicht <!-- omit in toc -->

##  Noch zu tun

##  Vorraussetzungen

keine   
vorteilhaft wären   

HQ [Jarmundshain wärmt auf](#jarmundshain-waermt-auf) abgeschlossen   
HQ [Vinnans helfende Hand](#vinnans-helfende-hand) angefangen.   


## Ablauf

## Questdialoge

### Dialog 1: Tjorben

**Tjorben** `Hey fremdes Gesischt, bringsche mir noch’n Bier?`

1. Dein Ernst? Nein! **`[Ende]`** weiter bei [Dialog 4](#dialog-4)   
2. Bekomme ich dann das Geld wieder?   
   **Tjorben** `Daran solls nisch ‘eitern.`   
   In Ordnung, ich frage mal den Wirt. `[Ende]`

### `[Quest Start]` [Hungriges Faultier]

**`Questlog:`**  *Besorge Tjorben ein Bier beim Wirt.*

**Der Spieler geht zum Wirt**

### Dialog 2: Stan

**Stan:**` Na Fremder, ne warme Suppe zum aufwärmen?`
1. Ja gerne! 
>> Spieler öffnet das Händlermenue 
2. Nein, ich möchte ein Bier.
   **Stan:** ` Ein Bier..  für Euch? *betrachtet Euch argwöhnisch* `     
   Nein, ich soll für den Herrn dort drüben ein Bier besorgen.   
   **Stan:** `Tjorben? Der bekommt nichts mehr bis er nicht endlich seine Schulden bezahlt.` **`[Ende]`**

`[Quest Ende]` [Hungriges Faultier](#hungriges-faultier)

### **`[Quest Start]`** [Kein Bier]

**`Questlog:`** *Erklärt Tjorben, dass er kein Bier mehr bekommt.*

### Dialog 3: Tjorben
**Tjorben** `Wo isht mein Bier?`  
Tut mir leid, der Wirt wollte mir kein Bier geben, weil du Schulden hast.
**Tjorben **`Ach was, so ein hartherschiger Kerl.`
So ist das Leben. 

`[Quest Ende]` [Kein Bier](#kein-bier)

### Dialog 4 

**Tjorben** `Hrmf..  die Fleischbrühe meiner Frau wär’ nu auch wash, könnt Ihr ein bischen Knochenmark besor’n und zu ihr bring’n?`  

1. Nein, werde erst mal wieder nüchtern. **`[Ende]`**    
**Spieler nimmt die Quest nicht an**

2. Ja, sowas kann ich.
   **Tjorben** `Gut, unser Haus ist hier raus..  danach rechts.. über die Brücke, da rechts den Weg weiter. Dann geht man gerade drauf zu, da findet Ihr meine Frau.`   
   Gut, da bring ich dann Knochenmark hin.



















   




#### Während der Quest 
> falls man den wirt Stan noch nicht angesprochen hat:

**Tjorben** `Wo isht mein Bier?`   
 Oh, achja richtig, ich frag gleich mal.`[Ende]`
   
















[Hungriges Faultier](#hungriges-faultier)






























### Rolfs Zettl

```yml
ID: 339
name: Rolfs Zettl
type: QUEST
quality: Common 
item: paper
lore: Eine Bestätigung von Rolf, dass ich den Wolf beseitigt habe.
max-stack-size: 1
```