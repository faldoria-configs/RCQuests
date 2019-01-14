# Jarmundshain wärmt auf <!-- omit in toc -->

Issue 64

[Link zum Google Docs Dokument](https://docs.google.com/document/d/1qNGtcrUiKUG56wcReh-0IIR2xnIP8pkHrfHObpcPeTo)

## Noch zu tun

viel 

## Verändert

Dialog am Anfang hinzugefügt, freiw. Quest in HQ integriert, Infodump Jorgendder und Kaltenstrom

## Vorherige Quest Eisenküste

**`Teleport`**

```yml
x: 495
y: 117
z: -1973
world: Faldoria .Frostak_Hochebene.Jarmundshain
```

`[QUEST UPDATE]` [Die Reise beginnt](#4-die-reise-beginnt)

**QuestLog:** *Sprich mit Elius und höre was für eine Aufgabe er für dich hat.*

Elius spricht Spieler an.
```yml
Eluis: Noch rechtzeitig sicher gelandet.
Spieler: Wollten wir wirklich hier hin? Hier ist es ja noch kälter.
Elius: Ja hier wollten wir hin, ich hab den Brennstoff gerade noch so richtig eingeschätzt, weiter kommen wir nun nicht mehr.
```

`[QUEST ENDE]` [Die Reise beginnt](#4-die-reise-beginnt) und erhält [Belohnung](#belohnung) 

## Übersicht

- [Noch zu tun](#noch-zu-tun)
- [Verändert](#ver%C3%A4ndert)
- [Vorherige Quest Eisenküste](#vorherige-quest-eisenk%C3%BCste)
- [Übersicht](#%C3%BCbersicht)
- [Ablauf](#ablauf)
- [Dialoge](#dialoge)
  - [Dialog 1](#dialog-1)
  - [`[Queststart]`Jarmundshain wärmt auf](#queststartjarmundshain-w%C3%A4rmt-auf)
  - [Dialog 2](#dialog-2)
  - [`[Queststart]` Bärenjagd](#queststart-b%C3%A4renjagd)
  - [`[Queststart]` Abgabe Bärenfell](#queststart-abgabe-b%C3%A4renfell)

## Ablauf

1. Der Spieler ist mit Elius mit dem Ballon nach Jarmundshain gefahren und dort gelandet. Er wechselt noch einige Worte mit Elius (-> Eisenküste-Dialog, s.o.)
2. Spielerin fragt Elius etwas aus, der gibt guten Rat
3. Spielerin macht sich auf den Weg zu dem Dorfältesten Vinnan.


## Dialoge

Spieler:  *Du fühlst dich plötzlich sehr unsicher und alleine. Vielleicht solltest du dich doch noch an Elius halten und ihn etwas ausfragen*

`[Queststart]`[Frage Elius aus](#frage-elius-aus)

`[Questlog]`  *Hole von Elius noch einige Informationen ein*

### Dialog 1

```yml
Spielerin: Elius, wo sind wir hier eigentlich?
Elius: Mitten in den Frostak Hochebenen, in Jarmundshain.
Spielerin: Und das ist wo?
Elius: Mitten im Landesinneren, westlich von Kaltenstrom. Hättest du dich nicht so auf den Boden gekauert, dann hättest du mehr gesehen. 
Spielerin: Aber es war ja so kalt, der eisige Wind hat meine Augen so tränen lassen, dass ich eh nichts gesehen hätte.
Elius: Nun, sei es wie es will, wir sind jetzt da. 
Spielerin: Jarmundshain hast du gesagt, der Name klingt seltsam. 
Elius: Die Bewohner sind auch seltsame Jorgendder, recht zurückgezogen und etwas mürrisch.  
Spielerin: Joggender? Was für Leute sind denn das wieder?
Elius: Jorgendder - sprich ja ihren Namen nicht falsch aus! Das ist ein Volk, das von den Zwergen abstammt, aber sich vor, warte, vor ungefähr xxx Jahren mit einem nordischen Seefahrevolk vermischt hat. Haben viel von beiden alten Stämmen, und nicht nur die guten Seiten, aber du wirst sehen, man kann schon mit ihnen auskommen. 
Spielerin: Hmm, ja, werden sie mit mir sprechen? 
Elius: Wenn du ihnen nicht dumm kommst schon. Ich würde mich an deiner Stelle an dem Ältesten wenden. Ich nehme an, du willst nach Kaltenstrom, dabei kann dir Vinnan sicherlich helfen. 
Spielerin: Kaltenstrom ist die große Stadt im Osten, nicht wahr, dort wo 
(Kaltenstrom Info)

Elius: Ja genau... (Kaltenstrom Info)
Spielerin: Und wo finde ich diesen Vinnan?
Elius: Sein Haus liegt in der Richtung des Weizenfeldes, genau dahinter. Es ist ein sehr großes Haus, es sollte kaum zu verfehlen sein.
Spielerin: Was sage ich ihm dann?
Elius: Na, wo du hinwillst. Ihm im gleichen Atemzug Hilfe anzubieten wäre allerdings eine gute Idee, das dürfte ihn sicherlich freuen. 
Spielerin: In Ordnung, dann werde ich mein Glück mal versuchen. Und Elius....
Elius: Ja?
Spielerin: *du lächelst Elius an* Danke für die Ballonfahrt!
```

`[Questende]`[Frage Elius aus](#frage-elius-aus)

`[Belohnung]`  XP

### `[Queststart]`[Jarmundshain wärmt auf](#jarmundshain-waermt-auf)

[Questlog] *Sprich mit dem Ältesten im Jarmundshain, sein Name ist Vinnan.*

**Die Spielerin verlässt Elius und sucht den Dorfältesten Vinnan**

### Dialog 2
```yml
Vinnan: Grüße Fremder, habt Ihr Hunger?
Spielerin: Ähm... Grüße...  ich bin [Spielername]. Ja, so ein wenig Hunger habe ich schon.
Vinnan: Schön, Euch kennenzulernen, [Spielername], ich heiße Vinnan und kümmere mich um die meisten Belange hier in Jarmundshain. Ich kann Euch Brot anbieten, wenn Ihr Hunger habt. 
Spielerin: Oh, ja, gerne!
```

> Spielerin erhält 3 [Frostakbrotlaib](#frostakbrotlaib)

```yml
Spielerin: Danke, kann ich vielleicht auch etwas helfen?
Vinnan: Oh, Ihr möchtet helfen? Das trifft sich gut, hier ist es gerade sehr chaotisch.
Spielerin: *Du schaust dich etwas um und siehst, dass hier wirklich eine helfende Hand nötig wäre*
Spielerin: Räumt hier denn niemand auf?
Vinnan: So meinte ich das nicht! *er lacht und du wirst rot*
Vinnan: Gunnar, unser Schmied und einziger Kämpfer im Dorf ist vor einer Weile aufgebrochen, um seine verschwundene Tochter zu suchen. Nun fehlt es uns an Fleisch und Fellen. Der Weizen wird dieses Jahr sicherlich nicht reichen. 
Spielerin: Ich kann auch helfen, nach der Tochter vom Schmied zu suchen. 
Vinnan: Nein, das kann ich nicht verantworten.
Spielerin: Warum darf ich Euch da nicht unterstützen?
Vinnan: Ihr dürft helfen, das Dorf mit Fleisch und Fellen zu versorgen. Geht jagen und bringt die Sachen dann zur Frau vom Schmied.
Spielerin: Vinnan, warum wird der Weizen denn nicht reichen?
Vinnan: Ich habe gerade keine Zeit es zu erklären, Ihr werdet es aber gewiss unweigerlich selbst bald erfahren.
Spielerin: Nun gut, ich lass mich überraschen. Dann mach ich mich wohl mal auf die Jagd.
Vinnan: Gut danke, meldet Euch bei seiner Frau wenn ihr ein Bären getötet habt, sie verarbeitet die Felle.
```
> 1.

`Spielerin: Bären? Ähm.. ich habe es mir anders überlegt.`

`Vinnan: *lacht* Ach was, Ihr schafft das schon.`

> 2.

`Spielerin: Joa, das dürfte kein Problem werden, ich bin schon gut in Übung was sowas angeht. `

`Vinnan: Na dann, vergesst nicht, die Felle zur Frau des Schmieds zu bringen.`

`[Questende]`[Jarmundshain wärmt auf](#jarmundshain-waermt-auf)

*****
### `[Queststart]` [Bärenjagd](#baerenjagd)
`[estlog]`Qu *Tötet Bären rund um den Jarmundshain und erbeutet 10 mal Sehniges Bärenfleisch und 10 mal Zerschundenes Bärenfell.*

**Sobald alle Items gesammelt sind:**

`[Questende]`[Bärenjagd](#baerenjagd)

### `[Queststart]` [Abgabe Bärenfell](#abgabe-baerenfell)

`[Questlog]` *Bringt die Felle zur Frau des Schmieds*









 


