# Heilpflanzen für Mairi

Issue 60

>>> Skill Bandagieren 1 (= Bandagen benutzen) wird erlernt!

## Was noch fehlt:

Die benötigten Blumen müssen im Wald gesetzt werden

## Übersicht
- [Heilpflanzen für Mairi](#heilpflanzen-f%C3%BCr-mairi)
  - [Was noch fehlt:](#was-noch-fehlt)
  - [Übersicht](#%C3%BCbersicht)
  - [Voraussetzungen](#voraussetzungen)
  - [Ablauf](#ablauf)
  - [Questdialoge](#questdialoge)
    - [Dialog 1](#dialog-1)
    - [Dialog 2](#dialog-2)
  - [NPCS](#npcs)
    - [Mairi](#mairi)
      - [Standartsätze](#standarts%C3%A4tze)
        - [Vor der Quest](#vor-der-quest)
        - [Während der Quest:](#w%C3%A4hrend-der-quest)
        - [Nach der Quest:](#nach-der-quest)
      - [Ausrüstung](#ausr%C3%BCstung)
      - [Standort](#standort)
  - [Items](#items)
    - [Einfache Bandage](#einfache-bandage)
  - [Belohnung](#belohnung)
  - [Referenzen](#referenzen)


        

## Voraussetzungen

NQ [Suche Mairis Familie](#suche-mairis-familie)

## Ablauf

1. Mairi fragt nun im Gegenzug, wie es dem Spieler geht
2. Der Spieler antwortet, je nach dem, ob er die Errungenschaft "Hat es zum Schiff geschafft" hat oder nicht. Er erwähnt eine Platzwunde am Kopf. 
3. Mairi schaut sie an und sagt, dass es gut wäre, sie mit bestimmten Kräutern zu behandeln.
4. Sie hat ein verletztes Bein und schickt deshalb den Spieler zum Heilpflanzen suchen.
5. Sie verspricht, ihm zu zeigen, wie man einen Wunde verbindet.
6. Der Spieler besorgt die benötigten Heilkräuter.
7. Mairi zeigt ihm das Bandagieren.
8. Spieler erhält den Skill "Bandagieren 1" 

## Questdialoge

### Dialog 1

```yml
Mairi: Sag, wie geht es dir, <Name des Spielers>?
```

Spieler:
>> Je nachdem ob er auf Ankanor gestorben ist (1.) oder nicht (2.)

> 1.  Nun, gut, wenn man bedenkt, dass ich den Weg auf’s Schiff fast nicht geschafft habe. So ein Mann von Agnatus hat mich niedergeschlagen und für tot zurückgelassen. Aber irgendjemand muss mich mit auf das Schiff geschleift haben, sonst wäre ich nicht hier. So habe ich nur diese Beule und Platzwunde als Erinnerung.

> 2. Gut, wenn man bedenkt, wie knapp ich dem Tod auf Ankanor entkommen bin und dann noch den Sturm und das Auseinanderbrechen des Schiffes überlebt habe. Mir ist nur die Beule und Platzwunde am Kopf als Erinnerung geblieben.

```yml
Mairi: Lass mal sehen, zeig mir deinen Kopf….  

*Du beugst dich und zeigst ihr deinen Kopf mit der Beule und Platzwunde*

Mairi: Oh, das sieht aber nicht schön aus. Da ist Dreck hineingekommen, das sollte ich behandeln, es eitert etwas. So eine Wunde am Kopf kann gefährlich werden. 
Spieler: Eiter? *Panik!* Was kann man ich dagegen tun?
Maori: Nichts, abwarten und hoffen, dass es nicht schlimmer wird. Was aber helfen würde, wäre eine bestimmte Pflanze. Ich weiß nicht, ob die hier wächst. Die zieht das Eiter aus der Wunde. 
Spieler: Ich könnte ja versuchen, sie zu finden. 
Mairi: Ja, das wäre sehr gut, ich kann nämlich nicht gut laufen, ich habe eine Verletzung am Bein.

*Mairi hebt ihren Rock etwas und zeigt dir ihr übel zugerichtetes Bein.*

Spieler: Oh, das sieht ja schrecklich aus. Sag mir schnell, was ich suchen soll. 
Mairi: Die grüne, farnähnliche Pflanze, die zwischen den Bäumen wächst. Und wenn du schon mal unterwegs bist, dann könntest du auch gleich etwas gegen  Husten und Halsweh mitbringen, da klagen schon viele darüber. Wir sind das kalte Wetter hier nicht gewohnt. Schau mal, ob du die blaue Heilorchidee findest oder die weiße Sternblume, die wären beide gut. Könntest du das tun?
```

1. 
> Spieler: Tut mir leid Mairi, ich habe grade keine Zeit, jetzt in den Wald zu gehen, ich habe noch so viele andere Aufgaben. 
```yml
Mairi: Schade, aber vielleicht klappt es ja später. Ich bräuchte auch jemand, der mein Bein verbindet, ich würde dir zeigen, wie das geht.
Spieler: Gerne, ich komme aber später wieder.
```
`[Ende]`

2. 
> Spieler:  Ich versuche sie zu finden, dann kannst du auch etwas davon auf dein Bein tun.
```yml
Mairi: Ja, du könntest mir mein Bein verbinden, ich leite dich an. 
Spieler: Das wäre großartig, wenn du mir das zeigen könntest! Ich hole schnell die Arzneiblumen. 
```


**QuestLog:** *Hole für Mairi im Wald die benötigten Arzneiblumen, 7 grüne Farne, 7 blaue Heilorchideen und 7 Sternblumen*

*Der Spieler.. erfüllt seine Aufgabe* 

### Dialog 2

```yml
Mairi: Da bist du ja wieder, <Name des Spielers>, hast du alles gefunden, was ich brauche?
```

> 1. Spieler: Ja, das war gar nicht so schwierig, es waren auch fast keine Wölfe unterwegs. Das sind sie. 
> *Du gibst Mairi deine Ausbeute*

```yml
Mairi: Wunderbar! Ich danke dir. Die Wölfe sind auch noch ein Grund, warum ich nicht so gerne in den Wald gehe, ich muss mich erst daran gewöhnen, dass Kräuter sammeln jetzt gefährlich sein kann. 

Mairi: Aber nun zeig mal deinen Kopf her.
```
*du beugst dich zu Mairi hinunter und sie säubert deine Wunde, legt einige der frischen Kräuter drauf und verbindet sie. 
```yml
Mairi: Es gibt zwar feinere Methoden, so eine Wunde zu verbinden, Bandagen, die an der Haut kleben, aber sowas haben wir jetzt hier nicht. So, jetzt bin ich fertig, jetzt kommst du dran. 

Mairi: Jetzt zeige ich dir, wie du mein Bein verbinden musst, dann kannst du es später, wenn du es brauchen solltest, für dich oder einen Kameraden.
```
*Mairi setzt sich hin, zieht ihren Rock hoch und streckt dir ihr Bein hin.*

```yml
Mairi: Als erstes nimmst du ein sauberes Tuch, feuchtest es etwas mit sauberem Wasser an, oder noch besser Kamillentee, wenn du den hast und entfernst den größten Schmutz aus der Wunde und außenrum. Auch angetrocknetes Blut, aber sei sehr vorsichtig und achtsam.
```

*Du folgst ihren Anweisungen und säuberst ihr Bein*

```yml
Mairi: Als nächstes legst du die Blätter des Farns drauf. Es wäre gut, wenn du die Blätter vorher etwas klopfst, damit der Saft austreten kann, aber notfalls geht es auch so. Ja, du machst das gut! Und jetzt kommen die sauberen Tücher rum, irgendwelche fusselfreien Stoffe sind gut, Leinen z.B. Fange unten am Knöchel an und wickle das Tuch um das Bein, so dass die Stoffbahnen sich etwas überlappen. Ja, genau so! Immer auf das Herz zuwickeln. Zum Schluß kommt dann als Schutz eine etwas gröberer Stoff herum, oder auch ein dünnes Leder, so dass das Bein Luft bekommt. Die letzte Lage musst du dann mit Schnüren vorsichtig festbinden, so dass es geradeso hält, nicht zu fest. Natürlich sollte ich jetzt nicht laufen. Wenn es nicht zu umgehen ist, kannst du auch einen Strumpf drüberziehen, so dass alles hält. Das werde ich jetzt wohl tun müssen.

Mairi: Danke <Name des Spielers> das hast du gut gemacht, jetzt hast du schon eine kleine Ahnung von der Heilkunst!
```

Spieler erhält Skill Bandage_1

```yml
Mairi: Hier, nimm als Dankeschön von mir einige fertig geschnittene und aufgewickelte Bandagen. Es wäre gut, wenn du immer einige dabei hast, denn wenn du sie brauchst, hast du nicht immer gleich eine zur Hand. Sonst musst du Streifen von deiner Kleidung reißen. 
```
*Mairi lacht dich jetzt an und du freust dich mit ihr*


## NPCS

### Mairi

Mairi ist Kräuterkundige und Heilerin und kann den Skill 'Bandagieren' lehren. Sie hat den Kontakt zu ihrer Familie verloren, seit Agnatus Schergen auf Ankanor einfielen und befürchtet, dass sie tot sein könnten. Ihre Kinder heißen Antosh und Irgrid, ihr Mann Arim. Auch Mimi hat sie auf Ankanor in ihre Familie aufgenommen.

 

#### Standartsätze

##### Vor der Quest
     nachdem Quest [Suche Mairis Familie](#suche-mairis-familie) abgeschlossen ist:

[Dialog 1](#dialog-1)

##### Während der Quest:

Mairi: Oh, du bist schn zurück, hast du schon alle Pflanzen gefunden?
Spieler: Leider nicht, die Wölfe kamen mir in die Quere, aber ich suche den Rest auch noch. 

##### Nach der Quest: 

1. Mairi: Schön dich zu sehen, <Name des Spielers>, *Mairi lächelt dich freundlich an*
   *Du grinst freundlich zurück*

#### Ausrüstung

Skin: 

#### Standort   

```yml
x: 3666
y: 64
z: -2804
world: faldoria.eisenküste
```


## Items

Item: engl. Bezeichnung hier: https://minecraft-ids.grahamedgecombe.com/


### Einfache Bandage

```yml
ID: 
name: Einfache Bandage
type: QUEST 
quality: COMMON 
item: paper
lore: Für notdürftiges, erstes Verbinden reicht's
max-stack-size: 16
```




## Belohnung

[Einfache Bandage](#einfache-bandage)



## Referenzen

Vorherige Quest:
[Suche Mairis Familie](#suche-mairis-familie)
























          





