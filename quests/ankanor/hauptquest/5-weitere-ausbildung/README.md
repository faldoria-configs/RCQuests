# Weitere Ausbildung

Lious schickt den Spieler nach der Klassenwahl wieder hinunter zum ältesten Jamos, dieser erklärt dem Spieler er solle den Bewohnern der Insel helfen. Nachdem er das getan hat, sind Agnatus Schergen auf der Insel angekommen und der Spieler soll zum Schiff welches am Dorf liegt und mit Kapitän Mafei reden.

- [Weitere Ausbildung](#weitere-ausbildung)
    - [Vorrausetzungen](#vorrausetzungen)
    - [Aufgaben](#aufgaben)
        - [1. Weitere Ausbildung](#1-weitere-ausbildung)
        - [2. Verteidige Ankanor](#2-verteidige-ankanor)
            - [Möglichkeit 1](#m%C3%B6glichkeit-1)
            - [Möglichkeit 2](#m%C3%B6glichkeit-2)
    - [NPCs](#npcs)
        - [Lious](#lious)
            - [Standartsätze](#standarts%C3%A4tze)
                - [Vor der Quest](#vor-der-quest)
                - [Während der Quest](#w%C3%A4hrend-der-quest)
                - [Nach der Quest](#nach-der-quest)
            - [Ausrüstung](#ausr%C3%BCstung)
            - [Standort](#standort)
        - [Ältester Jamos](#%C3%A4ltester-jamos)
            - [Standartsätze](#standarts%C3%A4tze)
                - [Vor der Quest](#vor-der-quest)
                - [Während der Quest](#w%C3%A4hrend-der-quest)
                - [Nach der Quest](#nach-der-quest)
            - [Ausrüstung](#ausr%C3%BCstung)
            - [Standort](#standort)
        - [Kapitän Mafei](#kapit%C3%A4n-mafei)
        - [Dialoge](#dialoge)
            - [Standartsätze](#standarts%C3%A4tze)
            - [Ausrüstung](#ausr%C3%BCstung)
            - [Standort](#standort)
    - [Items](#items)
        - [Abgetragene Hose](#abgetragene-hose)
    - [Mobs](#mobs)
        - [Agnatus Schergen](#agnatus-schergen)
    - [Belohnung](#belohnung)
    - [Referenzen](#referenzen)

## Vorrausetzungen

> 1. Erledigen der [HQ Klassenwahl](../4-klassenwahl/README.md)

## Aufgaben

### 1. Weitere Ausbildung

> Konversation angeknüpft an Vorquest [HQ Klassenwahl](../4-klassenwahl/README.md)

```yml
Lious: Gehe nun zu Ältester Jamos.
Spieler: Darf ich den verprügeln?
Lious: Ich glaube dir fehlt eine Tracht Prügel. Nein, er wird deine weitere Ausbildung überwachen.
Spieler: Ok ich werde ihn aufsuchen.
```

`[QUEST START]` [Weitere Ausbildung](#weitere-ausbildung))
> **QuestLog:** *Gehe zum Ältesten Jamos und sprich mit ihm, er steht unten am Weg nahe des Zugangs zum Tianbaum.*

```yml
Spieler: Ältester Jamos ich soll mich bei dir melden für weitere Ausbildung.
Jamos: Waaas? Du willst etwas hören über die Helden der Graupilzburg? Was ist das denn?
Spieler: Oh mann.
Jamos: Junger Mann, das war ein Scherz! Deine Weitere Ausbildung besteht darin nun den Bewohnern der Insel zu Helfen. Du bist nun ein Kaishi mit besonderen Fähigkeiten, nutze sie!
``` 

`[QUEST UPDATE]` [Weitere Ausbildung](#weitere-ausbildung)
> **QuestLog:** *Hilf den Bewohnern von Ankanor: 
> - Hilf dem Schmied
> - Hilf beim ausmerzen der Sandflöhe
> - Hilf bei der Höhle der Skelette*

> Um nun weiterzukommen soll der Spieler folgende Quests erledigt haben.
> - [Skelette in der Höhle](../../nebenquest/3-skelette-in-der-hoehle/README.md)
> - [Hilf in der Schmiede](../../nebenquest/4-hilf-in-der-schmiede/README.md)
> - [Sandflohplage](../../nebenquest/1-sandflohplage/README.md)

```yml 
Jamos: Ich hörte du hast den Bewohnern gut geholfen, gerade zur rechten Zeit.
Spieler: Warum was ist nun schon wieder?
Jamos: Agnatus Truppen wurden gesichtet. Wir brauchen dich sofort am Rand des Dorfes. 
Spieler: Wie? Was? Jetzt schon? Ich dachte ich werde noch weiter ausgebildet.
Jamos: Dies ist Teil deiner Ausbildung und nun verliere keine Zeit, lauf ins Dorf versuche dann zum Schiff zu kommen. Ich komme nach!
```

> 1. Ok, pass auf dich auf Alterchen.  
**Teleport:
```yml
x: -62
y: 80
z: 70
world: Ankanor-Event
```

### 2. Verteidige Ankanor
> **QuestLog:** *Laufe zum Dorf, schlage die Angreifer zurück und triff Bootsmann Klisur auf dem Schiff.*

Spieler hat zwei Möglichkeiten nun zur Eisenküste zu kommen, je nachdem wie er es löst ändert das im folgenden auch die Konversationen an der Eisenküste.

#### Möglichkeit 1

Der Spieler tötet unzählige [NPC Agnatus Scherge](#agnatus-scherge) bis er auf dem Schiff im Dorf ankommt und Kapitän Mafei anspricht.

```yml
MAfei: Ihr habt es geschafft, fast alle sind an Bord, wir müssen auch los.
Spieler: Aber, was ist mit unserer Heimat?
Mafei: Wir müssen sie aufgeben, vielleicht kehren wir eines Tages zurück.
Spieler: Wo segeln wir nun hin? 
Mafei: In den Westen.
```

> **Achievement:** Unversehrter Kaishi - *Erreiche die Eisenküste ohne von Agnatus Schergen ausgeknockt worden zu sein.*

**Teleport:
```yml
x: 3663
y: 64
z: -2820
world: Faldoria
```

`[QUEST ENDE]` [Weitere Ausbildung](#weitere-ausbildung) erhält [Belohung](#belohnung)

#### Möglichkeit 2

Der Spieler tötet unzählige [NPC Agnatus Scherge](#agnatus-scherge) wird aber von den Monstern ausgeknockt(getötet).

**Teleport:
```yml
x: 3667
y: 64
z: -2821
world: Faldoria
```

`[QUEST ENDE]` [Weitere Ausbildung](#weitere-ausbildung) erhält [Belohung](#belohnung)

## NPCs

### Lious

Lious ist der Geist eines Verstorbenen Helden, er ist eine Art Schutzpatron für die Kaishi geworden.

#### Standartsätze

##### Vor der Quest

1. nicht vorhanden

##### Während der Quest

1. Habt ihr schon den Worten der Ritualsteine gelauscht? Es ist wichtig das ihr genau zuhört.

##### Nach der Quest

1. Jamos wird euch weiterleiten auf eurem Pfad, verschwendet also keine Zeit.
2. Aus großer Macht folgt große Verantwortung!

#### Ausrüstung

#### Standort

```yml
x: 9
y: 183
z: 21
world: Ankanor
```

### Ältester Jamos

Der Jamos ist der älteste Kaishi, er fungiert als Berater für jeden Bewohner. Mit der Zeit hat er sich immer mehr zurück gezogen, deshalb ist er Tagsüber eher außerhalb des Dorfes anzutreffen.

#### Standartsätze

##### Vor der Quest

1. [Spielername], in meinem Alter...
2. Es ist die Zeit für einen Umbruch, die Kaishi werden einer harten Prüfung unterzogen.

##### Während der Quest

1. Helft unserem Volk mit deinen neuen Fähigkeiten. Frag herum welcher Bewohner hilfe bei etwas braucht.

##### Nach der Quest

1. nicht vorhanden

#### Ausrüstung

#### Standort

```yml
x: 60
y: 80
z: 72
world: Ankanor
```

### Kapitän Mafei

Der Kapitän ist ein ambitionierter Angler der ziemlich schnell genervt ist.

### Dialoge

#### Standartsätze  

**Vor der Quest**
1. nicht vorhanden

**Während der Quest**  
1. siehe [Quest Dialog](#möglichkeit-1)

**Nach der Quest**
1. nicht vorhanden

#### Ausrüstung

> Hält einen Bogen in der Hand

#### Standort

```yml
x: -6
y: 67
z: -101
world: Ankanor-Event
```

## Items

### Abgetragene Hose

```yml
name: Schwarzer Barsch
type: RÜSTUNG
quality: COMMON
item: LEATHER PANTS
lore: Ein Wunder das diese Hose überhaupt noch hält.
max-stack-size: 1
```

## Mobs

### Agnatus Schergen

```yml
name: Agnatus Schergen
type: zombie
min-level: 2
max-level: 4
min-health: 80
max-health: 88
min-damage: 6
max-damage: 10
spawn-chance: 1.0
spawning-naturally: false
loot-table: 
aggro: true
```

## Belohnung

[Weitere Ausbildung](#weitere-ausbildung)
> 10 Heller  
> 20 exp  
> [Abgetragene Hose](#abgetragene-Hose)

## Referenzen
