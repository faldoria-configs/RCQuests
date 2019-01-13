Mimis kaputte Puppe

Issue 78

## Noch zu tun

- Skin anziehen
- Standort festlegen

## Übersicht

- [Noch zu tun](#noch-zu-tun)
- [Übersicht](#%C3%BCbersicht)
- [Voraussetzungen](#voraussetzungen)
- [Ablauf](#ablauf)
- [Questdialoge](#questdialoge)
  - [Innerer Monolog](#innerer-monolog)
  - [`[Queststart]` NQ Rede mit Mimi](#queststart-nq-rede-mit-mimi)
  - [Dialog 1](#dialog-1)
  - [Dialog 2](#dialog-2)
  - [`[Queststart]` [Puppendoktor]](#queststart-puppendoktor)
- [NPCS](#npcs)
  - [Mimi](#mimi)
    - [Standartsätze](#standarts%C3%A4tze)
      - [Vor der Quest:](#vor-der-quest)
      - [Während der Quest:](#w%C3%A4hrend-der-quest)
      - [Nach der Quest:](#nach-der-quest)
    - [Ausrüstung](#ausr%C3%BCstung)
    - [Standort](#standort)
- [Referenzen](#referenzen)

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

### `[Queststart]`  NQ [Rede mit Mimi](#rede-mit-mimi)

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

### Dialog 2

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

### `[Queststart]`  [Puppendoktor]

**Questlog** *Suche jemanden, der dir hilft, Mimis Puppe zu reparieren. In Eisenküste wirst du niemanden finden*


Der Spieler trifft in Kaltenstrom (oder vorher?) auf jemand, der Reparatuarbeiten aller Art macht und kann Stoff, Leder und Wolle kaufen  - oder fertigen Puppenkörper? 
Der Spieler trifft Mimi wieder in Kaltenstrom. 

## NPCS

### Mimi

Mimi ist ein Kind, das im Alter von ca 3 Jahren auf der Insel Ankanor in einem kleinen Boot angespült wurde, das eigentlich nicht seetauglich war. Sie besaß nichts außer zerissene Kleidung, eine Puppe (Aneli), ein Amulet um den Hals und etwas Verpflegung. Mairi nahm sie in ihre Familie auf.

Mimi ist inzwischen ein hübsches, rothaariges Mädchen mit einem rundlichen Gesicht und grünen Augen. Meist kleben einige Krümel in ihrem Gesicht, da sie trotz Mairies Bemühungen, sie gesund zu ernähren, von Kiakeksen zu leben scheint. Sie ist vom vielen Spielen im Freien braungebrannt und liebt es, sich bunte Blumen ins Haar zu flechten.

Gerne trägt sie grüne oder blaue Kleidchen, Schuhe jedoch mag sie nicht, da sie hinderlich beim Klettern im Tianbaum sind. Sie ist für ihr Alter von 10 Jahren ziemlich klein und erscheint manchen viel jünger als sie wirklich ist.  


#### Standartsätze

##### Vor der Quest:

*Mimi weint und will mit niemanden sprechen*

##### Während der Quest:

-

##### Nach der Quest: 

Mimi: Hast du vielleicht schon Zeug zum Flicken meiner Puppe?

Spieler: 
1. Woher soll ich denn hier etwas bekommen? Ein Schimmerwolffell wirst du nicht haben wollen. 
2. Spieler: Mimi, nein, aber ich verspreche dir, ich vergesse dich nicht.
3. Jetzt nerve mich nicht, ich hatte jetzt doch noch keine Gelegenheit.


#### Ausrüstung

Eisenküsteskin
https://faldoria.de/board/thread/528-skins-f%C3%BCr-npcs/?postID=4053#post4053

Hält Puppe in der Hand (Totem der Unsterblichkeit?)

#### Standort   

```yml
x: 
y: 
z: 
world: faldoria.eisenküste
```

## Referenzen

Damit zusammenhängende Quest

[Mimi braucht dich](#mimi-braucht-dich)



