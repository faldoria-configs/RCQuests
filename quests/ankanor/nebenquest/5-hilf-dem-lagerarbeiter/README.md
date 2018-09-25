# Der Lagerarbeiter

[NPC Kansa](#Kansa) steht im Lager an der Versammlungshalle, weil sich das Lager langsam leer soll der Spieler dieses wieder füllen. Kansa bittet ihn Wolle, Äpfel, Fisch und Milch zu besorgen.

* [Ablauf](#ablauf)
* [Vorrausetzungen](#vorrausetzungen)
* [Aufgaben](#aufgaben)
    * [1. Hilf dem Lagerarbeiter](#1-hilf-dem-lagerarbeiter)
    * [2. Bringe die Vorräte zu Kansa](#2-bringe-die-vorräte-zu-kansa)
* [NPCs](#npcs)
    * [Kansa](#kansa)
        * [Standartsätze](#standartsätze)
            * [Vor der Quest](#vor-der-quest)
            * [Während der Quest](#während-der-quest)
            * [Nach der Quest](#nach-der-quest)
        * [Ausrüstung](#ausrüstung)
        * [Standort](#standort)
* [Items](#items)
    * [Schwarzer Barsch](#schwarzer-barsch)
    * [Geschorene Wolle](#geschorene-wolle)
    * [Frischer Eimer Milch](#frischer-eimer-milch)
    * [Roter Apfel](#roter-apfel)
* [Mobs](#mobs)
    * [Skelett](#skelett)
* [Belohnung](#belohnung)
* [Referenzen](#referenzen)

## Ablauf

1. Start: Spieler nähert sich Kansa
2. Spieler spricht [NPC Kansa](#Kansa) an welcher ihm die Aufgabe gibt Schafe zu scheren, Äpfel zu sammeln, Fische zu angeln und eine Kuh zu melken `Questbeginn:`[Hilf dem Lagerarbeiter](#hilf-dem-lagerarbeiter)
3. Für die Aufgabe bekommt der Spieler 1x leerer Eimer, 1x Angel und 1x Schere
4. Der Spieler beginnt mit der Aufgabe
    * Auf der Weide im Westen muss der Spieler Schafe scheren für 5x Wolle
    * Auf der Weide im Westen muss der Spieler mit dem Eimer eine Kuh melken
    * Auf der gesamten Insel sind Äpfel verteilt welche der Spieler aufsammeln kann. Außerdem finden sich in einigen Kisten auch Äpfel. Hiervon benötigt er 10.
    * In den Gewässern um und auf der Insel muss der Spieler 3x Schwarzer Barsch angeln
5. Spieler kehrt zurück und erhält eine [Belohnung](#Belohnung) `Questende:`[Hilf dem Lagerarbeiter](#hilf-dem-lagerarbeiter)

## Vorrausetzungen

Keine

## Aufgaben

### 1. Hilf dem Lagerarbeiter

Spieler wird von Kansa angesprochen sobald er in der Nähe (3 Blocks) vorbei läuft.

> **QuestLog:** *Sammle 10 Äpfel, angel 3 Schwarze Barsche und schere Schafe für 5 Wolle und melke eine Kuh. Schafe und Kühe findest du auf der Weide im westen. Äpfel sind überall auf der Insel zu finden. Barsche findest du hier in allen Gewässern.*

```yml
NPC: Hey, [Name des Spielers], Hast du mal nen Moment? Könntest du nicht zufällig etwas für mich erledigen?
```

> 1. Was soll ich denn tun?
> 2. Tut mir leid, Agnatus ist auf dem Weg. Ich habe keine Zeit!

```yml
NPC: "Nun gut, vielleicht hast du danach etwas Zeit für mich."
```

**Weiter nach #1:**

```yml
NPC: "Nun, die Lager sind so gut wie leer und ich brauche Hilfe beim einholen der Rohstoffe. Könntest du für mich die Schafe im westen scheren und eine Kuh melken? Außerdem brauche ich noch ein paar Schwarze Barsche und Äpfel."
```

> 1. Na klar! Du kannst auf mich zählen.

`[QUEST START]` [Hilf dem Lagerarbeiter](#hilf-dem-lagerarbeiter)

> 2. Nein, ich habe besseres zu tun…`[Ende]`

### 2. Bringe die Vorräte zu Kansa

*Spieler hat alles gesammelt und muss dann zum Questgeber zurück kehren.*

> **Questlog:** *Bringe die Vorräte zu Kansa.*

```yml
NPC: Hast du die Sachen?
```
> 1. Ja habe ich. `[QUEST ENDE]` [Hilf dem Lagerarbeiter](#hilf-dem-lagerarbeiter) und erhält [Belohnung](#Belohnung)

```yml
NPC: Danke vielmals für die Hilfe!
Spieler: Hab ich doch gern gemacht.
```

> 2. Nein, du musst dich noch gedulden. `[ENDE]`


```yml
Kansa: Wir haben Zeit.
```

## NPCs

### Kansa

Der Lagerarbeiter Kansa ist ein sehr ruhiger und geduldiger Geselle, trotz das Agnatus auf dem Weg ist, sagt er dem Spieler das man viel Zeit hat.

#### Standartsätze

##### Vor der Quest

1. Jemand sagte einmal "In der Ruhe liegt die Kraft", dass war ein sehr weiser Mann.  
2. Ich mag diese Hektik wegen diesem Agnatus nicht.

##### Während der Quest

1. Lasst euch Zeit mit dem beschaffen der geforderten Materialien, Agnatus ist sicher noch weit entfernt.

##### Nach der Quest

1. Das Lager ist dank dir nun wieder etwas voller, doch ob wir dieses Lager noch lange nutzen ist fraglich.  
2. Sag, bist du auch so ein begeisterter Angler wie Kaptiän Mafei, denn du hattest die Fische ziemlich schnell gefangen.

#### Ausrüstung

#### Standort

```yml
x: 85
y: 82
z: -88
world: Ankanor
```

## Items

### Schwarzer Barsch

Ist durch Angeln in diversen Gewässern zu finden, kann weiterverarbeitet werden.

```yml
name: Schwarzer Barsch
type: ROHSTOFF
quality: COMMON
item: RAW SALMON
lore: Ein gewöhnlicher Fisch der fast überall in zu fangen ist.
max-stack-size: 64
```

### Geschorene Wolle

Normale Wolle die von einem Schaf geschoren wurde.

```yml
name: Geschorene Wolle
type: QUEST
quality: COMMON
item: WOOL
lore: Frisch geschorene Wolle, stinkt und ist fusselig.
max-stack-size: 64
```

### Frischer Eimer Milch

Dieser Eimer Milch ist von einer gewöhnlichen Kuh gemolken.

```yml
name: Frischer Eimer Milch
type: ROHSTOFF
quality: COMMON
item: MILK BUCKET
lore: Diese frische Milch im Eimer ist noch ganz warm.
max-stack-size: 1
```

### Roter Apfel

Ein gewöhnlicher roter Apfel

```yml
name: Roter Apfel
type: FOOD
quality: COMMON
item: APPLE
lore: Ein frischer, knackiger Apfel.
max-stack-size: 64
```

## Mobs

### Skelett

> Nicht vorhanden

## Belohnung

[Hilf dem Lagerarbeiter](#hilf-dem-lagerarbeiter)
> 5 Heller  
> 5 exp  
> 2 [Rote Äpfel](#Roter-Apfel)

## Referenzen
