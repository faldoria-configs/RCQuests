# Frische Zutaten


Adanion, der Koch der Eiseküste steht im Camp in der provisorischen Küche.


## Ablauf

1. Der Spieler geht, angezogen vom Duft der Küche zum Koch Adanion.
2. Der Koch spricht den Spieler an und bittet ihn, frische Zutaten zu besorgen.
3. Der Spieler besorgt sie, aber der Koch braucht noch andere.
4. Diese reichen immer noch nicht, so dass der Spieler noch ein drittes Mal losziehen muss. 


## Vorraussetzungen

lvl ?
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

Adanion spricht Spieler an, wenn er in 5 Block Reichweite ist

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

> 1. Spieler: Vielleicht kann euch jemand anderes helfen
     Adanion: Schade 

`[Ende]`


> 2. Spieler: Was brauchst du genau?

Weiter mit #2:

```yml
Adanion: Mein Eintopf benötigt einige weiße Beeren, aber auch einige Magus-Beeren. Ich hoffe sie wachsen hier überhaupt. Im Wald wirst du wohl am ehesten fündig. 
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
Adanion: Ich glaube, ein wenig Fleisch würde dem ganzen eine würzige Note geben. Besorg mir doch ein wenig  Fisch und etwas Kiesfloh Fleisch.
```
`[Ende]`


> 1. Spieler: NEIN, besorg dir deinen Kram selbst! 
     Adanion: Ich hätte mehr von jemandem wie dir erwartet!

> 2. Spieler: Na gut, ich bringe dir das auch noch…
     Adanion: Ausgezeichnet!


Weiter nach Antwort #2

`[Quest START]` [3. Fleisch macht es besser.](#fleisch-macht-es-besser)

**QuestLog:**  *Gehe zum Strand, besorge 10x Kiesfloh-Fleisch, 3x rohen Lachs und 7x rohen Fisch.*

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
Spieler: Na gut, ich bin ja eine geduldige Person...
```
`[Ende]`

`[Quest START]` [5. Es fehlt noch was.](#es-fehlt-noch-was)

**QuestLog:**  *Suche 10 Pilze für Adanion.*

Spieler sucht im Wald nach 10 Pilzen, 

`[Quest START]` [4. Kehre mit den Pilzen zu Adanion zurück.](#kehre-mit-den-Pilzen-zu-Adanion-zurueck)

Spieler kehrt zu Adanion zurück
 
```yml
Adanion: Gott sei Dank. Bist du mit den Pilzen zurück?
Spieler: JA. Lass mich raten, du hast noch etwas vergessen...?
Adanion: FABELHAFT. Wovon redest du? Warte kurz, schnell die Pilze schneiden, anrösten und rein damit. Dreimal nach rechts rühren, kurz warten, dreimal nach links rühren und - es ist fertig! Und es schmeckt absolut köstlich! 
Spieler: Wurde auch Zeit… 
Adanion: Ich danke dir! Jetzt gibt es auch mal wieder etwas Anständiges zum Essen! Hier ist deine Belohnung. - Adanion reicht dir eine Schüssel dampfenden Eintopf - 
```
`[Ende]`


## NPC

### Koch Akisk

Ein genialer, etwas zerstreuter Koch


#### Standartsätze

##### Vor der Quest
keine

##### Während der Quest

######  Teil 1: Frische Zutaten

> Adanion: Nun, war es schwierig, die Beeren zu finden?
  Spieler: Leider habe ich noch nicht alle, aber ich suche nochmals. Ich kann sie im Wald finden, sagtest du?
  Adanion: Ja klar, im Wasser wachsen sie nicht.

######  Teil 3: Fleisch macht es besser

> Adanion: Und, waren die Kiesflöhe lästig? Hast du die Fische auch?
  Spieler: Leider habe ich noch nicht alle Zutaten. 
  Adanion: Na, dann aber fix!

######  Teil 5: Es fehlt noch was

> Adanion: Hast du genügend Pilze?
  Spieler: Reichen die veilleicht schon? 
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
x: 3654
y: 67
z: -2828
world: Faldoria, Eisenküste
``` 

## Items

### Magus Beeren

```yml
name: Magus-Beere
type: ROHSTOFF
quality: rare
item: 
lore: 
max-stack-size: 16
```

### Weiße Beeren

Weiße Beeren, die..

```yml
name: Weiße Beere
type: ROHSTOFF
quality: COMMON
item: 
lore: Dieses Beere wächst gerne...
max-stack-size: 64
```

### Kießflohfleisch

```yml
name: Kiesflohfleisch
type: ROHSTOFF
quality: COMMON
item: ?
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

### Eintopf

```yml
name: Adanions Bester
type: ?
quality: COMMON
item: rabbit_stew
lore: Schmeckt einfach köstlich.
max-stack-size: 64
```



## Belohnung: 

Adanions Eintopf 
Weitere Belohnung überprüfen (Vervollständigen einer Rüstung)









Spieler erhält: [x] Erfahrung, [x] Geld, 1 Kiesfloh-Pilzeintopf [regeneriert Mana und/oder Herzen]

Quest Abgeschlossen: Es fehlt noch was




> 1. Spieler: NEIN, leider noch nicht
     Adanion: Na los, die Leute hungern ja schon!

> 2. 