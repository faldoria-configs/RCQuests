# Lewis NonQuestNPC <!-- omit in toc -->

Lewis ist ein ängstlicher junger Kaishi der als Feldarbeiter das Dorf unterstützt.

## Ausrüstung

Feldhacke in der Hand

## Standort

```yml
x: -57
y: 83
z: -22
world: Ankanor
```

## Dialog 1

1. Lewis: Hallo [Spieler], was machst du hier bei den Feldern? Willst du wieder Erdäpfel klauen?
    1. Spieler: Ich klaue nicht, ich hole nur meinen Anteil. Du gehst wie immer deiner Arbeit nach? 
        1. Lewis: Ja, und... ich bin wieder so nah an dem Brunnen.
            1. Spieler: Was ist mit dem Brunnen? Immer noch Angst davor?
                1. Lewis: Er ist gruselig, ich höre immer ein Grollen in seiner nähe, hörst du es nicht?
                    1. Spieler: Moment... Irgendwas ist da, aber das ist sicher nur das Wasser was da Geräusche macht.
                        1. Lewis: Danke das du mich versuchst zu beruhigen, aber ganz beruhigt bin ich noch immer nicht. 
                            1. Spieler: Mach dir nicht so viele Gedanken. [Sprung zu Dialog 2](#dialog-2)
                    2. Spieler: Moment... Nein ich höre nichts, du bildest dir das nur ein.
                        1. Lewis: Du glaubst mir also auch nicht. [Ende]
    2. Spieler: Pssst, nicht so Laut, das darf keiner wissen.
        1. Lewis: Ok, ich will dir ja auch keinen ärger machen, sonst passiert mir auch noch was, weil ich dich nie aufgehalten habe.
            1. Spieler: Genau, aber sicher kommt gleich jemand, ich sollte schnell weiter. [Ende]
            2. Spieler: Du solltest nicht immer so viel Angst haben. Sonst verpasst du noch ganz viel. Schau dir mich an.
                1. Lewis: Dorftrottel werden? ... Entschuldige. [Ende]


## Dialog 2

Wenn der Spieler zuvor mit Lutz gesprochen hat und folgenden Tag erhalten hat tritt folgender Dialog ein.
> Tag: Ankanor.lutz-faulenzen - *Bekommt der Spieler wenn er mit Lutz gesprochen hat und der Spieler zustimmt ihn beim Faulenzen zu decken.*

1. Lewis: Hast du Lutz gesehen? Roschick hat ihm gesagt er solle mir heute helfen. Wenn du ihn siehst sag ihm das ich auf ihn warte.
    1. Spieler: [Lügen] Ja ich habe ihn gesehen. Er ist Krank und kann nicht helfen kommen. Er sagte du musst alleine klarkommen. 
        1. Lewis: Oh nein, ich hoffe es geht ihm bald besser. [Ende]
    2. Spieler: [verraten] Er hatte mich gebeten dir zu sagen das er Krank sei, er möchte lieber faulenzen.
        1. Lewis: Dieser Faulpelz soll seinen Arsch hier her bewegen. Ich werde Roschik davon erzählen. Danke das du ehrlich zu mir warst. [Ende]

Wenn der Spieler nicht mit Lutz vorher gesprochen hat tritt folgender Dialog ein.

1. Lewis: Hast du Lutz gesehen? Roschick hat ihm gesagt er solle mir heute helfen. Wenn du ihn siehst sag ihm das ich auf ihn warte.
    1. Spieler: Nein ich habe ihn nicht gesehen. Soll ich ihm sagen das du nach ihm suchst wenn ich ihn sehe?
        1. Lewis: Das wäre sehr nett von dir. Danke.

> TAG: Ankanor.lewis-bitte - *Bekommt der Spieler wenn er mit Lewis gesprochen hat bevor er mit Lutz sprach.*
