# Der verlorene Jäger

> Achtung - verwoben mit Quest: Seltene Pelze
1. Der Spieler trifft als Erstes auf Kalbert, dann erst auf Svein - Quest Der verlorenen Jäger. Während der Quest kann die Quest: Seltene Pelze angenommen werden. 



> Vorschlag: ein anderer NPC, vlltch Marduk, fragt, on der Spieler Kalbert oder Svein gesehen hat. Ohne , nur um den spieler darauf hinzuweisen, dass es da noch jemanden gibt. 

>  Kalbert (Vater), Svein (Sohn)

## Veränderungen

Etwas erweitert, der Sohn Svein ist jetzt nicht nur verloren gegangen, sondern hat Angst, die Erwartungen des Vaters nicht zu erfüllen. 

## Ablauf

Der Spieler trifft erst aud Kalbert, dann auf den Sohn Svein


## Questdialoge

Der Spieler trifft (mehr oder weniger) zufällig auf Kalbert (den er noch nicht kennt). Er sieht ihn stehen, wenn der Spieler sich Kalbert auf 5 Block genähert hat, hört er ihn murmeln.
```yml
Kalbert: Hmmm… Wo ist er nur hin?
Spieler: Von wem redet ihr?
Kalbert: Großer Tianbaum! Erschreck mich doch nicht so!
Spieler: Tut mit Leid. Also, wen sucht Ihr?
Kalbert: Meinen Sohn Svein. Wir waren zusammen auf der Jagd. Hier gibt es ausgesprochen seltene Pelze, wisst ihr? Besonders die Eisen Bergkatzen haben es mir angetan. Wir trennten uns, damit Svein sein Geschick beweisen kann, aber er sollte schon längst zurück sein. Wir wollten uns hier wieder treffen. 
Spieler: Und was nun?
NPC: Könntet ihr vielleicht nach meinem Sohn schauen? Ich warte hier auf ihn, wenn ich weggehe und er kommt zurück, dann verpassen wir uns erst recht.
````
> 1. Spieler: Ich habe grade keine Zeit, tut mir leid. Ich hoffe, er kommt bald! ```[Ende]```

> 2. Spieler. Ich sehe, was ich tun kann. In welche Richtung ist er denn gegangen? Und wer seid Ihr, wenn ich fragen darf?
     Kalbert: Kalbert heiß ich. Und Svein ist nach Norden gegangen, da hinter. *deutet mir dem Arm zur Bergwand*

`[QUESTSTART]`[Der verlorene Jäger](#der-verlorene-jaeger)

> **QuestLog:** *Suche nach Svein, der irgendwo nördlich von Kalbert sein muss.*

Der Spieler findet nach etwas Suchen [Svein](#svein).


Der Spieler nähert sich Svein, der ihn bemerkt und anspricht (5 Blöcke):
```yml
*Du siehst eine jungen Mann, der in dicke Felle gehüllt ist und sich gedankenverloren auf einen Bogen stützt. Er schaut auf, als du dich ihm näherst* 

Svein: Hallo, habt Ihr vielleicht meinen Vater getroffen?
Spieler: Seid Ihr Svein? Euer Vater sucht Euch! Was ist denn passiert?
Svein: Nun, nichts eigentlich.
Spieler: Eigentlich?
Svein: Naja, mein Vater und ich haben uns getrennt, da er sagte, ich muss jetzt endlich mal mein Geschick auf der Jagd beweisen und soll ihm Felle der Eisen Bergkatze bringen. Ich habe es ja auch versucht, aber..
Spieler: Aber?
Svein: Ich kann gut schießen! Sehr gut! Aber keine Eisen Bergkatzen, auch keine Schimmerwölfe, ich finde sie viel zu schön... ich mag ihre Pelze auch nicht tragen..
Spieler: Da hast du ein Problem. Und was willst du nun tun?
*Sven schaut bittend zu dir hin*
Svein: Du könntest die Bergkatzen und Schimmerwölfe für mich töten und die Pelze besorgen? Das ist zwar auch nicht viel besser, aber - ich bring's nicht über's Herz und ohne traue ich mich nicht zu meinem Vater zurück. Ich belohne dich auch dafür!
```

> 1. Spieler: Nein, diese Aufgabe kann ich dir nicht abnehmen. Da musst du durch. Entweder töte sie, oder gestehe deinem Vater, dass du es nicht tun kannst.
```yml
     Svein: Würdest du mich zu meinem Vater begleiten? Dann fällt es mir vielleicht leichter, mit ihm darüber zu sprechen. 
         1.1 Spieler: Nein, da musst du alleine durch. Ich gehe jetzt zu deinem Vater zurück und sage ihm, dass ich dich gefunden habe und du bald kommst. `[Ende]`
         1.2 Ja, komm, wir gehen zusammen hin. 
         
