# Abschied von Ariani

Issue #61

Die Quest beginnt bei NPC [Yoshni](#yoshni), die neben Bürgermeister [Roschik](#roschik) steht.

## Was noch fehlt:

Das Buch! Ist in Arbeit.

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
        - [Während den Quests:](#w%C3%A4hrend-den-quests)
        - [Nach der Quest:](#nach-der-quest)
      - [Ausrüstung](#ausr%C3%BCstung)
      - [Standort](#standort)
    - [Yoshni](#yoshni)
      - [Standort](#standort-1)
    - [Roschik](#roschik)
      - [Standort](#standort-2)
  - [Items](#items)
    - [Mirunis Tagebuch](#mirunis-tagebuch)
      - [Standort](#standort-3)
  - [Referenzen](#referenzen)

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
Yoshni: Ich weiß, dass es eilig und wichtig ist, dass <Name der Spielerin> zum Tianbaum hinaufsteigt, aber ich mache mir Sorgen um Ariani. Könnte <Name der Spielerin> Ariani nicht vorher suchen, sie braucht doch länger als wir, bis sie zum Schiff kommt und sie ist schießlich <Name der Spielerin>s Urgroßmutter. 
Roschik: Von mir aus, vielleicht kann <Name der Spielerin> sie ja nebenbei suchen, ihr Haus liegt ja am Weg. 
Yoshni: Ja, aber ich glaube, ich habe Ariani beim Aussichtsplatz oben auf der Klippe gesehen, vielleicht schaust du da erst nach, <Name der Spielerin>.
```
**Spielerin:**

> 1. Ich suche Großmutter später, ich möchte erst zum Tianbaum hinauf. `[Ende]`

Fortsetzung der Quest: [Aufstieg zum Tianbaum](../3-aufstieg-zum-tianbaum/README.md)

 
>> Wenn die Spielerin später wiederkommt, nach dem Abschluß anderer Quests, aber bevor sie das letzte Mal zu Jamos geht und das Event anfängt:

NQ [Abschied von Ariani](#abschied-von-ariani)

1.1
```yml
Yoshni: Hast du jetzt Zeit, nach Ariani zu suchen?
SpielerIn: Nein, ich bin immer noch beschäftigt.
Yoshni: Na, dann muss ich es wohl selber machen, schade, dass du so wenig für deine Großmutter übrig hast.
SpielerIn: Nagut, ich geh ja schon und suche sie. 
```
> **Weiter wie mit Antwort 2.** 
 
1.2
```yml
SpielerIn: Es geht jetzt wirklich nicht, wenn dieser Ananani unterwegs ist, Großmutter schafft das schon alleine.

Yoshni: *kalt* Wie du meinst.
```

`[Ende]`

>>> SpielerIn kann die Quest hinterher nicht mehr annehmen!!!


**SpielerIn:**

> 2. Ja, ich hole sie gleich, sie wird nicht weg wollen, wie ich sie kenne!

`[QUESTSTART]`[Abschied von Amari](#abschied-von-amari)

**Questlog**  *Finde deine Urgroßmutter Ariani und rede mit ihr.*

Die Spielerin läuft zum Aussichtspunkt und findet dort Ariani, sie fängt ein Gespräch an. 

### Dialog 2

Sobald die Spielerin oben auf dem Aussichtpunkt ist, etwas 10 Blocks entfernt von Ariani.

*Du siehst deine Urgroßmutter Ariani auf der Bank sitzen, sie schaut auf den Tianbaum*

```yml
SpielerIn: Ariani, warum sitzt du hier rum und machst dich nicht fertig, warum bist du noch nicht auf dem Schiff? Soll ich dir helfen, dorthin zu kommen?
Ariani: Nein, <Name der Spielerin>, ich bleibe da, ich gehe nicht auf das Schiff.
SpielerIn: Aber Agmanus Schergen kommen doch, du musst weg, sonst wirst du sterben.
Ariani: Ich bin alt, ich fürchte mich nicht vor dem Tod. Ich glaube kaum, dass ich die Schiffsreise überleben würde. Und noch weniger die Strapazen eines Lebens in einem fremden Land.
SpielerIn: Aber... wir können dich doch nicht einfach zurücklassen.
Ariani: Doch, doch, schau, ich genieße die letzten Stunden hier auf dem Aussichtspunkt und dann gehe ich ein letztes Mal hinauf in den Tianbaum. Ich habe mein ganzes, langes Leben hier verbracht, ich will auch hier sterben.
SpielerIn: Aber...
```

> 1. *Du bist ganz verstört und weißt nicht, was du tun sollst, die Tränen stehen dir in den Augen*

> 2. SpielerIn: *Du schüttelsts energisch den Kopf.* Nein, Großmutter, das geht gar nicht, du musst mitkommen. Und wenn du nicht willst, trage ich dich zum Schiff. 
 
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
Ariani: Kein 'Aber', <Name der Spielerin>, doch du könntest mir noch einen Gefallen tun. In meinem Haus - du weißt doch, wo ich jetzt wohne - in dem Haus nach dem Aufgang zu Mairis und Roschiks Haus,  gleich links hoch, da liegt das Tagebuch meiner Ur-Urgroßmutter Miruni. Sie lebte noch auf [Name des Kontinents] und hat die letzten Tage beschrieben, bis sie weggezogen sind, dann die Seereise und die Ankunft hier auf Ankanor vor 400 Jahren. Es wäre schade, wenn das Tagebuch den Kaishi verloren gehen würde. Hole es und nimm es mit, für dich und deine Kinder. Und dann lebe wohl!

*Ariani steht auf schiebt dich sanft Richtung Versammlungshalle*
SpielerIn: *Du umarmst deine Großmutter das letzte Mal fest und rennst weg. Unten angekommen schaust du zurück und siehst sie fröhlich winken. Dieses Bild wird dir ewig in Erinnerung bleiben*
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

Und die Spielerin erhält das **Achievement: "Ein Buch gefunden"**   (oder auch was anderes)

Sie erhält sofort die nächste Quest: 

`[QUESTSTART]` [Rette Mirunis Buch](#rette-mirunis-buch)

**Questlog**  *Nimm Mirunis Tagebuch an dich und bewahre es sicher auf, bis du einen Ort gefunden hast, an dem es gut aufgehoben ist.*

> Die Quest kann erst irgendwo auf Faldoria, Kaltenstrom oder wo auch immer abgeschlossen werden. 

SpielerIn sucht und findet das Buch und erledigt dann weitere Quests. 


## NPCS

### Ariani

Ariani ist mit ihren 144 Jahren die älteste Frau, die auf Ankanor lebt und die Urgroßmutter der Spielerin. Eine ihrer direkten Vorfahren beschreibt in ihrem Tagebuch die Suche nach dem Baum der Bindung, dem Tianbaum, der die Insel Ankanor bedeckt.

#### Standartsätze

    ##### Vor der Quest:

Stör mich bitte nicht, <Name der Spielerin>, ich genieße hier die Aussicht.

##### Während den Quests:

[Abschied von Amari](#abschied-von-amari)

    Bei Abbruch der Quest mittendrin Questtext ab [Dialog 2](#dialog-2) wieder neu starten.

[Mirunis Tagebuch](#mirunis-tagebuch)

    Ariani: Warum bist du noch da, Enkelkind?

    SpielerIn: Ich finde das Buch nicht, kannst du mir den Weg nochmals beschreiben?

    Ariani: Geh in die Richtung des Schiffes. Geh an dem Faulenzer Schicho vorbei, wende dich nach rechts. Auf der lonken Seite kommt ein haus, geh dran vorbei und dann links hoch, dort ist der Eingang. In der einzelnen Kiste hinten am Fesnter müsste das Buch sein.

##### Nach der Quest:

> [Rette Mirunis Buch](#rette-mirunis-buch) ist noch offen

1. Ariani: Geh, geh und eile zum Schiff, oder erledige was du noch tun musst!


2. Ariani: Lauf zum Schiff, Kind, lauf!

#### Ausrüstung

Arianis weiße Haare sind zu einem langen Zopf geflochten, der den Rücken hinabhängt. Ein grünes Umhängetuch schützt Ariani sie vor Kälte, ihr brauner Rock ist bunt bestickt, die Bluse weiß.

Skin: http://lh3.googleusercontent.com/3F1bjixpzhuGUU1E2EX8TxNAPOI6mwYEV4PLwxn3Ks3-l8KFhFwFkvIfurDG14QMz0yQ3uhnWuYnFLCbTSKgOQ

https://faldoria.de/board/index.php?thread/528-skins-f%C3%BCr-npcs/&postID=3866#post3866

#### Standort   

```yml
x: 118
y: 105
z: -104
world: ankanor
```

### Yoshni

Steht neben Roschik in der Versammlungshalle

#### Standort

name: Yoshni
type: NPC
health: 100
attackable: false
friendly: true
disguise: Yoshni
location:
  world: ankanor
  x: 101
  y: 83
  z: -82
default-conv: this.yoshni.default
talk-close: false

>> Stimmt das?

### Roschik

Er ist der Bürgermeister des Dorfes in dem die Kaishi wohnen. Roschik ist ein sehr gütiger Kaishi und wird von allen Respektiert.

siehe Hauptquests Ankanor

#### Standort

```yml
x: 100
y: 82
z: -85
world: Ankanor
```


## Items

### Mirunis Tagebuch

```yml
ID: 
name: Mirunis Tagebuch
type: QUEST 
quality: einzigartig
item: written_book ??
lore: Ein sehr wertvolles Buch der Kaishi
max-stack-size: 1
```
#### Standort   

```yml
x: 1
y: 85
z: -43
world: ankanor
```

## Referenzen











