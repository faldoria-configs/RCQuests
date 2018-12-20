# Abschied von Ariani

Issue #61

Die Quest beginnt bei NPC [Yoshni](#yoshni), die neben Bürgermeister [Roschik](#roschik) steht.

## Was noch fehlt:

Das Buch!

## Übersicht 

- [Abschied von Ariani](#abschied-von-ariani)
  - [Was noch fehlt:](#was-noch-fehlt)
  - [Übersicht](#%C3%BCbersicht)
  - [Ablauf](#ablauf)
  - [Voraussetzungen](#voraussetzungen)
  - [Questdialoge](#questdialoge)
    - [Dialog 1](#dialog-1)
    - [Dialog 2](#dialog-2)
  - [NPCS](#npcs)
    - [Ariani](#ariani)
      - [Standartsätze](#standarts%C3%A4tze)
      - [Ausrüstung](#ausr%C3%BCstung)
      - [Standort](#standort)
  - [Items](#items)
    - [Name des Items](#name-des-items)

## Ablauf

1. Die Spielerin steht bei Roschik, um ihre Quest [HQ Vorräte für das Schiff](../2-vorraete-fuer-das-schiff/README.md) abzugeben.
2. Sobald sie die nächste Quest, [Aufstieg zum Tianbaum](../3-aufstieg-zum-tianbaum/README.md) angenommen hat, spricht Yoshni sie an.
3. Yoshni bittet sie, nach ihrer Urgroßmutter, der alten Ariani zu sehen, die am Aussichtspunkt ist.
4. Die Spielerin findet sie und redet mit ihr.
5. Ariani schickt sie weg, um das Tagebuch ihrer Ur-Urgroßmutter zu finden und zu retten. 

## Voraussetzungen

Erledigen der [HQ Vorräte für das Schiff](../2-vorraete-fuer-das-schiff/README.md)
Annahme der Quest: [Aufstieg zum Tianbaum](../3-aufstieg-zum-tianbaum/README.md)

> Sobald die Spielerin die Quest angenommen hat, nach folgender Zeile:

> > 1. Spieler/in: Wie ihr wollt, ich werde zur Krone des Baumes hinauf steigen.. `[QUEST START]` [Aufstieg zum Tianbaum](#aufstieg-zum-tianbaum)  
**Questlog**: *Folge den Weg um den Tianbaum herum auf die andere Seite, triff den Wächter des Heiligtums und steige den Tianbaum hinauf. **Dort wird dir Lious weiterhelfen** *

spricht Yoshni die Spielerin an! 

## Questdialoge

### Dialog 1

```yml
Yoshni: <Name der Spielerin>, wart mal kurz. 
```

> Fortsetzung des Dialogs, wenn die Spielerin stehen bleibt

```yml
*Yoshni wendet sich zu Roschik*
Yoshni: Ich weiß, dass es eilig und wichtig ist, dass <Name der Spielerin> zum Tianbaum hinaufsteigt, aber ich mache mir Sorgen um Ariani. Könnte <Name der Spielerin> sie nicht vorher suchen, sie braucht doch länger als wir, bis sie zum Schiff kommt und sie ist schießlich ihre Urgroßmutter. 
Roschik: Von mir aus, vielleicht kann <Name der Spielerin> sie ja nebenbei suchen, ihr Haus liegt ja am Weg. 
Yoshni: Ja, aber ich glaube, ich habe sie beim Aussichtsplatz oben auf der Klippe gesehen, vielleicht schaust du da erst nach, <Name der Spielerin>.
```
**Spieler:**

> 1. Ich suche Großmutter später, ich möchte erst zum Tianbaum hinauf. 

Fortsetzung der Quest: [Aufstieg zum Tianbaum](../3-aufstieg-zum-tianbaum/README.md)

 

>> Wenn die Spielerin später wiederkommt, nach dem Abschluß anderer Quests, aber bevor sie das letzte Mal zu Jamos geht und das Event anfängt:

NQ [Abschied von Ariani](#abschied-von-ariani)

1.1.1
```yml
Yoshni: Hast du jetzt Zeit, nach Ariani zu suchen?
Spieler/in: Nein, ich bin immer noch beschäftigt.
Yoshni: Na, dann muss ich es wohl selber machen, schade, dass du so wenig für deine Großmutter übrig hast.
``` 
Wenn die Spielerin erneut wiederkommt und erneut ablehnt:

1.1.2
```yml
 Spieler/in: Es geht jetzt wirklich nicht, wenn dieser Ananani unterwegs ist, Großmutter schafft das schon alleine.

Yoshni: *kalt* Wie du meinst.
```

`[Ende]`

>>> Spieler/in kann die Quest hinterher nicht mehr annehmen!!!

1.2

```yml
Spieler/in: Nagut, ich geh ja schon und suche sie. 
```

>**Weiter wie mit Antwort 2.** 


**Spieler/in:**

> 2. Ja, ich hole sie gleich, sie wird nicht weg wollen, wie ich sie kenne!

`[QUESTSTART]`[Abschied von Amari](#abschied-von-amari)

**Questlog**  *Finde deine Urgroßmutter Ariani und rede mit ihr.*

Die Spielerin läuft zum Aussichtspunkt und findet dort Ariani, sie fängt ein Gespräch an. 

### Dialog 2

Sobald die Spielerin oben auf dem Aussichtpunkt ist, etwas 10 Blocks entfernt von Ariani.

*Du siehst deine Urgroßmutter Ariani auf der Bank sitzen, sie schaut auf den Tianbaum*

```yml
Spieler/in: Ariani, warum sitzt du hier rum und machst dich nicht fertig, warum bist du noch nicht auf dem Schiff? Soll ich dir helfen, dorthin zu kommen?
Ariani: Nein, <Name des Spielers>, ich bleibe da, ich gehe nicht auf das Schiff.
Spieler/in: Aber Agmanus Schergen kommen doch, du musst weg, sonst wirst du sterben.
Ariani: Ich bin alt, ich fürchte mich nicht vor dem Tod. Ich glaube kaum, dass ich die Schiffsreise überleben würde. Und noch weniger die Strapazen eines Lebens in einem fremden Land.
Spieler/in: Aber... wir können dich doch nicht einfach zurücklassen.
Ariani: Doch, doch, schau, ich genieße die letzten Stunden hier auf dem Aussichtspunkt und dann gehe ich ein letztes Mal hinauf in den Tianbaum. Ich habe mein ganzes, langes Leben hier verbracht, ich will auch hier sterben.
Spieler/in: Aber...
```

> 1. *Du bist ganz verstört und weißt nicht, was du tun sollst, die Tränen stehen dir in den Augen*

> 2. Spieler/in: *Du schüttelsts energisch den Kopf.* Nein, Großmutter, das geht gar nicht, du musst mitkommen. Und wenn du nicht willst, trage ich dich dich zum Schiff. 
 
```yml
Ariani: Komm her zu mir, setz dich neben mich.
*Du setzt dich neben deine Urgroßmutter, sie nimmt deine Hand*
Ariani: <Name der Spielerin>, sei nicht traurig wegen mir. Ich bin alt und habe ein glückliches Leben geführt. Und nun ist meine Zeit gekommen, zu gehen. Aber ihr Jungen, ihr müsst fliehen, denn Agnatus ist zu böse und stark, als dass ihr ihm hier widerstehen könntet. 
Ariani: Aber ich bin fest davon überzeugt, dass ihr jüngeren Kaishi das Unglück, die erneute Flucht gut überleben werdet. Wir sind hier mit dem Segen des Tianbaumes in den letzten vierhundert Jahren ein starkes Volk geworden, auch wenn wir friedlich sind. Das heißt nicht, dass wir uns nicht zu wehren wissen. Aber manchmal heißt klug zu sein, auszuweichen, auch wenn andere Völker das als feige Flucht bezeichnen würden. Glaube das nicht! Und nun geh. Der Segen des Tianbaumes sei mit dir. 

*Ariani streicht dir mit ihren knochigen Fingern über das Haar*
```

> 1. Spieler: Aber Großmutter.. *deine Worte ersticken in deinem Schluchzen*

> 2. Spieler: Aber Großmutter, ich kann dich hier nicht zurücklassen! 

```yml
Ariani: Kein 'Aber', <Name des Spielers>, doch du könntest mir noch einen Gefallen tun. In meinem Haus - du weißt doch, wo ich jetzt wohne - gleich links hoch nach dem Aufgang zu Mairis und Roschiks Haus, da liegt das Tagebuch meiner Ur-Urgroßmutter Miruni. Sie lebte noch auf [Name des Kontinents] und hat die letzten Tage beschrieben, bis sie weggezogen sind, dann die Seereise und die Ankunft hier auf Ankanor vor 400 Jahren. Es wäre schade, wenn das Tagebuch den Kaishi verloren gehen würde. Hole es und nimm es mit, für dich und deine Kinder. Und dann lebe wohl!

*Ariani steht auf schiebt dich sanft Richtung Versammlunshalle*
Spieler/in: *Du umarmst deine Großmutter das letzte Mal fest und rennst weg. Unten angekommen schaust du zurück und siehst sie fröhlich winken. Dieses Bild wird dir ewig in Erinnerung bleiben*
```

`[Ende]` [Abschied von Ariani](#abschied-von-ariani)

**Belohnung** XP

`[QUESTSTART]` [Mirunis Tagebuch](#mirunis-tagebuch)

**Questlog** *Finde Mirunis Tagebuch und nimm es an dich.*

Die Spielerin sucht Mirunis Tagebuch, schließt damit die Quest ab. 

`[Ende]`

**Belohnung** XP

> Es erscheint im Chat:

>>> Du hast dein erstes Buch gefunden

Und er erhält das **Achievement: "Ein Buch gefunden"**   (oder auch was anderes)

Er erhält sofort die nächste Quest: 

`[QUESTSTART]` [Rette Mirunis Buch](#rette-mirunis-buch)

**Questlog**  *Nimm Mirunis Tagebuch an dich und bewahre es sicher auf, bis du einen Ort gefunden hast, an dem es gut aufgehoben ist.*

> Die Quest kann erst irgendwo auf Faldoria, Kaltenstrom oder wo auch immer abgeschlossen werden. 

Spieler/in sucht und findet das Buch und erledigt dann weitere Quests. 


## NPCS

### Ariani

Ariani ist mit ihren 144 Jahren die älteste Frau, die auf Ankanor lebt und die Urgroßmutter der Spielerin. Eine ihrer direkten Vorfahren beschreibt in ihrem Tagebuch die Suche nach dem Baum der Bindung, dem Tianbaum, der die Insel Ankanor bedeckt.

#### Standartsätze

    ##### Vor der Quest:

Stör mich bitte nicht, <Name der Spielerin>, ich genieße hier die Aussicht.

    ##### Während den Quests:
     [Abschied von Amari](#abschied-von-amari)
     Bei Abbruch der Quest Questtext ab [Dialog 2](#dialog-2) wieder neu starten.




    ##### Nach der Quest:
    Ariani: Geh, geh und eile zum Schiff, oder erledige was du noch tun musst!






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










