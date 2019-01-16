# Jarmundshain wärmt auf <!-- omit in toc -->

Issue 64

[Link zum Google Docs Dokument](https://docs.google.com/document/d/1qNGtcrUiKUG56wcReh-0IIR2xnIP8pkHrfHObpcPeTo)

## Übersicht

- [Übersicht](#%C3%BCbersicht)
- [Noch zu tun](#noch-zu-tun)
- [Verändert](#ver%C3%A4ndert)
- [Vorherige Quest Eisenküste](#vorherige-quest-eisenk%C3%BCste)
- [Ablauf](#ablauf)
- [Dialoge](#dialoge)
  - [`[Queststart]`Frage Elius aus](#queststartfrage-elius-aus)
  - [Dialog 1 Elius](#dialog-1-elius)
  - [`[Queststart]`Jarmundshain wärmt auf](#queststartjarmundshain-w%C3%A4rmt-auf)
  - [Dialog 2 Vinnan](#dialog-2-vinnan)
  - [`[Queststart]` Bärenjagd](#queststart-b%C3%A4renjagd)
  - [`[Queststart]` Abgabe Bärenfell](#queststart-abgabe-b%C3%A4renfell)
  - [Dialog 3 Inge](#dialog-3-inge)
  - [`[Queststart]` Belohnung](#queststart-belohnung)
  - [Dialog 4 Vestrak](#dialog-4-vestrak)
  - [Dialog 5 Vinnan](#dialog-5-vinnan)
- [NPCs](#npcs)
  - [Elius](#elius)
    - [Standartsätze](#standarts%C3%A4tze)
      - [Vor der Quest:](#vor-der-quest)
      - [Während der Quest:](#w%C3%A4hrend-der-quest)
      - [Nach der Quest: Frage Elius aus](#nach-der-quest-frage-elius-aus)
      - [Nach der Quest:](#nach-der-quest)
    - [Ausrüstung](#ausr%C3%BCstung)
    - [Standort](#standort)
  - [Vinnan](#vinnan)
    - [Standartsätze](#standarts%C3%A4tze-1)
      - [Vor der Quest:](#vor-der-quest-1)
      - [Während der Quest, wenn die Bären noch nicht getötet sind:](#w%C3%A4hrend-der-quest-wenn-die-b%C3%A4ren-noch-nicht-get%C3%B6tet-sind)
      - [Während der Quest, wenn schon alle Questgegenstände gesammelt sind:](#w%C3%A4hrend-der-quest-wenn-schon-alle-questgegenst%C3%A4nde-gesammelt-sind)
      - [Nach der Quest:](#nach-der-quest-1)
    - [Ausrüstung](#ausr%C3%BCstung-1)
    - [Standort](#standort-1)
  - [Inge](#inge)
    - [Standartsätze](#standarts%C3%A4tze-2)
      - [Vor der Quest: Bärenjagd](#vor-der-quest-b%C3%A4renjagd)
      - [Während der Quest Abgabe Bärenfell](#w%C3%A4hrend-der-quest-abgabe-b%C3%A4renfell)
      - [Nach der Quest:](#nach-der-quest-2)
    - [Ausrüstung](#ausr%C3%BCstung-2)
    - [Standort](#standort-2)
  - [Vestrak](#vestrak)
    - [Standartsätze](#standarts%C3%A4tze-3)
      - [Vor der Quest:](#vor-der-quest-2)
      - [Während der Quest:](#w%C3%A4hrend-der-quest-1)
      - [Nach der Quest:](#nach-der-quest-3)
    - [Ausrüstung](#ausr%C3%BCstung-3)
    - [Standort](#standort-3)
- [Items](#items)
  - [Fellüberwurf](#fell%C3%BCberwurf)
- [Mobs](#mobs)
  - [Frostakbär ??](#frostakb%C3%A4r)
- [Belohnungen](#belohnungen)

## Noch zu tun

Skins verlinken
Item und Mobs hinzufügen, Namen nachsehen
Belohnungen


## Verändert

- Dialog am Anfang hinzugefügt,
- freiw. Quest in HQ integriert,
- Infodump Jorgendder und Kaltenstrom,
- Quest in mehrere aufgespalten
- Gespräch mit Vestrak erweitert, etwas umgeschrieben

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



## Ablauf

1. Der Spieler ist mit Elius mit dem Ballon nach Jarmundshain gefahren und dort gelandet. Er wechselt noch einige Worte mit Elius (-> Eisenküste-Dialog, s.o.)
2. Spielerin fragt Elius etwas aus, der gibt guten Rat
3. Spielerin macht sich auf den Weg zu dem Dorfältesten Vinnan.
4. Vinnan schickt die Spielerin auf die Bärenjagd.
5. Die Felle und das Fleisch sollen Inge, der Frau des Schmieds gebracht werden.
6. Bei Inge trifft die Spielerin auf Vestrak, den Sohn des Schmieds.
7. Die Spielerin holt sich die Belohnung von Vinnan ab und erhält neue Aufgaben.


## Dialoge

Spieler:  *Du fühlst dich plötzlich sehr unsicher und alleine. Vielleicht solltest du dich doch noch an Elius halten und ihn etwas ausfragen*

### `[Queststart]`[Frage Elius aus](#frage-elius-aus)

`[Questlog]`  *Hole von Elius noch einige Informationen ein*

### Dialog 1 [Elius](#elius)

```yml
Spielerin: Elius, wo sind wir hier eigentlich?
Elius: Mitten in den Frostak Hochebenen, in Jarmundshain.
Spielerin: Und das ist wo?
Elius: Mitten im Landesinneren, westlich von Kaltenstrom. Hättest du dich nicht so auf den Boden gekauert, dann hättest du mehr gesehen. 
Spielerin: Aber es war ja so kalt, der eisige Wind hat meine Augen so tränen lassen, dass ich eh nichts gesehen hätte.
Elius: Nun, sei es wie es will, wir sind jetzt da. 
Spielerin: Jarmundshain hast du gesagt, der Name klingt seltsam. 
Elius: Die Bewohner sind auch seltsame Jorgendder *lacht*, recht zurückgezogen und meist etwas mürrisch.  
Spielerin: Joggender? Was für Leute sind denn das wieder?
Elius: Jorgendder - sprich ja ihren Namen nicht falsch aus! Unser Volk stammt von den Zwergen ab, aber hat sich vor, warte, vor über tausend Jahren mit einem nordischen Seefahrevolk vermischt. Wir haben viel von beiden alten Stämmen, und nicht nur die guten Seiten, aber du wirst sehen, man kann schon mit uns auskommen. 
Spielerin: Wir? Bist du etwa auch ein Jorgennder?
Elius: Na klar, hast du das nicht gewußt?
Spielerin: Nein, du hast es nicht erwähnt. Werden die Leute im Dorf mit mir sprechen? 
Elius: Wenn du ihnen nicht dumm kommst schon. Ich würde mich an deiner Stelle an den Ältesten wenden. Ich nehme an, du willst nach Kaltenstrom, dabei kann dir Vinnan sicherlich helfen. 
Spielerin: Kaltenstrom ist die große Stadt, über die wir geflogen sind, nicht wahr, mit der großen Burg in der Mitte. Gehört die auch den Jorgenddern?
Elius: Ja genau, das ist nicht ihre Hauptstadt, das ist Sorvenheim, aber Kaltenstrom ist ihr ganzer Stolz, weil sie es als Jorgendder gebaut haben und nicht von den Zwergen übernommen. Und wenn du den Namen Gimdus hörst, das ist ihr Jarl.
Spielerin: Jarl?
Elius: Jarl ist ein Titel, er ist nur dem König untertan.
Spielerin: *Du seufzt* Ich glaube, ich konzentriere mich jetzt lieber auf das Hier und Jetzt.
Spielerin: Wo finde ich diesen Vinnan?
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

### Dialog 2 [Vinnan](#vinnan)
```yml
Vinnan: Grüße Fremder, habt Ihr Hunger?
Spielerin: Ähm... Grüße...  ich bin [Spielername]. Ja, so ein wenig Hunger habe ich schon.
Vinnan: Schön, Euch kennenzulernen, [Spielername], ich heiße Vinnan und kümmere mich um die meisten Belange hier in Jarmundshain. Ich kann Euch Brot anbieten, wenn Ihr Hunger habt. 
Spielerin: Oh, ja, gerne!
```

> Spielerin erhält 3 [Frostakbrotlaib](#frostakbrotlaib)

Danke, kann ich vielleicht auch etwas helfen?  
**Vinnan:** `Oh, Ihr möchtet helfen? Das trifft sich gut, hier ist es gerade sehr chaotisch.`  
_*Du schaust dich etwas um und siehst, dass hier wirklich eine helfende Hand nötig wäre*_  
Räumt hier denn niemand auf?  
**Vinnan:** `So meinte ich das nicht! *er lacht und du wirst rot*`  
**Vinnan:** `Gunnar, unser Schmied und einziger Kämpfer im Dorf ist vor einer Weile aufgebrochen, um seine verschwundene Tochter zu suchen. Nun fehlt es uns an Fleisch und Fellen. Der Weizen wird dieses Jahr sicherlich nicht reichen.`  
Ich kann auch helfen, nach der Tochter vom Schmied zu suchen.  
**Vinnan:** `Nein, das kann ich nicht verantworten.`  
Warum darf ich Euch da nicht unterstützen?  
**Vinnan:** `Ihr dürft helfen, das Dorf mit Fleisch und Fellen zu versorgen. Geht jagen und bringt die Sachen dann zur Frau vom Schmied.`  
Vinnan, warum wird der Weizen denn nicht reichen?  
**Vinnan:** `Ich habe gerade keine Zeit es zu erklären, Ihr werdet es aber gewiss unweigerlich selbst bald erfahren.`  
Nun gut, ich lass mich überraschen. Dann mach ich mich wohl mal auf die Jagd.  

**Vinnan:** `Gut danke, meldet Euch bei seiner Frau wenn ihr ein Bären getötet habt, sie verarbeitet die Felle.`  
1. _Bären? Ähm.. ich habe es mir anders überlegt._  
    **Vinnan:** `*lacht* Ach was, Ihr schafft das schon.`

2. _Joa, das dürfte kein Problem werden, ich bin schon gut in Übung was sowas angeht._  
    **Vinnan:** `Na dann, vergesst nicht, die Felle zur Frau des Schmieds zu bringen.`  

`[Questende]`[Jarmundshain wärmt auf](#jarmundshain-waermt-auf)

*****
### `[Queststart]` [Bärenjagd](#baerenjagd)
`[Questlog]` *Tötet Bären rund um den Jarmundshain und erbeutet 10 mal Sehniges Bärenfleisch und 10 mal Zerschundenes Bärenfell.*

**Sobald alle Items gesammelt sind:**

`[Questende]`[Bärenjagd](#baerenjagd)

### `[Queststart]` [Abgabe Bärenfell](#abgabe-baerenfell)

`[Questlog]` *Bringt die Felle zur Frau des Schmieds*


**Sobald die Spielerin (mit Questitems) bei Inge ankommt**


### Dialog 3 [Inge](#inge)
```yml
Inge: *zieht die Augenbrauen hoch und schaut dich fragend an, sagt aber nichts*
Spielerin: Uhm... seid Ihr die Frau vom Schmied?
Inge: Wer möchte das wissen?
Spielerin: Ich bin [Spielername]. Ich habe im Auftrag von Vinnan Bären getötet und das da erbeutet. *Du zeigst auf die Felle und das Fleisch*
Inge: Oh, sehr schön. Ich mache mich gleich an die Arbeit. Wenn Euch eine Belohnung versprochen wurde, sprecht mit Vinnan, ich habe für sowas gerade echt keinen Kopf. 
```
`[Questende]` [Abgabe Bärenfell](#abgabe-baerenfell)

>> sehniges Bärenfleisch und zerschundene Bärenfelle verschwinden aus dem Inventar

### `[Queststart]` [Belohnung](#belohnung)
`[Questlog]` *Sprecht mit Vinnan wegen der Belohnung*


**Während die Spielerin noch da steht, kommt ein Mann aus dem Haus und spricht die Spielerin an. Keine Quest, Gespräch kann durch Weglaufen beendet werden. Später wieder aufnehmbar?**

### Dialog 4 [Vestrak](#vestrak)
```yml
Vestrak: Sie hat mich Euch gesprochen?
Spieler: Ähm huch? *vor dir steht ein breitschuldriger Koloss von Mann*
Vestrak: Meine Mutter..  sie ist immer zurückgezogener geworden seitdem Arula und danach noch Papa weg sind. Was hat sie gesagt?
Spieler: Sie hat nur die Felle und das Fleisch angenommen, mehr nicht.
Vestrak: Ich halt es langsam nicht mehr aus, ich kann sie aber auch nicht alleine lassen.
Spielerin: Was ist denn passiert?  
Vestrak: Arula war.. ist meine Schwester. Sie ist verschwunden, war nur in  den Wald gegangen, um einige Pilze zu sammeln. Als sie nicht wiederkam, gingen mein Vater und ich sie suchen. 
Spielerin: *Du hörst geduldig zu, was Vestrak dir erzählt, er scheint das Bedürfniss zu haben, mit jemanden zu reden.*
Vestrak: Wir teilten uns auf, um eine größere Fläche abzusuchen. So geschah es, dass mein Vater auch verschwand. *Er zuckt mit den Schultern und fängt fast zum Weinen an*
Spielerin: Vielleicht kann ich Euch ja helfen, aber zuerst muss ich zu Vinnan zurück. 
Vestrak: Passt auf Euch auf!
```

**Spielerin sucht Vinnan auf**

### Dialog 5 [Vinnan](#vinnan)

```yml
Vinnan: Da seid Ihr ja wieder.
Spielerin: Alles erledigt.
Vinnan: Das ging schneller als erwartet, hört Euch doch bitte auch noch etwas im Dorf um, ob Ihr dort Hilfe anbieten könnt, das würde mir auch sehr helfen.
Spielerin: Gerne... nur, ich bin sehr kapp an Vorräten und..
Vinnan: Oh ja, entschuldigt, natürlich werd ich Euch diesen Aufwand entlohnen. Helft den Dorfbewohnern und Ihr werdet es nicht bereuen.
Spielerin: Das hört sich gut an, ich werde schauen was ich tun kann.
Vinnan: Nehmt diesen Fellüberwurf als Dank für die Bärenjagd und dieses Papier um Euch aufschreiben zu lassen, wem Ihr geholfen habt.
Spieler: Vielen Dank!
```

`[Questende]` [Belohnung](#belohnung)

**Belohnung** [Fellüberwurf](#fellüberwurf)


>>> Die Spielerin bekommt [10 Leeres Papier] für die nächste Quest

>>> Nächste HQuest: [Vinnans helfende Hand](#vinnans-helfende-hand)   LINK! falsch?



## NPCs

### Elius

#### Standartsätze

##### Vor der Quest:
-

##### Während der Quest:
-
##### Nach der Quest: [Frage Elius aus](#queststartfrage-elius-aus)
Vor allen anderen Quests:

`Elius: Na, was zögerst du?`
##### Nach der Quest: 
```
1.
Elius: Nun, wie kommst du mit den Dorfbewohnern aus?
Spielerin: Gut, ich muss weiter!

2.
Elius: Na, wie hat Vinnan reagiert?
Spieler: Er braucht wirklich sehr viel Hilfe
Elius: Na lass dich nicht aufhalten.
```


#### Ausrüstung

Skin? Kompass in der Hand 

#### Standort   

```yml
x: 497
y: 117
z: -1973
world: faldoria.eisenküste
```

### Vinnan

Vinnan ist der Älteste der Jorgenddersiedlung Jarmundshain und kümmert sich um die Belange der Einwohner. Er ist ein sehr freundlicher Mann, der gerne Hilfe anbietet, aber auch darum bitttet, wenn er welche braucht. 

#### Standartsätze

##### Vor der Quest:
Wenn die Quest [Jarmundshain wärmt auf](#jarmundshain-waermt-auf) noch nicht angenommen ist: 
*`Vinnan bemerkt dich nicht`*
##### Während der Quest, wenn die Bären noch nicht getötet sind:
```
1. 
Vinnan: Na, seid Ihr schon fertig?
Spielerin: Nein, ich mach nur mal Pause.

2. 
Vinnan: Braucht Ihr noch was?
Spielerin: Ja, *räusper*, was sollte ich nochmal tun?
Vinnan: *schaut sehr geduldig* Bären töten und danach das Fleisch und die Felle zur Frau des Schmieds bringen. 
Spielerin: Wo finde ich denn die Bären?
Vinnan: Sehr nah an und auf den Bergen, sie leben größtenteils in schneebedeckten Regionen.
```
##### Während der Quest, wenn schon alle Questgegenstände gesammelt sind:

```
Vinnan: Braucht Ihr noch was?

1.
Spielerin: Auftrag erledigt, hier sind die Felle und das Fleisch.

>> Falls 1. angeklickt wird:
Vinnan: Bitte bringe es zu Inge, der Frau des Schmieds, ich kann das nicht verarbeiten.
Spielerin: Dein Ernst? Wo finde ich denn diese Frau des Schmieds?
Vinnan: Sie wohnt am Hang, dort wo das Wasser vom Berg ins grüne Land fließt. Es ist das einzige Haus mit Wasserrad hier im Dorf.

2. Spielerin: Vinnan, wo finde ich Inge?

>> Falls 2. angeklickt wird:
Vinnan: Sie wohnt am Hang, dort wo das Wasser vom Berg ins grüne Land fließt. Es ist das einzige Haus mit Wasserrad hier im Dorf.

```
##### Nach der Quest: 

#### Ausrüstung

Brot in der Hand?
Skin:

#### Standort   

```yml
x: 505
y: 111
z: -1851
world: faldoria.eisenküste
```

### Inge

Frau des Schmieds, die Felle verarbeitet

#### Standartsätze

##### Vor der Quest: [Bärenjagd](#baerenjagd)
```
Inge: Wer seid Ihr und was wollt Ihr? *unwirsch*
Spielerin: Ich bin [Name der Spielerin], fremd hier im Land. Verzeiht, dass ich Euch gestört habe.
``` 
##### Während der Quest [Abgabe Bärenfell](#abgabe-baerenfell)
(wenn nicht alle Questitems vorhanden sind)

```
Inge: *schaut dich an und zieht die Augenbrauen hoch* Ist was?
Spielerin: Oh, ich seh gerade, mir fehlt doch noch was. Ich komm später nochmal wieder.
```

##### Nach der Quest: 

Alternativ:

```
1.
Inge: Wolltet Ihr noch was?
Spielerin: *du räusperst dich*  Ne, bin schon weg.

2.
Spielerin: Kann ich Euch irgendwie helfen?
Inge: Nein *schaut auf den Boden*
```


#### Ausrüstung

Schere in der Hand

#### Standort   

```yml
x: 487
y: 109
z: -1805
world: faldoria.eisenküste
```

### Vestrak

#### Standartsätze

##### Vor der Quest:
Vestrak: Lasst mich bitte in Ruhe.

##### Während der Quest:
-
##### Nach der Quest: 
Vestrak: Schön, dich zu sehen.
Spielerin: *Du lächelst Vestrak aufmunternd an*

#### Ausrüstung

Welchen Skin hat der NPC? Was hält er in der Hand?

#### Standort   

```yml
x: 497
y: 104
z: -1805
world: faldoria.eisenküste
```

## Items
### Fellüberwurf

## Mobs

### Frostakbär 
name: Frostakbär
type: polar_bear
aggrvo: true
passie: false
min-level: 5
max-level: 8

## Belohnungen







