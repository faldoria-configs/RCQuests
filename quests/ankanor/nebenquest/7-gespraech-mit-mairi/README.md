# Gespräch mit Mairi

[Mairi](#mairi) ist eine Kaishi von Ankanor, die ihr Haus hoch oben im Tianbaum hat. 


## Was noch fehlt:

Fast alles


## Übersicht 

- [Voraussetzungen](#voraussetzungen)
- [Ablauf](#ablauf)
- [Questdialoge](#questdialoge)
   - [Dialog 1](#dialog-1)
   - [Dialog 2](#dialog-2) 
   - [Dialog 3](#dialog-3)  - 
- [NPCs](#npcs)
     - [Name des NPCs](#name-des-npcs)
         - [Standartsätze](#standartsaetze)
            - [Vor der Quest](#vor-der-quest)
            - [Während der Quest](#waehrend-der-quest)
            - [Nach der Quest](#nach-der-quest)
         - [Ausrüstung](#ausruestung)
         - [Standort](#standort)
       
-  [Mobs](#mobs)
    - [Name des Mobs](#name-des-mobs)
    
-  [Items](#items)
    - [Name des Items](#name-des-items)
   
- [Belohnung](#belohnung)
         


## Voraussetzungen

Keine


## Ablauf

1. Mairi spricht den Spieler an (5 Blocks?), wenn er die Treppe zu den zwei oberen Häusern hochläuft. 
   Variationen im Gespräch, je nachdem ob er die Quest von Mimi weiter unten angenommen hat.
2. Der Spieler unterhält sich mit Mairi über Mimi.
3. Mairi gibt dem Spieler den auftrag, Mimi zu sagen, dass sie zum Schiff gehen soll.  
4. Mairi verabschiedet sich vom Spieler.



## Questdialoge

Spieler läuft die Treppe zu den oberen Häusern hoch. Mairi spricht Spieler an, wenn er 5 Blöcke weg ist



```yml
Mairi: Hey, <Name des Spielers>, wart mal einen Augenblick bitte.
```
Möglichkeit 1:  Geht er auf sie zu und klickt sie an, startet der Dialog
Möglichkeit 2: Geht er weiter, sagt Mairi:
```yml
Mairi: Na , dann eben nicht, dann muss ich selber suchen. 
```
### **Dialog 1**   nach Möglichkeit 1

```yml
Mairi: Hast du vielleicht Mimi gesehen?
```
1. Spieler: Ja, sie sitzt unten auf der Treppe. 
   Mairi: Gut, danke, ich sehe nach ihr.

2.  Spieler: Ja, sie sitzt da unten auf der Treppe und wollte, dass ich ihre Puppe hole.
Mairi: Und du hast dich breitschlagen lassen?

      2.1 der Spieler [NQ Mimi brauch dich](#6-mimi-braucht-dich) angenommen hat:

     > Spieler: Ja, natürlich, wer kann ihrem Charm widerstehen?

     2.2 Wenn der Spieler [NQ Mimi brauch dich](#6-mimi-braucht-dich) NICHT angenommen hat:

     > Spieler: Nein, ich lass mich doch von ihr nicht auf dem Arm nehmen. 

```yml
Mairi: Ja, die Puppe bedeutet ihr viel, sie sagt, dass ihre Mutter sie gemacht hat und dass sie das Einzige ist, das sie noch von ihr hat.
Spieler: Ja, ich erinnere mich, Mimi war eines Tages da, am Strand angespült, in einem kleinen Boot, das unmöglich die ganze Strecke über das Meer geschafft haben kann. Mit nichts dabei außer einigen Kiakeksen und einen großen, leeren  Schlauch Wasser. Und ihrer Puppe. 
Mairi: Genau, und das Kleid der Puppe war so ausgeblichen und zerrissen wie ihr eigenes. Es war nicht mehr möglich, daraus einige Rückschlüsse auf ihre Herkunft zu ziehen. Sie selbst konnte es uns auch nicht sagen, sie war ja noch klein, vielleicht drei Jahre alt. 
Spieler: Du hast sie dann bei dir aufgenommen, nicht wahr? Hast du das nicht schon bereut, so ein Frechdachs wie sie ist?
Mairi: Aber nein! Sie ist ein Lausemädchen, aber lieb! Ich wünschte, meine eigenen Kinder würden so folgen wie sie!
Mairi: Aber was reden wir hier, anstatt dass wir unsere Sachen packen, Agnatus Schergen sind auf dem Weg hierher und wir trödeln rum! Schnell, lass uns unsre letzten Sachen erledigen!
Aber warte - könntest du ihr bitte sagen, dass sie schnell zum Schiff laufen soll?
```
Spieler:

1. Nein, ich habe leider keine Zeit. `[Ende]`
2. Ja, ich hole nur schnell noch ihre Puppe {falls der Spieler die [NQ Mimi brauch dich](#6-mimi-braucht-dich) angenommen hat}.
3. Ja, ich sag es ihr.  {falls der Spieler die [NQ Mimi braucht dich](#6-mimi-braucht-dich) NICHT angenommen hat}.

`[QUESTSTART]`[Schicke Mimi zum Schiff](#schicke-mimi-zum-schiff)

> **QuestLog:** *Schicke Mimi zum Schiff, sobald du sie siehst*

*Der Spieler.. erfüllt seine Aufgabe* 

### **Dialog 2**  

Sobald der Spieler Mimi wieder trifft, spricht er sie erst darauf an. 
```Yml
Spieler: Mimi, ich habe Mairi getroffen und sie lässt dir ausrichten, du sollst sofort zum Schiff rennen. 
Mimi: Aber ich brauche doch meine Puppe!
```
1. Falls [NQ Mimi braucht dich](#6-mimi-braucht-dich) angenommen wurde und der Spieler sie schon hat:
   

    > Weiter mit Zeile 51 der [NQ Mimi braucht dich](#6-mimi-braucht-dich) 

2. Falls [NQ Mimi braucht dich](#6-mimi-braucht-dich) NICHT angenommen wurde und der Spieler die Puppe nicht hat.


## Belohnung : [XP](#xp)

Nur XP

`[Ende]` 


## NPCS

### Mimi

Beschreibung des NPCs, wenn möglich Verlinkung zum Wiki 

#### Standartsätze

    ##### Vor der Quest:

*Wenn z.B. die Vorraussetzungen noch nicht erfüllt sind*



    ##### Während der Quest:

Wenn die Quest noch nicht erfüllt ist und der Spieler trotzdem zurück kommt

    ##### Nach der Quest: 

Wenn der Spieler nach Abschluss der Quest den NPC anklickt



#### Ausrüstung

Welchen Skin hat der NPC? Was hält er in der Hand?

#### Standort   

```yml
x: 
y: 
z: 
world: faldoria.eisenküste
```


## Items

Item: engl. Bezeichnung hier: https://minecraft-ids.grahamedgecombe.com/


### Name des Items

```yml
ID: 
name: 
type: QUEST (z.B.)
quality: COMMON (z.B.)
item: (engl. Bezeichnung aus dem MC-Wiki)
lore: 
max-stack-size: 
```


## Mobs

### Name des Mobs

```yml
name: 
type: engl. Bezeichnung aus dem MC Wiki
min-level: 
max-level: 
min-health: 
max-health: 
min-damage: 
max-damage: 
spawn-chance: 
spawning-naturally: 
loot-table: was droppt es?
aggro: false/true
```


## Belohnung

[Name des Items](##name-des-items)



## Referenzen

Links!
-  zur Lore
- Zur Mobkarte
- Oder was auch immer nützlich erscheint 
























          




