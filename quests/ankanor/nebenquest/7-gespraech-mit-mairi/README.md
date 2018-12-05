# Gespräch mit Mairi

Issue 54

[Mairi](#mairi) ist eine Kaishi von Ankanor, die ihr Haus hoch oben im Tianbaum hat. 


## Was noch fehlt:

NPC Mairi muss noch plaziert werden


## Übersicht 

- [Voraussetzungen](#voraussetzungen)
- [Ablauf](#ablauf)
- [Questdialoge](#questdialoge)
   - [Dialog 1](#dialog-1)
   - [Dialog 2](#dialog-2) 
   - [NPCs](#npcs)
     - [Name des NPCs](#name-des-npcs)
         - [Standartsätze](#standartsaetze)
            - [Vor der Quest](#vor-der-quest)
            - [Während der Quest](#waehrend-der-quest)
            - [Nach der Quest](#nach-der-quest)
         - [Ausrüstung](#ausruestung)
         - [Standort](#standort)
       
   
- [Belohnung](#belohnung)
         


## Voraussetzungen

Keine


## Ablauf

1. Mairi spricht den Spieler an (5 Blocks?), wenn er die Treppe zu den zwei oberen Häusern hochläuft. 
   Variationen im Gespräch, je nachdem ob er die Quest von Mimi weiter unten an der Treppe angenommen hat.
2. Der Spieler unterhält sich mit Mairi über Mimi.
3. Mairi gibt dem Spieler den Auftrag, Mimi zu sagen, dass sie zum Schiff gehen soll.  
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

      2.1 wenn der Spieler [NQ Mimi brauch dich](#6-mimi-braucht-dich) angenommen hat:

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
```
`[Ende]`
```yml
Mimi: Aber ich brauche doch meine Puppe!
```
1. Falls [NQ Mimi braucht dich](#6-mimi-braucht-dich) angenommen wurde und der Spieler sie schon hat:
   

    > Weiter mit Zeile 51 der [NQ Mimi braucht dich](#6-mimi-braucht-dich) 

2. Falls [NQ Mimi braucht dich](#6-mimi-braucht-dich) NICHT angenommen wurde und der Spieler die Puppe nicht hat.

   2.1: Spieler: Hau ab, oder die bösen Männer holen dich!
        Mimi: *Mimi schaut dich böse an*

   2.2: Ich hole sie ja schon! Wo sagtest du ist sie? Im obersten Haus unter der Kiste in der Treppe?
        Mimi: *lacht* Ja genau!

**Nach Möglichkeit 2.2 :**
      
`[Quest START]` [Mimi braucht dich](#mimi-braucht-dich)

Issue 51



## Belohnung : [XP](#xp)

Nur XP

`[Ende]` 


## NPCS

### Mairi

#### Standartsätze

##### Während der Quest
```yml
Mairi: hast du Mimi schon Bescheid gesagt?
Spieler: Noch nicht, mache ich aber gleich!
Mairi: Beeil dich bitte!
```
##### Nach der Quest:

Mairi: Was, du bist immer noch hier? Hast du nichts Besseres zu tun?

#### Ausrüstung

  > normalen Skin

#### Standort

```yml
x: 44
y: 88116
z: -7
world: Ankanor
``` 


### Mimi

> siehe [Mimi braucht dich](#mimi-braucht dich)

#### Standartsätze

   > siehe [Mimi braucht dich](#mimi-braucht dich)


#### Ausrüstung

   siehe [Mimi braucht dich](#mimi-braucht dich)

#### Standort

```yml
x: 38
y: 88
z: -32
world: Ankanor
``` 


## Items

 - 


## Belohnung

[Name des Items](##name-des-items)

XP



## Referenzen

Hängt zusammen mit:  

[NQ Mimi braucht dich](#6-mimi-braucht-dich)
























          




