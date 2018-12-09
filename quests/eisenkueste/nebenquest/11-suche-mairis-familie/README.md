# Suche Mairis Familie

Issue 59

[Mairi](#mairi) ist ein NPC, dem der spieler schon in einer Nebenquest auf Ankanor begenet ist. Sie ist Kräuterkundige und Heilerin und kann den Skill 'Bandagieren' lehren. 

## Was noch fehlt:

Ziemlich alles

 
## Veränderungen

Reines NPC Gespräch aus dem Doc fast völlig ignoriert... 

## Übersicht  

- [Voraussetzungen](#voraussetzungen)
- [Ablauf](#ablauf)
- [Questdialoge](#questdialoge)
   - [Dialog 1](#dialog-1)
   - [Dialog 2](#dialog-2) 
   - [Dialog 3](#dialog-3)  - 
[NPCs](#npcs)
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

[HQ Was ist passiert?](../1-was-ist-passiert/README.md) - Abgeschlossen
[HQ Reparaturarbeiten](../2-reparaturarbeiten/README.md) - Abgeschlossen


## Ablauf

1. Der Spieler trifft auf Mairi und fragt, wie es ihr geht.
2. Mairi erzählt von ihrer vermissten Familie.
3. Der Spieler verspricht, die Augen offen zu halten. 
   

## Questdialoge

Mairi steht am Strand und schaut auf das Meer hinaus, sobald der Spieler sie anspricht/anklickt, dreht sie sich zu ihm um. (Oder auch, wenn er nur nah genug kommt)

### **Dialog 1**

```yml
*Du siehst Mairi auf's Meer hinausblicken, ihre Haltung zeigt dir, dass sie Kummer hat*
Spieler: Mairi, wie geht es dir?
Mairi: *versucht ein Schluchzen zu unterdrücken*
Mairi: Meine Kinder, mein Mann, sie sind nicht hier… sie sind bestimmt tot. Wir waren alle auf dem Schiff, aber nun sind sie… nicht da. 
Spieler: Aber du hast sie nicht gefunden, ich meine, hast du ihre Leichen gesehen?
Mairi: Nein…
Spieler: Nun, siehst du, vielleicht sind sie woanders angespült worden, du darfst die Hoffnung nicht aufgeben. 
Mairi: Meinst du? Glaubst du das wirklich? Kannst du nach ihnen Ausschau halten? 
Spieler: Ja klar, ich komme ja etwas rum. Ich halte die Augen offen. Wenn ich sie hier nicht finde, dann vielleicht anderswo. 
Mairi: Du weiß noch, wie sie heißen? Antosh und Irgrid sind meine Kinder, Arim heißt mein Mann. Nur, wie und wo treffe ich dich wieder?
Spieler: Das weiß ich auch nicht, aber wenn ich sie sehe, dann kann ich ihnen sagen, dass du lebst. Irgendwann komme ich zurück - oder ihr fahrt alle mit dem Ballon ins Landesinnere wie ich. 
*Mairi  sieht jetzt etwas zuversichtlicher aus.*
Mairi: Ich bin so froh, dass du mir hilfst. Ich danke dir!
Spieler: Ist doch klar, warum sollte ich das nicht tun?
```

`[Queststart]` [Suche Mairis Familie](#suche-mairis-familie)

>>> Quest kann auf unbestimmte Zeit nicht abgeschlossen werden!


### Dialog 2




> 1. Spieler: Antwort 1, etc 
`[Ende]`


*****

> 2.1 Spieler: Antwort 2.1   …

**Alternativ wenn der Spieler ….:** 

> 2.2 Spieler: ……

`[QUESTSTART]`[Name der Quest](#name-der-quest)

> **QuestLog:** *Was soll der Spieler tun?*

*Der Spieler.. Erfüllt seine Aufgabe* 



### **Dialog 2**  

```Yml

```

Der Spieler kehrt zum Questgeber zurück(eventuell extra Quest für das Zurückgehen)

**Belohnung**: [Name der Belohnung](#name-der-belohnung)

`[Ende]` 


## NPCS

### Name des NPCs

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
























          





