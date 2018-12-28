# Abenteurer Renlik

Issue 14

## Noch zu tun

Lagerfeuer bauen (Rüstungsständer, noch keine Rechte)
Belohnung ändern, falls Klassen vorerst abgeschafft werden
Vorraussetzung Waffe festlegen
Renlik versetzen
Werte Monster festlegen

## Überblick

- [Voraussetzungen](#voraussetzungen)
- [Ablauf](#ablauf)
- [Questdialoge](#questdialoge)
   
- [NPCs](#npcs)
     - [Renlik](#renlik)
         - [Standartsätze](#standartsaetze)
            - [Vor der Quest](#vor-der-quest)
            - [Während der Quest](#waehrend-der-quest)
            - [Nach der Quest](#nach-der-quest)
         - [Ausrüstung](#ausruestung)
         - [Standort](#standort)
-  [Mobs](#mobs)
    - [Die Quelle allen Übels](#die-quelle-allen-uebels)
  
-  [Items](#items)

     [Magische Asche](#magische-asche)

-  > mehrere Belohnungen für verschiedene Klassen? Gegebenenfalls abändern
    
- [Belohnung](#belohnung)


## Ablauf


1. Der Spieler findet beim Erkunden der Gegend den Abenteurer Renlik und spricht ihn an.
2. Dieser redet wirres Zeug, von einer Expedition zur Quelle des Flusses und dem Tod der Gruppe. 
3. Der Spieler geht zur Quelle und sucht nach der Ursache.
4. Er findet ein Ungeheur, welches er tötet.
5. Er kehrt dann zu Renlik zurück. 


## Vorraussetzungen

 - lvl 5
 - Waffe???  Ausrüstung?

## Aufgaben/Quests

1. Die Quelle allen Übels
2. Kehre zu Renlik zurück



## Questdialoge

### 1. Die Quelle allen Übels

Der Spieler findet Renlik und spricht ihn an. 

```yml
Spieler: Was suchst du denn hier draußen in der Wildnis? 
Renlik: Was ich hier suche? Das habe ich längst gefunden! Aber keine Lösung… keine Lösung… 
Spieler: Wovon redest du? 
Renlik: Siehst du die hölzerne Ruine oben auf dem Berg Richtung Westen? Von dort aus ging es los, dort fing es an. Nicht, dass es einfach gewesen wäre überhaupt bis dorthin zu kommen, nein! Doch von da an fing es an wirklich schlimm zu werden! 
```

> 1. Ich hab genug von deinem wirren Geschwätz. Adieu. `[Ende]`

> 2. Ganz von vorn bitte, ich verstehe kein Wort. 

```yml
Renlik: Als eine einfache Erkundungstour, eine gemütliche Expedition hatten sie es angepriesen! Nur bis zur Quelle und zurück. Nur die Götter wissen, was sie dort wollten, aber jedem wurde eine großzügige Belohnung versprochen… 
Spieler: Eine Expedition zur Quelle des Flusses? Wer hat das denn veranlasst? 
Renlik: Unwichtig, vollkommen unwichtig! Viel wichtiger ist, was jetzt dort ist, und dass alle außer mir das Zeitliche gesegnet haben! 
Spieler: Was?? Was ist denn an dieser Quelle? 
NPC: Wenn ich das wüsste… sicher ist nur, dass meine langen Beine mich davor gerettet haben. Im Gegensatz zu all den anderen. 
```

> 1. Das klingt ja sehr gefährlich, ich denke ich halte mich da lieber raus.`[Ende]`

> 2. Na gut. Was immer an der Quelle haust, ich werde es unschädlich machen. 

`[Quest START]` [Die Quelle allen Übels](#die-quelle-allen-uebels)

`**QuestLog:**` *Finde die Quelle des Flusses und gehe dem Tod der Expeditionsmitglieder auf den Grund.*


Der Spieler folgt dem Flusslauf bis zur Quelle und tötet das dortige Monster (blaze). Sobald dies erledigt ist, kehrt er zum Abenteurer Renlik zurück. 

`[Ende]`

> > **Belohnung**  Drop?


### 1. Kehre zu Renlik zurück

`[Quest START]` [Kehre zu Renlik zurück](#kehre-zu-renlik-zurueck)

`**QuestLog:**` *Kehre zu Renlik zurück und erzähle ihm, was du gefunden hast.*


```yml
Renlik: Was hast du gefunden? Den Tod nicht, aber was war es dann?
Spieler: Ich denke ich möchte nicht wissen, was die Leiter dieser seltsamen Expedition dort getrieben haben, aber ich glaube, sie führten nichts Gutes im Schilde. Dort war ein Wesen, das ich noch nie zuvor gesehen habe. Es bestand aus Feuer und schien von einer magischen Aura umgeben zu sein. Ich konnte es aber trotzdem mit meinen Waffen besiegen.
Renlik: Ha! Gedacht hab ich’s mir! Dunkle Magie, Beschwörungen… Renlik hat’s gewusst, da ist was faul. 
Spieler: Wer waren denn nun deine Auftraggeber? 
Renlik: Auch wenn die jetzt tot sind, denke ich nicht, dass ich dir das sagen werde… manchmal ist Wissen eben nicht nur Macht. Naja, du sollst jedenfalls nicht leer ausgehen. Etwas mehr als einen Gefallen, das wär schon was. Hmmm… Hier, das hab ich mir von einem der Expeditionsleiter.. ähm … ausgeliehen. Brauchen tut er’s jetzt wohl nicht mehr, hihihi...
```

`[Ende]`

## NPC 

### Renlik 

Renlik ist ein seltsamer Vogel, einziger Überlebender einer Expedition, die nach etwas suchte, das dem Spieler nicht verraten wird. Er redet wohl oft mit sich selbst, so der Eindruck, als er dem Spieler Auskunft gibt. Renlik erscheint gewitzt, etwas zweideutig in seiner Ausdrucksweise und voller Wissen, doch auch etwas wirr im Kopf. 


#### Standartsätze

##### Vor der Quest:

> 1. Haha, hahaha, was willst du hier?
> 2. Geh weg, du schaust noch so grün aus, dir kann ich nichts erzählen.
> 3. Weg mit dir, stör mich nicht. 

##### Während der Quest/Aufgabe #1

> 1. Du lebst noch? War wohl der Weg zu steil oder der Schnee zu tief?
> 2. Sag bloß, da oben ist gar nichts mehr los?
> 3. Ist nicht so einfach mit der Orientierung, was?

##### Nach der Questabgabe/Aufgabe #2

> 1. Ist die Gegend so schön, dass du wiederkommst, oder hast du mich vermisst?
> 2. Ah, der Monsterkiller! Auf der Sche nach neuen Opfern?


#### Ausrüstung

Skin hat er schon
Angel, die er ins Feuer hält ??

-->  möchte ihn an ein kleines Lagerfeuer setzen


#### Standort

ungefähr da, muss noch versetzt werden

```yml
x: 3440
y: 125
z: -2816
world: Faldoria, Eisenküste
``` 

##Items

### Magische Asche

zu nichts zu gebrauchen, droppt beim Monster

```yml
name: Magische Asche
type: PLUNDER
quality: COMMON
item: gunpowder
lore: Memento Mori
max-stack-size: 1
```

### Schwert 

Belohnung für Krieger...

```yml
name: 
type: 
quality: 
item: 
lore: 
max-stack-size: 1
```


### Dolch 

Belohnung für Assassine

```yml
name: 
type: 
quality: 
item: 
lore: 
max-stack-size: 1
```


### Bogen 

Belohnung für Waldläufer

```yml
name: 
type: 
quality: 
item: 
lore: 
max-stack-size: 1
```
### Stab 

Belohnung für Elementarist, Kleriker

```yml
name: 
type: 
quality: 
item: 
lore: 
max-stack-size: 1
```

## Mobs

### Die Quelle allen Übels

```yml
name: Die Quelle allen Übels
type: blaze
min-level: 3
max-level: 5
min-health: 100
max-health: 120
min-damage: 3
max-damage: 5
spawn-chance: 1.0
spawning-naturally: false
loot-table: gunpowder --> s. Item
aggro: true
```

## Belohnung

[Kehre zu Renlik zurück](#kehre-zu-renlik-zurueck)
> 10 Heller  
> 15 exp

## Referenzen


https://git.faldoria.de/tof/plugin-configs/RCQuests/blob/develop/quests/eisenkueste/eisenkueste_mobs.PNG

