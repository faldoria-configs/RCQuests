# Angriff ist die beste Verteidigung

NPC: 'Rechte Hand' Marduks: Bari, steht neben Marduk

Bari ist der Stellvertreter von Hauptmann Marduk und bei weitem kriegerischer eingestellt als dieser. Ein untypischer Kaishi.


##Änderungen

Text ziemlich umgeschrieben und angepasst. 
Der Anfang war einfach unpassend - Bari steht neben Maduk und sollte wissen, was passiert ist, außerdem hört er die ganze Zeit schon zu. Ich würde die Quest später ansetzen und erst kurz vor der Abfahrt anbieten..


## Ablauf

1. Der Spieler wird von Bari angesprochen, er will, dass der Spieler für ihn Schmuggler tötet.
2. Spieler stellt die Notwendigkeit in Frage
3. Bari überzeugt den Spieler (nicht)
4. Der Spieler tötet die Schmuggler und den Anführer.
5. Er kehrt zu Bari zurück.

## Voraussetzungen

HQ [Was ist passiert](#was-ist-passiert)

HQ [Reparaturarbeiten](#reparaturarbeiten)

Nachdem der Spieler die Quest bei Marduk abgegeben hat, kann Bari ihn ansprechen.

lvl 4,
genug Ausrüstung


## Questdialoge

1. Bari: *mürrisch*  Bevor du auf Abenteuerreise gehst und in die schöne neue Welt aufbrichst, gäbe es eigentlich noch mehr Aufgaben, die du erledigen könntest. Es würde uns, die wir vorerst im Lager zurückbleiben müssen, das Leben etwas erleichtern. *Bari schielt etwas zu Marduk hinüber*
   1. Spieler:  *du schaust etwas erschrocken ob des Ausbruchs*  Aber gerne, was soll ich tun?
      1. Bari: Es gibt hier eine Höhle mit ein paar zwielichtigen Gestalten. Sie scheinen sich auf einen Kampf vorzubereiten.
         1. Spieler: Einen Kampf?
            1. Bari: *unwirsch*  Ja, einen Kampf! Und wir werden das Angriffsziel sein!
               1.Spieler: Woher wollt Ihr das wissen?
                  1. Bari: Das weiß ich aus Erfahrung! Wen bitteschön sollten sie wohl sonst als Ziel haben? Die Schimmerwölfe und Bergeisenkatzen? Es ist sonst niemand da, den sie angreifen könnten, außer wir!
                     1. Spieler: Aber ich soll sie als Erstes angreifen? Wieso bereiten wir uns nicht darauf vor und verteidigen uns, wenn sie wirklich kommen?
                         1. Bari: Weil wir nicht stark genug sind. Kaum einer kann hier kämpfen. Nur durch den Überraschungeffekt können wir die Schmuggler kriegen. Du musst dich anschleichen und einen nach dem anderen erledigen. 
                             1. Spieler: Aus dem Hinterhalt
                                1. Bari: Angriff ist die beste Verteidigung.

                           
                                    1. Spieler: Ich kann das nicht machen, auf Leute schießen, die mir  - noch - nichts getan haben, das bringe ich einfach nicht fertig. `[Ende]`


                                    2.Spieler: Ich tu es, auch wenn mich das Gewissen drückt, aber ich will auch helfen, das Camp sicherer zu machen. 
                                        2.1 Bari: Nimm dir aus der Truhe dort den Helm und die Waffe, um gegen sie gewappnet zu sein. 
                                           2.1 Spieler: Wo finde ich die .. Schmuggler?
                                              2.1 Bari: Geh in Richtung Südwesten, dort im Fels ist eine Höhle, dort sollten sich die Schmuggler aufhalten. Versuche den Anführer zu töten. Er trägt einen roten Hut. Den will ich sehen. 
                                         


`[QUEST START]` [Angriff ist die beste Verteidigung](#angriff-ist-die-beste-verteidigung)  
> **QuestLog:** *Geh' in Richtung Südwesten, dort im Fels ist eine Höhle, dort sollten sich die Schmuggler aufhalten. *
- Töte 15 Eisen Schmuggler
- Bring den roten Hut des Anführers zu Bari.

Anführer droppt seinen roten Hut.

Spieler kehrt zu Bari zurück:



1. Bari: Hast du die Bande getötet und den Hut?
    1. Spieler: Hier ist der rote Hut. Ich habe alle getötet, die sich mir in den Weg gestellt haben.
        1. Bari: In den Weg gestellt?
            1. Alle, die ich gesehen habe.
                1. Nun gut, nimm dies als Belohnung, dass du über deinen Schatten gesprungen bist. Die Leute werden dir dankbar sein, dass sie wieder friedlich schlafen können und sich keine Gedanken mehr machen müssen.
                    1. Dankeschön `[Ende]` 


## NPC: 

### Bari

Bari ist Marduks rechte Hand, aber während Marduk keine Kämpfer ist, wurde Bari schon immer von Kampf und Auseinadersetzung angezogen. Er ist ein kriegerischer Typ, ganz untypisch Kaishi. Durch die Missachtung seiner Vorlieben in der Kaishi Gesellschaft ist er auch mürrisch geworden. Er setzt auf das Recht des Stärkeren und hat kein Verständnis für die Bedenken anderer Kaishi, was das Töten angetrifft, wenn es um sein Leben und das seiner Mitbewohner geht. Hauptmann Marduk versucht ihn zu bremsen, ist aber auf seine Fähigkeiten angewiesen.  

#### Standartsätze

##### Vor der Quest:

> Kümmere dich um deinen Kram!

##### Während der Quest:

1. Bari: Hast du die Bande getötet und Anführer auch?
    1. Spieler: Ich habe noch nicht alle erwischt.
       1. Dann sieh zu, dass du fertig wirst, sonst fährt der Ballon ohne dich.

##### Nach der Quest:

1. Immer noch da? Schau, dass du weiter kommst. 

#### Ausrüstung

Skin: Kriegerisch,
Schwert in der Hand

#### Standort:

```yml
x: 3645
y: 64
z: -2829
world: faldoria.eisenküste
```

## Items:

### Roter Hut 

Questitem/Drop: Hut des Anführers

```yml
name: Roter Hut
type: Quest
quality: COMMON
item: leather_helmet (red)
lore: Ein roter, auffälliger Hut.
max-stack-size: 1
```

### Waffen aus Kiste

####  Schwert (für Krieger)

```yml
name: Banditentod
type: Quest
quality: COMMON Werte?
item: iron_sword  (leicht verzaubert)
lore: leicht und scharf 
max-stack-size: 1
```

####  Dolch (für Assassine)

```yml
name: Banditentod
type: Quest
quality: COMMON
item: iron_sword  (leicht verzaubert)
lore: Dieser Dolch ist scharf
max-stack-size: 1
```

####  Bogen (für Waldläufer)

```yml
name: Banditentod
type: Quest
quality: COMMON
item: bow  (leicht verzaubert)
lore: 
max-stack-size: 1
```

###  Stab (für Kleriker und Elementarist)

```yml
name: Banditentod
type: Quest
quality: COMMON
item: ?? (leicht verzaubert)
lore: 
max-stack-size: 1

```


## Belohnung:

Darf obige Waffe behalten?