```

**Weiter mit 1.1:**

Spieler geht alleine zu Kalbert und berichtet:
```yml
Spieler: Ich habe eueren Sohn gefunden!
Kalbert: Wirklich? Großartig! Wo ist er?
Spieler: Er befindet sich im Norden, gar nicht weit von hier.
Kalbert: Hat er sich wieder verlaufen? Ich hab ihm gesagt, er soll bei mir bleiben!
Spieler: Nein, das war nicht die Ursache, aber kommt bald und will mit ech reden.
Kalbert: Mit mir reden? Na sowas. 
*Kalbert kratzt sich verdutzt am Kopf, wirkt wie in Gedanken*
Kalbert: Hier ist eine Kleine Belohnung für eure Mühen.
Spieler: Habt Dank! Und viel Glück bei der Jagd - und versucht, euren Sohn zu verstehen!
Kalbert: Vielen Dank.
``` 
`[Ende]` 

**Weiter mit 1.2.** 

Spieler geht mit Svein mit um mit dem Vater zu reden.

```yml
Spieler: Kalbert, ich habe Euren Sohn gefunden und ihn auch gleich mitgebracht.
Kalbert: Svein, da bist du ja, was hast du denn die ganze Zeit gemacht! Hast du die Pelze?
Svein: Nein, ich.... ich muss mit dir reden, Vater.
Kalbert: Reden? Wozu? Wir sind hier zum Jagen, nicht zum Reden. 
Spieler: Kalbert, bitte hört zu, was Euch Euer Sohn sagen will!
*Kalbert schaut erstaunt von dir zu Svein*
Svein: Vater, du weißt, dass ich gut mit dem Bogen umgehen kann, aber ich will keine Katzen schießen und auch keine Wölfe. Ich bewundere sie zu sehr, als dass ich ihnen ein Leid antun könnte. 
*Kalbert schaut Svein sprachlos an und wendet sich dann zu dir*
Kalbert: Ein Jäger, der nicht jagen will, und das soll mein Sohn sein?
Spieler: Ein Jäger mit Sinn für Schönheit, und ein Jäger, der für seine Überzeugung einsteht, auch wenn es ihm schwer gefallen ist. Ihr solltet stolz auf Euren Sohn sein. Er hat den Mut aufgebracht, es Euch zu sagen ... und vertraut darauf, dass Ihr es akzeptieren werdet. 
Kalbert: Soso, braucht es soviel Mut, dem eigenen Vater etwas zu sagen?
Svein: Ja Vater, deine Erwartungen in mich waren so hoch und ich wollte dich nicht enttäuschen. 
Kalbert: Nun gut, ich werde damit leben müssen, dass...  ach was ... ich sollte Euch eine Belohnung dafür geben, dass Ihr Svein gesucht habt. Nehmt dies, er wird es nicht haben wollen. 
Spieler: Habt Dank!
```
`[Ende]`

> 2.  Spieler: Du machst es dir leicht, aber ich will dir die Pelze besorgen. Warte hier, bis ich wieder komme. 

`[QUESTSTART]`[Seltene Pelze](#seltene-pelze)

> **Questlog** *Töte Schimmerwölfe und Bergkatzen und bringe Svein jeweils 7 ihrer Pelze. Die Bergkatzen sind an den westlichen Berghängen oder Plateaus, bis zur Höhe des Ballons. Die Wölfe tummeln sich im Wald.*

Spieler sammelt alle Pelze und geht zu Svein zurück. 

```yml
Spieler: Svein, ich bin zurück.
Svein: Hast du die Pelze?
Spieler: Ja, obwohl es mir auch schwer gefallen ist, die Eisen-Bergkatzen haben eine wunderbare Zeichnung. Was tust du jetzt, gehst du zurück zu deinem Vater und tust so, als ob du die Pelze gesammelt hast, die Tiere getötet?
Svein: Was bleibt mir anderes übrig? Ich will seinen Respekt und seine Zuneigung nicht verlieren. DankIch bin sehr froh, dass du mir geholfen hast, hier, nimm das als Dank.
Spieler: Willst du dir es nicht nochmals überlegen?
```
> 1. Svein: Nein, geh du zu meinem Vater und sage ihm, dass ich gleich komme. 

`[Ende]`

















Z.B.
# Wenn Quest der-verlorene-jaeger
          


Belohnung: Robuste Lederweste + 2 Dukaten
