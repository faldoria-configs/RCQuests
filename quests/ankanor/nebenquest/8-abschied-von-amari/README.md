# Abschied von Amari

Issue #61

Die Quest beginnt bei NPC [Yoshni](#yoshni), die neben Bürgermeister [Roschik](#roschik) steht.

## Was noch fehlt:

Das Buch!

## Übersicht 

- [Abschied von Amari](#abschied-von-amari)
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
3. Sie bittet ihn, nach seiner Urgroßmutter, der alten Amari zu sehen, die am Aussichtspunkt ist.
4. Der Spieler findet sie und redet mit ihr.
5. Amari schickt ihn weg, um das Tagebuch ihrer Ur-Urgroßmutter zu finden und zu retten. 

## Voraussetzungen

Erledigen der [HQ Vorräte für das Schiff](../2-vorraete-fuer-das-schiff/README.md)
Annahme der Quest: [Aufstieg zum Tianbaum](../3-aufstieg-zum-tianbaum/README.md)

> Sobald der spieler die Quest angenommen hat, nach folgender Zeile:

> > 1. Spieler: Wie ihr wollt, ich werde zur Krone des Baumes hinauf steigen.. `[QUEST START]` [Aufstieg zum Tianbaum](#aufstieg-zum-tianbaum)  
**Questlog**: *Folge den Weg um den Tianbaum herum auf die andere Seite, triff den Wächter des Heiligtums und steige den Tianbaum hinauf und wähle deinen Pfad des Kampfes.*

spricht Yoshni den Spieler an! 

## Questdialoge

### Dialog 1

```yml
Yoshni: <Name des Spielers>, wart mal kurz. 
```

> Fortsetzung des Dialogs, wenn der spieler stehen bleibt

```yml
*Yoshni wendet sich zu Roschik*
Yoshni: Ich weiß, dass es eilig und wichtig ist, dass <Name des Spielers> zum Tianbaum hinaufsteigt, aber ich mache mir Sorgen um Amari. Könnte er sie nicht vorher suchen, sie braucht doch länger als wir, bis sie zum Schiff kommt und sie ist schießlich seine Urgroßmutter. 
Roschik: Von mir aus, vielleicht kann <Name des Spielers> sie ja nebenbei suchen, ihr Haus liegt ja am Weg. 
Yoshni: Ja, aber ich glaube, ich habe sie beim Aussichtsplatz oben auf der Klippe gesehen, vielleicht schaust du da erst nach, <Name des Spielers>.
```
**Spieler:**

> 1. Ich suche Großmutter später, ich möchte erst zum Tianbaum hinauf.  `[Ende]`

Fortsetzung der Quest: [Aufstieg zum Tianbaum](../3-aufstieg-zum-tianbaum/README.md)

 

>> Wenn der Spieler später wiederkommt, nach dem Abschluß anderer Quests, aber bevor er zu Jamos geht:

> Fortsetzung Quest [Abschied von Amari](#abschied-von-amari)

```yml
Yoshni: Hast du jetzt Zeit, nach Amari zu suchen?
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

**Questlog**  *Finde deine Urgroßmutter Amari und rede mit ihr.*

Der Spieler läuft zum Aussichtspunkt und findet dort Amari, er fängt ein Gespräch an. 

### Dialog 2



