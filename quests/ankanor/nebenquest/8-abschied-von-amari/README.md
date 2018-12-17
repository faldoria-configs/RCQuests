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

## Ablauf

1. Der Spieler steht bei Roschik, um seine Quest [HQ Vorräte für das Schiff](../2-vorraete-fuer-das-schiff/README.md) abzugeben.
2. Sobald er die nächste Quest, [Aufstieg zum Tianbaum](../3-aufstieg-zum-tianbaum/README.md) angenommen hat, spricht Yoshni ihn an.
3. Sie bittet ihn, nach seiner Urgroßmutter, der alten Ariani zu sehen, die am Aussichtspunkt ist.
4. Der Spieler findet sie und redet mit ihr.
5. Ariani schickt ihn weg, um das Tagebuch ihrer Ur-Urgroßmutter zu finden und zu retten. 

## Voraussetzungen

Erledigen der [HQ Vorräte für das Schiff](../2-vorraete-fuer-das-schiff/README.md)
Annahme der Quest: [Aufstieg zum Tianbaum](../3-aufstieg-zum-tianbaum/README.md)

> Sobald der Spieler die Quest angenommen hat, nach folgender Zeile:

> > 1. Spieler: Wie ihr wollt, ich werde zur Krone des Baumes hinauf steigen.. `[QUEST START]` [Aufstieg zum Tianbaum](#aufstieg-zum-tianbaum)  
**Questlog**: *Folge den Weg um den Tianbaum herum auf die andere Seite, triff den Wächter des Heiligtums und steige den Tianbaum hinauf und wähle deinen Pfad des Kampfes.*

spricht Yoshni den Spieler an! 

## Questdialoge

### Dialog 1

```yml
Yoshni: <Name des Spielers>, wart mal kurz. 
```

> Fortsetzung des Dialogs, wenn der Spieler stehen bleibt

```yml
*Yoshni wendet sich zu Roschik*
Yoshni: Ich weiß, dass es eilig und wichtig ist, dass <Name des Spielers> zum Tianbaum hinaufsteigt, aber ich mache mir Sorgen um Ariani. Könnte er sie nicht vorher suchen, sie braucht doch länger als wir, bis sie zum Schiff kommt und sie ist schießlich seine Urgroßmutter. 
Roschik: Von mir aus, vielleicht kann <Name des Spielers> sie ja nebenbei suchen, ihr Haus liegt ja am Weg. 
Yoshni: Ja, aber ich glaube, ich habe sie beim Aussichtsplatz oben auf der Klippe gesehen, vielleicht schaust du da erst nach, <Name des Spielers>.
```
**Spieler:**

> 1. Ich suche Großmutter später, ich möchte erst zum Tianbaum hinauf.  `[Ende]`

Fortsetzung der Quest: [Aufstieg zum Tianbaum](../3-aufstieg-zum-tianbaum/README.md)

 

>> Wenn der Spieler später wiederkommt, nach dem Abschluß anderer Quests, aber bevor er zu Jamos geht:

> Fortsetzung Quest [Abschied von Ariani](#abschied-von-ariani)

```yml
Yoshni: Hast du jetzt Zeit, nach Ariani zu suchen?
Spieler: Nein, ich bin immer noch beschäftigt.
Yoshni: Na, dann muss ich es wohl selber machen, schade, dass du so wenig für deine Großmutter übrig hast.
``` 


1.1
```yml
 Spieler: Es geht jetzt wirklich nicht, wenn dieser Ananani unterwegs ist, Großmutter schafft das schon alleine.

Yoshni: *kalt* Wie du meinst.
```

`[Ende]`

>>> Spieler kann die Quest hinterher nicht mehr annehmen!!!

1.2

```yml
Spieler: Nagut, ich geh ja schon und suche sie. 
```

>**Weiter wie mit Antwort 2.** 


**Spieler:**

> 2. Ja, ich hole sie gleich, sie wird nicht weg wollen, wie ich sie kenne!

`[QUESTSTART]`[Abschied von Amari](#abschied-von-amari)

**Questlog**  *Finde deine Urgroßmutter Ariani und rede mit ihr.*

Der Spieler läuft zum Aussichtspunkt und findet dort Ariani, er fängt ein Gespräch an. 

### Dialog 2

Sobald der Spieler oben auf dem Aussichtpunkt ist, etwas 10 Blocks entfernt von Ariani.

*Du siehst deine Urgroßmutter Ariani auf der Bank sitzen, sie schaut auf den Tianbaum*

```yml
Spieler: Ariani, warum sitzt du hier rum und machst dich nicht fertig, warum bist du noch nicht auf dem Schiff? Soll ich dir helfen, dorthin zu kommen?
Ariani: Nein, <Name des Spielers>, ich bleibe da, ich gehe nicht auf das Schiff.
Spieler: Aber Agmanus Schergen kommen doch, du musst weg, sonst wirst du sterben.
Ariani: Ich bin alt, ich fürchte mich nicht vor dem Tod. Ich glaube kaum, dass ich die Schiffsreise überleben würde. Und noch weniger die Strapazen eines Lebens in einem fremden Land.
Spieler: Aber... wir können dich doch nicht einfach zurücklassen.
Ariani: Doch, doch, schau, ich genieße die letzten Stunden hier auf dem Aussichtspunkt und dann gehe ich ein letztes Mal hinauf in den Tianbaum. Ich habe mein ganzes, langes Leben hier verbracht, ich will auch hier sterben.
Spieler: Aber...

*Du bist ganz verstört und weißt nicht, was du tun sollst, die Tränen stehen dir in den Augen*
Ariani: Komm her zu mir, setz dich neben mich.

*Du setzt dich neben deine Urgroßmutter, sie nimmt deine Hand*
Ariani: <Name des Spielers>, sei nicht traurig wegen mir. Ich bin alt und habe ein glückliches Leben geführt. Und nun ist meine Zeit gekommen, zu gehen. Aber ihr Jungen, ihr müsst fliehen, denn Agnatus ist zu böse und stark, als dass ihr ihm hier wiederstehen könntet. 
Ariani: Aber ich bin fest davon überzeugt, dass ihr jüngeren Kaishi das Unglück, die erneute Flucht gut überleben werdet. Wir sind hier mit dem Segen des Tianbaumes in den letzten vierhundert Jahren ein starkes Volk geworden, auch wenn wir friedlich sind. Das heißt nicht, dass wir uns nicht zu wehren wissen. Aber manchmal heißt klug zu sein, auszuweichen, auch wenn andere Völker das als feige Flucht bezeichnen würden. Glaube das nicht! Und nun geh. Der Segen des Tianbaumes sei mit dir. 

*Ariani streicht dir mit ihren knochigen Fingern über das Haar*
Spieler: Aber Großmutter.. *deine Worte ersticken in deinem Schluchzen*
Ariani: Kein 'Aber', <Name des Spielers>, doch du könntest mir noch einen Gefallen tun. In meinem Haus - du weißt doch, wo ich jetzt wohne - gleich links hoch nach dem Aufgang zu Mairis und Roschiks Haus, da liegt das Tagebuch meiner Ur-Urgroßmutter Miruni. Sie lebte noch auf [Name des Kontinents] und hat die letzten Tage beschrieben, bis sie weggezogen sind, dann die Seereise und die Ankunft hier auf Ankanor vor 400 Jahren. Es wäre schade, wenn das Tagebuch den Kaishi verloren gehen würde. Hole es und nimm es mit, für dich und deine Kinder. Und dann lebe wohl!

*Ariani steht auf schiebt dich sanft Richtung Versammlunshalle*
Spieler: *Du umarmst deine Großmutter das letzte Mal fest und rennst weg. Unten angekommen schaust du zurück und siehst sie fröhlich winken. Dieses Bild wird dir ewig in Erinnerung bleiben*
```

`[Ende]` [Abschied von Ariani](#abschied-von-ariani)

`[QUESTSTART]` [Mirunis Tagebuch](#mirunis-tagebuch)

**Questlog** *Finde Mirunis Tagebuch und nimm es an dich.*

Der Spieler sucht Mirunis Tagebuch, schließt damit die Quest ab 

`[Ende]`

> Es erscheint im Chat:

>>> Du hast dein erstes Buch gefunden

Und er erhält das **Achievement: "Ein Buch gefunden"**   (oder auch was anderes)

Er erhält sofort die nächste Quest: 

`[QUESTSTART]` [Rette Mirunis Buch](#rette-mirunis-buch)

**Questlog**  *Nimm Mirunis Tagebuch an dich und bewahre es sicher auf, bis du einen Ort gefunden hast, an dem es gut aufgehoben ist.*

> Die Quest kann erst irgendwo auf Faldoria, Kaltenstrom oder wo auch immer abgeschlossen werden. 














