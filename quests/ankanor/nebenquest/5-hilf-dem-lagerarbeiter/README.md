# Der Lagerarbeiter

[NPC Kansa](#Kansa) steht im Lager an der Versammlungshalle, weil sich das Lager langsam leer soll der Spieler dieses wieder füllen. Kansa bittet ihn Wolle, Äpfel, Fisch und Milch zu besorgen.

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

> 1. Keine

## NPCs

### Kansa

Der Lagerarbeiter Kansa ist ein sehr ruhiger und geduldiger Geselle, trotz das Agnatus auf dem Weg ist, sagt er dem Spieler das man viel Zeit hat.

Standartsätze:
    1. Jemand sagte einmal "In der Ruhe liegt die Kraft", dass war ein sehr weiser Mann.
    2. Ich mag diese Hektik wegen diesem Agnatus nicht.
    
#### Dialoge

##### Quest Dialoge

##### Hilf dem Lagerarbeiter

```yml
NPC: Hey, [Name des Spielers], Hast du mal nen Moment? Könntest du nicht zufällig etwas für mich erledigen?
Spieler: Was soll ich denn tun?
NPC: Nun, die Lager sind so gut wie leer und ich brauche Hilfe beim einholen der Rohstoffe. Könntest du für mich die Schafe im westen scheren und eine Kuh melken? Außerdem brauche ich noch ein paar Schwarze Barsche und Äpfel.
```
> 1. Na klar! Du kannst auf mich zählen.
`[QUEST START]` [Hilf dem Lagerarbeiter](#hilf-dem-lagerarbeiter)
**QuestLog:** *Sammle 10 Äpfel, angel 3 Schwarze Barsche und schere Schafe für 5 Wolle und melke eine Kuh. Schafe und Kühe findest du auf der Weide im westen. Äpfel sind überall auf der Insel zu finden. Barsche findest du hier in allen Gewässern.*

> 2. Nein, ich habe besseres zu tun…`[Ende]`

> Spieler sammelt alle Materialien und kehrt zum Questgeber zurück

```yml
NPC: Hast du die Sachen?
```
> 1. Ja habe ich. `[QUEST ENDE]` [Hilf dem Lagerarbeiter](#hilf-dem-lagerarbeiter) und erhält [Belohnung](#Belohnung)

`Kansa: Super!`

```yml
NPC: Danke vielmals für die Hilfe!
Spieler: Hab ich doch gern gemacht.
```

> 2. Nein, du musst dich noch gedulden. `[ENDE]`

`Kansa: Wir haben Zeit.`


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

