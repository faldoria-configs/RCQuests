# Die Erlaubnis <!-- omit in toc -->

Während Elius den Ballon repariert soll der Spieler nochmal ins Camp und mit seinen Leuten Reden. Marduk weist ihn draufhin sich vorzubereiten und die Türme am Strand zu erkunden.

- [Vorrausetzungen](#vorrausetzungen)
- [Aufgaben](#aufgaben)
    - [1. Die Erlaubnis](#1-die-erlaubnis)
    - [Türme](#türme)
        - [Aufgabenübersicht](#aufgabenübersicht)
            - [Erkundungspunkte](#erkundungspunkte)
- [NPCs](#npcs)
    - [Hauptmann Marduk](#hauptmann-marduk)
        - [Standartsätze](#standartsätze)
            - [Vor der Quest](#vor-der-quest)
            - [Während der Quest](#während-der-quest)
            - [Nach der Quest](#nach-der-quest)
        - [Ausrüstung](#ausrüstung)
        - [Standort](#standort)
- [Items](#items)
    - [Zerschlissene Robe](#zerschlissene-robe)
- [Mobs](#mobs)
- [Belohnung](#belohnung)
- [Referenzen](#referenzen)

## Vorrausetzungen

[HQ Reparaturarbeiten](../2-reparaturarbeiten/README.md) - Abgeschlossen

## Aufgaben

### 1. Die Erlaubnis

```yml
Marduk: Ich hoffe du weißt was du tust, aber du bist der einzige der gerade auf diese Reise gehen kann.
Spieler: Das ist etwas sehr wichtiges, oder?
Marduk: Ja, du wirst es großartig machen. Nun Gut, aber du solltest dich noch etwas besser vorbereiten bevor ich dir die Erlaubnis geben von hier fort zu gehen.
Marduk: Außerdem hilf doch den anderen hier im Camp auch noch bitte.
Spieler: Das mache ich. Welche Aufgabe hast du für mich denn noch?
Marduk: Am Strand sind anscheinend einige Ruinen von Türmen, die einst wohl mal die Küste sichern sollten. Gehe doch dorthin und schaue ob du etwas brauchbares findest.
```

> Ich mache mich direkt auf den Weg.
`[QUEST START]` [Die Erlaubnis](#1.-die-erlaubnis)  
> **QuestLog:** *Erkunde die drei Turmruinen und finde etwas nützliches dort.*

### Türme

#### Aufgabenübersicht

Zu erledigende Aufgaben zum Abschließen der Quest.
> 1. Auf jedem Rüstungsslot ein [Item](#items)  
> 2. [Türme erkunden](#erkundungspunkte)  

Bei den Türmen [Events](../events.md) beachten.

##### Erkundungspunkte

Nördlicher Turm
```yml
x: 3738
y: 8101
z: -2898
world: faldoria.eisenküste
```
> Chat ausgabe: Weiter Komme ich wohl nicht mehr hoch, oder doch?

Mittlerer Turm
```yml
x: 3619
y: 85
z: -2578
world: faldoria.eisenküste
```
> Chat ausgabe: Diesen Turm sollte ich nun erkundet haben.

Südlichster Turm
```yml
x: 3711
y: 68
z: -2547
world: faldoria.eisenküste
```
> Chat ausgabe: Dieser Turm ist sehr klein, hier finde ich sicher nicht viel.

Nachdem erledigen aller Aufgaben, spricht Spieler Marduk an.

```yml
Spieler: Hauptmann Marduk, die Türme waren sehr zerfallen, aber das ein oder andere konnte ich finden.
Marduk: Du siehst auch bereiter aus als vorher.
Spieler: Kann ich nun los zu Elius und ihm sagen das ich mit ihm mitfliegen werde?
Marduk: Ja, ich gebe dir die Erlaubnis nun los zu ziehen, finde mehr über dieses Land heraus. Wir werden uns hier erstmal weiter aufhalten. Komm aber bald wieder und melde dich bei uns.
Spieler: Ich bin ganz aufgeregt, keiner von uns war jemals wo ich hingehen werde. Ich werde aber so schnell es geht wieder hier her zurück kommen. 
Marduk: Pass auf dich auf und ich habe noch etwas von uns allen für dich.
Spieler: Vielen dank, aber ich sollte mich nun auf den Weg machen. Haltet durch.
```

`[QUEST ENDE]` [Die Erlaubnis](#1.-die-erlaubnis) und erhält [Belohnung](#belohunung) 

Elius ist dann erst wieder 30 Minuten später ansprechbar in der Zwischenzeit

```yml
Elius: Ich bin noch nicht soweit, komm bitte später wieder.
```

Weiter bei [HQ Die Erlaubnis](../3-die-erlaubnis/README.md)

## NPCs

### Hauptmann Marduk

Er schimpft sich zwar Hauptmann, es gibt aber eigentlich keine richtigen Truppen bei den Kaishi. Marduk ist ein sehr entspannter Typ, er hat keine Kampferfahrungen, soll sich aber um die Verteidigung kümmern.

#### Standartsätze

##### Vor der Quest

1. Nicht vorhanden bzw. siehe Quest

##### Während der Quest 

1. Geh und erkunde die drei Türme am Strand. Einer ist im Norden die anderen beiden sind südlich von hier. 
2. Wir zählen alle auf dich.

##### Nach der Quest

1. Ich hoffe wir sehen dich bald wieder, nachdem du mehr über dieses Land erfahren hast.
2. Du bist gut vorbereitet auf deine Reise, das gibt uns allen Hoffnung.

#### Ausrüstung

Lederrüstung ohne Helm
Steinaxt in der Hand

#### Standort

```yml
x: 3645
y: 63
z: -2829
world: faldoria
```

## Items

TurmLootliste

### Zerschlissene Robe

Ein gewöhnliches Brustteil, das seine besten Tage schon hinter sich hat.  
Belohnung für Kleriker und Magier.

```yml
ID: 
name: Zerschlissene Robe
type: Rüstung
quality: COMMON
item: LEATHER TUNIC
lore: Diese Robe scheint ihre besten Zeiten hinter sich zu haben, aber besser als nichts.
max-stack-size: 1
attributes: +1 ausdauer / +1 Int
```

## Mobs

Keine

## Belohnung

[Reparaturarbeiten](#1.-die-erlaubnis)
> 50 Heller  
> 50 exp  

## Referenzen


