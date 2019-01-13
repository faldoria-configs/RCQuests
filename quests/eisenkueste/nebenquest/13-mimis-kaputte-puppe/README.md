Mimis kaputte Puppe

Issue 78

## Übersicht

- [Übersicht](#%C3%BCbersicht)
- [Voraussetzungen](#voraussetzungen)
- [Ablauf](#ablauf)
- [Questdialoge](#questdialoge)
  - [Innerer Monolog](#innerer-monolog)
  - [```[Queststart]```](#queststart)
  - [Dialog 1](#dialog-1)
- [Dialog 2](#dialog-2)

## Voraussetzungen

[HQ Was ist passiert?](../1-was-ist-passiert/README.md) - Abgeschlossen

[HQ Reparaturarbeiten](../2-reparaturarbeiten/README.md) - Abgeschlossen


## Ablauf

1. Der Spieler läuft an Mimi vorbei und hört sie weinen.
2. Er fragt sich, ob er sie ansprechen soll - und kann die quest annehmen
3. Sie zeigt ihm ihre kaputte Puppe
4. Er merkt vielleicht, das an der etwas Besonderes ist.
5. Er verspricht zum Schluß, ihr zu helfen (oder auch nicht) und kann weitere offen bleibende Quest annehmen. 

## Questdialoge

### Innerer Monolog

Spieler: *Du siehst, dass Mimi traurig da sitzt, Tränen laufen ihr die Wange hinab und du überlegst, ob du sie ansprechen sollst*

> 1. Spieler: Hmm, soll ich mit ihr reden? Lieber nicht.. 

```[Ende]```

> 2. Spiele: Das arme Ding, ich werde versuchen, sie zu trösten


Klickt der Spieler Mimi an, hat er die Quest: NQ [Rede mit Mimi](#rede-mit-mimi)
angenommen.

### ```[Queststart]```

**Questlog** *Rede mit Mimi und tröste sie*

### Dialog 1

```yml

Spieler: Aber Mimi, was ist den los, warum weinst du denn. Ist dir kalt? 
Mimi: Kalt ist mir auch, aber das ist nicht so schlimm, aber sieh her, meine Puppe ist ganz kaputt. Oh meine arme Aneli!
```

> 1. Falls der Spieler die Quest [Mimi braucht Hilfe](#mimi-braucht-hilfe) abgeschlossen hat:

`Spieler: Oh je, die war doch noch ganz, als ich sie dir aus dem Haus geholt habe, nicht wahr? Wie ist das passiert?
`

> 2. Falls der Spieler die Quest [Mimi braucht Hilfe](#mimi-braucht-hilfe) nicht gemacht hat:

```yml
Spieler: Oh je, die schaut übel aus, aber das ist doch nur eine Puppe, du lebst, das ist wichtiger!
Mimi: Was verstehst du von Puppen! Meine Aneli ist lebendig, *Mimi schaut auf die zerstörte Puppe* jedenfalls fast.
Spieler: Wie ist das denn passiert?
```

## Dialog 2

```yml
Mimi: Als ich zum Schiff gerannt bin, hat ein schwarzer Mann auf mich geschossen, mit einem brennenden Pfeil! Aber der Pfeil ist in Aneli stecken geblieben. Ich bin hingefallen, auf Aneli drauf, da ging das Feuer aus und der Pfeil auch raus.
Spieler: Und dir ist nichts passiert? Wieso lebst du noch, wenn auf dich geschossen wurde?
Mimi: *zuckt mit den Schultern* Meine Puppe hat mich beschützt!
Spieler: *du schaust etwas ungläubig, bemerkst erst jetzt, dass einige ihrer roten Locken versengt sind, ihr verschmiertes Gesicht ist notdürftig gesäubert*
Spieler: Wie soll das denn gegangen sein?
Mimi: Schau sie dir doch mal an
*Sie reicht dir die zerstörte Puppe, nur der feine geschnitzte Kopf wie auch die Hände und Füße aus hartem Holz scheinen halbwegs in Ordnung zu sein, der restliche Körper schaut übel aus. Du nimmst die Puppe in die Hand und bemerkst, dass etwas Hartes in ihren kaputten Torso steckt.* 
Spieler: Was ist denn das, da ist was Hartes drin!
Mimi: Ja, das ist ihr Herz, das hat den Pfeil abgehalten.
*Mimi nimmt die Puppe wieder an sich, bevor du sie näher untersuchen kannst*
Spieler: Und was soll ich jetzt tun?
Mimi: Du besorgst mir die Sachen, die wir brauchen, um Aneli wieder ganz zu machen.
Spieler: Aber woher soll ich wissen, was man dazu braucht, und woher soll ich das bekommen?
*Mimi zuckt mit den Schultern*
Mimi: Frag halt Leute, wie man eine Puppe wieder heil macht.
Spieler: *Du siehst Wolle, die aus dem Körper der Puppe quillt, der Rest scheint Leder oder auch ein fester Stoff zu sein. *
Mimi: Du kannst das bestimmt, auf dich hören die Leute auch. Mich lachen sie doch bloß aus, wenn ich frage, eine Puppe ist nicht wichtig. Mairi würde mir bestimmt helfen, aber die ist so beschäftigt...
```
`[Questende]` 

> 1. Spieler: Mimi, ich habe jetzt wirklich keine Zeit, mich um eine kaputte Puppe zu kümmern, ich fliege jetzt bald mit dem Ballon weg. Du musst dir jemand anders suchen.

`Mimi: *traurig* Ich dachte, du bist mein Freund`

`[Ende]`


> 2. Mimi, ich weiß nicht, wie ich das machen soll, ich fliege jetzt bald mit dem Ballon weg, wie soll ich dir helfen, deinen Puppe wieder heil zu machen?

`Mimi: Vielleicht triffst du ja irgendwo jemand, der sich mit Puppen auskennt - vor allem so besonderen wie meine ...`

`Spieler: *seufzt* : Na, ich verspreche nichts, aber ich werde sehen, was ich tun kann. `

`[Queststart]`  [Puppendoktor]

**Questlog** *Suche jemanden, der dir hilft, Mimis Puppe zu reparieren. In Eisenküste wirst du niemanden finden*


Der Spieler trifft in Kaltenstrom (oder vorher?) auf jemand, der Reparatuarbeiten aller Art macht und kann Stoff, Leder und Wolle kaufen  - oder fertigen Puppenkörper? 
Der Spieler trifft Mimi wieder in Kaltenstrom. 