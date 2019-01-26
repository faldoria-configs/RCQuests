# Frische Zutaten

Issue 15


[Adanion](#adanion), der Koch der Eiseküste steht im Camp in der provisorischen Küche.

## Noch zu tun.

Weiße Beeren, Magus Beeren?  
(Schimmerwölfe, normale Mobs, droppen was?)
Standort fertig

## Übersicht

- [Voraussetzungen](#voraussetzungen)
- [Ablauf](#ablauf)
- [Questdialoge](#questdialoge)
   
- [NPCs](#npcs)
     - [Adanion](#adanion)
         - [Standartsätze](#standartsaetze)
            - [Vor der Quest](#vor-der-quest)
            - [Während der Quest](#waehrend-der-quest)
            - [Nach der Quest](#nach-der-quest)
         - [Ausrüstung](#ausruestung)
         - [Standort](#standort)
-  [Mobs](#mobs)
   
-  [Items](#items)
      -  [Weiße Beere](#weisse-beere)
      -  [Magus-Beere](#magus-beere)
      -  [Kießflohfleisch](#kiesflohfleisch)
      -  [Pilze](#pilze)
      -  [Roher Fisch](#roher-fisch)
      -  [Roher Lachs](#roher-lachs)
      -  [Adanions Eintopf](#adanions-eintopf)
   

- [Belohnung](#belohnung)

## Ablauf

1. Der Spieler geht, angezogen vom Duft der Küche zum Koch Adanion.
2. Der Koch spricht den Spieler an und bittet ihn, frische Zutaten zu besorgen.
3. Der Spieler besorgt sie, aber der Koch braucht noch andere.
4. Diese reichen immer noch nicht, so dass der Spieler noch ein drittes Mal losziehen muss. 


## Vorraussetzungen

HQ [Was ist passiert](#1.-was-ist-passiert?)  abgeschlossen
HQ `[QUEST UPDATE]` [Was ist passiert](#1.-was-ist-passiert?)
> **QuestLog:** *Erkunde die Gegend und schau dir das Licht am Berg im Westen an. Finde heraus ob dort jemand lebt.*  angenommen


lvl 2  
Waffe von Ankanor?
Rüstung?


## Aufgaben

1. Frische Zutaten  - Besorge 4 Magus-Beeren und 6 weiße Beeren
2. Kehre mit den Früchten zu Adanion zurück.
3. Fleisch macht es besser - Besorge 10 Kiesflohfleischstücke, 7 Fische und 3 Lachse
4. Kehre mit dem Fleisch zu Adanion zurück.
5. Es fehlt noch was.
6. Kehre mit den Pilzen zu Adanion zurück.


## Questdialoge

### 1. Frische Zutaten

Adanion spricht Spieler an, wenn er in 7 Block Reichweite ist

```yml
Adanion: Hallo, du da, kannst du kurz mal herkommen?
Spieler: Ja? Brauchst du Hilfe bei etwas?
Adanion: Ja, denn ich habe viel zu tun, weil ich ein kleines Mahl herrichten soll.
Spieler: Und wo liegt das Problem?
Adanion: Mir sind die frischen Zutaten ausgegangen und nun kann ich nichts Gutes kochen.
Spieler: Wieso besorgst du nicht einfach einige Zutaten?
Adanion: Ich kenne mich hier noch nicht allzu gut aus und ich muss ja mit dem was wir haben, schon mal anfangen.
Spieler: Dann genüge dich doch mit dem was da ist.
Adanion: Wir brauchen aber bessere Nahrung. Vor allem die Alten und die Kinder brauchen frische Nahrung.
```

> 1. Spieler: Vielleicht kann dir jemand anderes helfen
     Adanion: Schade 

`[Ende]`


> 2. Spieler: Was brauchst du genau?

Weiter mit #2:

```yml
Adanion: Mein Eintopf benötigt einige [Weiße Beeren](#weisse-beeren), aber auch einige [Magus-Beeren](#magus-beeren). Ich hoffe sie wachsen hier überhaupt. Im Wald wirst du wohl am ehesten fündig. 
```

`[Quest START]` [1. Frische Zutaten](#frische-zutaten)


**QuestLog:**  *Sammle im Wald 4 Magus-Beeren und 6 weiße Beeren.*


Der Spieler geht in den Wald und sammelt die Beeren. 
`[Ende]`



`[Quest START]` [2. Kehre mit den Beeren zu Adanion zurück.](#kehre-mit-den-Beeren-zu-Adanion-zurueck)

Spieler kehrt zurück.


```yml
Adanion: Da bist du ja wieder! Hast du die Beeren? 
Spieler: Ja, sie wachsen tatsächlich oben im Wald.
Adanion: Warte etwas, dann kannst du gleich mal probieren....  Oh nein!.....  Ich fürchte das geht so nicht. 
Spieler: Wieso, was ist los? 
Adanion: Das Aroma stimmt nicht! So etwas kann ich nicht servieren! Das geht nicht. Du musst mir noch ein paar andere Dinge besorgen. 
Spieler: Was brauchst du denn noch? 
Adanion: Ich glaube, ein wenig Fleisch würde dem ganzen eine würzige Note geben. Besorg mir doch ein wenig  Fisch und etwas [Kiesflohfleisch](#kiesflohfleisch).
```
`[Ende]`


> 1. Spieler: NEIN, besorg dir deinen Kram selbst! 
     Adanion: Ich hätte mehr von jemandem wie dir erwartet!

`[Ende]`

> 2. Spieler: Na gut, ich bringe dir das auch noch…
     Adanion: Ausgezeichnet!


**Weiter nach Antwort #2**

`[Quest START]` [3. Fleisch macht es besser.](#fleisch-macht-es-besser)

**QuestLog:**  *Gehe zum Strand, besorge 10x Kiesflohfleisch, 3x rohen Lachs und 7x rohen Fisch.*

Spieler besorgt das Gewünschte.

`[Ende]`

`[Quest START]` [4. Kehre mit dem Fleisch zu Adanion zurück.](#kehre-mit-dem-Fleisch-zu-Adanion-zurueck)

Spieler kehrt zu Adanion zurück


```yml
Adanion: Hast du mir das Fleisch besorgt? 
Spieler: JA, kannst du jetzt endlich deinen Eintopf kochen?  
Adianon: Hhmmh, nun ja… ich muss zugeben, ich habe noch eine Kleinigkeit vergessen.  
Spieler: WAS BRAUCHST DU DENN JETZT NOCH? 
Adianon: Ich brauche noch eine kleine Ration meiner Spezialzutat. Ich würze meinen Eintopf immer noch mit einigen Pilzen. Wenn du mir die noch beschaffst, bekommst du für deine Mühen auch etwas! 
```
`[Ende]`

> 1. Jetzt reicht es aber wirklich, ich habe jetzt was anderes zu tun. `[Ende]` --> Keine Belohnung!

> 2. Spieler: Na gut, ich bin ja eine geduldige Person...

**Weiter nach #2.**

`[Quest START]` [5. Es fehlt noch was](#es-fehlt-noch-was)

**QuestLog:**  *Suche 10 Pilze für Adanion.*

Spieler sucht im Wald nach 10 Pilzen, 

`[Quest START]` [4. Kehre mit den Pilzen zu Adanion zurück.](#kehre-mit-den-Pilzen-zu-Adanion-zurueck)

Spieler kehrt zu Adanion zurück
 
```yml
Adanion: Gott sei Dank. Bist du mit den Pilzen zurück?
Spieler: JA. Lass mich raten, du hast noch etwas vergessen...?
Adanion: FABELHAFT. Wovon redest du? Warte kurz, schnell die Pilze schneiden, anrösten und rein damit. Dreimal nach rechts rühren, kurz warten, dreimal nach links rühren und - es ist fertig! Und es schmeckt absolut köstlich! 
Spieler: Wurde auch Zeit… 
Adanion: Ich danke dir! Jetzt gibt es auch mal wieder etwas Anständiges zum Essen! Hier ist deine Belohnung. *Adanion reicht dir eine Schüssel dampfenden Eintopf* 
```
`[Ende]`


## NPC

### Koch Akisk

Ein genialer, etwas zerstreuter Koch


#### Standartsätze

##### Vor der Quest

*der Koch murmelt abwesend vor sich hin, du verstehst nicht, was er sagt*

##### Während der Quest

######  Teil 1: Frische Zutaten

> Adanion: Nun, war es schwierig, die Beeren zu finden?
  Spieler: Leider habe ich noch nicht alle, aber ich suche nochmals. Ich kann sie im Wald finden, sagtest du?
  Adanion: Ja klar, im Wasser wachsen sie nicht.

######  Teil 2: Fleisch macht es besser

> Adanion: Und, waren die Kiesflöhe lästig? Hast du die Fische auch?
  Spieler: Leider habe ich noch nicht alle Zutaten. 
  Adanion: Na, dann aber fix! Die Leute haben schon schrecklichen Hunger!

######  Teil 3: Es fehlt noch was

> Adanion: Hast du genügend Pilze?

  Spieler: Reichen die vielleicht schon? 
  Adanion: Nein, das ist nichts, da brauche ich schon mehr, das Aroma, denk an das Aroma!
  Spieler: Nagut, ich mach mich nochmals auf die Socken.

##### Nach der Quest:

> Adanion: Sag bloß, du willst noch mehr Eintopf, der ist leider aus. 
  Spieler: Schade

> Adanion: Jetzt störe mich bitte nicht, Kochen ist eine kreative Kunst!

> Adanion: Du willst mehr für mich besorgen? Morgen vielleicht!

#### Ausrüstung

Skin mit Kochschürze
In der Hand - Schüssel?

#### Standort

```yml
x: 3607
y: 67
z: -2807
world: Faldoria, Eisenküste
``` 

## Items

### Magus Beere

```yml
name: Magus Beere
type: ROHSTOFF
quality: rare
item: allium
lore: Eine Beere, der man magische Eigenschaften nachsagt
max-stack-size: 16
```

### Weiße Beere


```yml
name: Weiße Beere
type: ROHSTOFF
quality: COMMON
item: azure_bluet
lore: Tarnt sich gerne im Schnee
max-stack-size: 64
```

### Kießflohfleisch

```yml
name: Kiesflohfleisch
type: ROHSTOFF
quality: COMMON
item: rotten_flesh
lore: Wenn's sein muss, kann man's essen. 
max-stack-size: 64
```


### Pilze

```yml
name: Schwammerling
type: ROHSTOFF
quality: COMMON
item: brown_mushroom
lore: Hat schon manch Einen vor dem Hungertod bewahrt.
max-stack-size: 64
```

### Roher Fisch

```yml
name: Roher Fisch
type: ROHSTOFF
quality: COMMON
item: cod
lore: Gebraten schmeckt er besser.
max-stack-size: 64
```

### Roher Lachs

```yml
name: Roher Lachs
type: ROHSTOFF
quality: COMMON
item: salmon
lore: Auch roh genießbar.
max-stack-size: 64
```

### Adanions Eintopf

```yml
name: Adanions Eintopf
type: ?
quality: COMMON
item: rabbit_stew
lore: Schmeckt einfach köstlich.
max-stack-size: 64
```



## Belohnung: 

[Adanions Eintopf](#adanions-eintopf)
Weitere Belohnung überprüfen (Vervollständigen einer Rüstung)









Spieler erhält: [x] Erfahrung, [x] Geld, 1 Kiesfloh-Pilzeintopf [regeneriert Mana und/oder Herzen]

Quest Abgeschlossen: Es fehlt noch was




