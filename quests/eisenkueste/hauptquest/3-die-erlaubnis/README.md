# Die Erlaubnis <!-- omit in toc -->

Während Elius den Ballon repariert soll der Spieler nochmal ins Camp und mit seinen Leuten Reden. Marduk weist ihn draufhin sich vorzubereiten und die Türme am Strand zu erkunden.

##  Übersicht <!-- omit in toc -->
- [Noch zu klären](#noch-zu-kl%C3%A4ren)
- [Vorrausetzungen](#vorrausetzungen)
- [Aufgaben](#aufgaben)
  - [1. Die Erlaubnis](#1-die-erlaubnis)
  - [`[QUEST START]` Die Erlaubnis](#quest-start-die-erlaubnis)
  - [Türme](#t%C3%BCrme)
    - [Aufgabenübersicht](#aufgaben%C3%BCbersicht)
      - [Erkundungspunkte](#erkundungspunkte)
- [NPCs](#npcs)
  - [Hauptmann Marduk](#hauptmann-marduk)
    - [Standartsätze](#standarts%C3%A4tze)
      - [Vor der Quest](#vor-der-quest)
      - [Während der Quest](#w%C3%A4hrend-der-quest)
      - [Nach der Quest](#nach-der-quest)
    - [Ausrüstung](#ausr%C3%BCstung)
    - [Standort](#standort)
- [Items](#items)
  - [Kleiner Zauber Almanach](#kleiner-zauber-almanach)
  - [Anfänger Zwergenschild](#anf%C3%A4nger-zwergenschild)
  - [Jäger Talisman](#j%C3%A4ger-talisman)
- [Mobs](#mobs)
- [Belohnung](#belohnung)
- [Referenzen](#referenzen)

## Noch zu klären

Koords neu setzen
Belohnungen anpassen ?

## Vorrausetzungen

[HQ Reparaturarbeiten](../2-reparaturarbeiten/README.md) - Abgeschlossen

## Aufgaben

### 1. Die Erlaubnis


**Marduk:** ` Ich hoffe, du weißt was du tust, aber du bist der Einzige, der gerade auf diese Reise gehen kann.`  
Das ist etwas sehr Wichtiges, oder?  
**Marduk:** ` Ja, du wirst es großartig machen. Nun gut, aber du solltest dich noch etwas besser vorbereiten bevor du gehst, ich hätte da noch eine besondere Aufgabe für dich.`  
**Marduk:** ` Und, habe ich es schon gesagt? Hilf doch den anderen hier im Camp auch noch bitte.`  
Das mache ich. Welche Aufgabe hast du für mich denn noch?   
**Marduk:** `Am Strand sind anscheinend einige Ruinen von Türmen, die einst wohl mal die Küste sichern sollten. Gehe doch dorthin und schaue ob du etwas Brauchbares findest.`

1. Ich mache mich direkt auf den Weg.


### `[QUEST START]` [Die Erlaubnis](#1.-die-erlaubnis)  
> **QuestLog:** *Erkunde die drei Turmruinen und finde dort etwas Nützliches .*

### Türme

#### Aufgabenübersicht

Zu erledigende Aufgaben zum Abschließen der Quest.

> 1. Auf jedem Rüstungsslot ein [Item](#items)   

> 2. [Türme erkunden](#erkundungspunkte)  

Bei den Türmen [Events](../events.md) beachten.

##### Erkundungspunkte

**Nördlicher Turm**
```yml
x: 3738
y: 8101
z: -2898
world: faldoria.eisenküste
```
> Chatausgabe: Weiter komme ich wohl nicht mehr hoch, oder doch?

**Mittlerer Turm**
```yml
x: 3619
y: 85
z: -2578
world: faldoria.eisenküste
```
> Chatausgabe: Diesen Turm sollte ich nun erkundet haben.

**Südlichster Turm**
```yml
x: 3711
y: 68
z: -2547
world: faldoria.eisenküste
```
> Chatausgabe: Dieser Turm ist sehr klein, hier finde ich sicher nicht viel.

**Nachdem Erledigen aller Aufgaben spricht Spieler Marduk wieder an.**

Hauptmann Marduk, die Türme waren sehr zerfallen, aber das ein oder andere konnte ich finden.
**Marduk:** ` Du siehst auch bereiter aus als vorher.`   
Kann ich nun los zu Elius und ihm sagen, dass ich mit ihm mitfliegen werde?  
**Marduk:**  ` Ja, ich gebe dir die Erlaubnis nun loszuziehen, finde mehr über dieses Land heraus. Wir werden uns hier erstmal weiter aufhalten. Komm aber bald wieder und melde dich bei uns.`
Ich bin ganz aufgeregt, keiner von uns war jemals wo ich hingehen werde. Ich werde aber so schnell es geht wieder hierher zurück kommen.    
**Marduk:** ` Pass auf dich auf und  - ich habe noch etwas von uns allen für dich. Es ist eines unserer kostbarsten Besitztümer, noch aus der alten Zeit bevor wir auf Ankanor lebten.`
Vielen Dank, aber ich sollte mich nun auf den Weg machen. Haltet durch.


`[QUEST ENDE]` [Die Erlaubnis](#1.-die-erlaubnis) und erhält [Belohnung](#belohunung) 

`[QUEST START]` [Die Reise beginnt](../4-die-reise-beginnt/README.md)   
**QuestLog:** *Gehe zu Elius an seinem Ballon und reise mit ihm ins Landesinnere. Sofern du schon bereit dafür bist.*

Weiter bei [HQ Die Reise beginnt](../4-die-reise-beginnt/README.md)

## NPCs

### Hauptmann Marduk

Er schimpft sich zwar Hauptmann, es gibt aber eigentlich keine richtigen Truppen bei den Kaishi. Marduk ist ein sehr entspannter Typ, er hat keine Kampferfahrungen, soll sich aber um die Verteidigung kümmern.

#### Standartsätze

##### Vor der Quest

1. Nicht vorhanden bzw. siehe Quest

##### Während der Quest 

1. Geh und erkunde die drei Türme am Strand. Einer ist im Norden, die anderen beiden sind südlich von hier. 
2. Wir zählen alle auf dich.

##### Nach der Quest

1. Ich hoffe wir sehen dich bald wieder, nachdem du mehr über dieses Land erfahren hast.
2. Du bist gut vorbereitet auf deine Reise, das gibt uns allen Hoffnung.

#### Ausrüstung

Lederrüstung ohne Helm
Steinaxt in der Hand

#### Standort

```yml
x: 
y: 
z: 
world: faldoria
```

## Items

### Kleiner Zauber Almanach

```yml
ID: 40
```

### Anfänger Zwergenschild

```yml
ID: 41
```

### Jäger Talisman

```yml
ID: 42
```

## Mobs

Keine

## Belohnung

[Reparaturarbeiten](#1.-die-erlaubnis)
> 50 Heller  
> 50 exp   
> [Jäger Talisman](#jäger_talisman) - für Assassine/Waldläufer  
> [Anfänger Zwergenschild](#anfänger_zwergenschild) - für Krieger  
> [Kleiner Zauber Almanach](#kleiner_zauber_almanach) - für Elementarist/Kleriker

## Referenzen


