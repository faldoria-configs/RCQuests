# Die Reise beginnt <!-- omit in toc -->

Nun hat der Spieler die Erlaubnis und den Segen seiner Leute und geht zu Elius, der ihn mitnimmt nach Jarmundshain.

- [Vorrausetzungen](#vorrausetzungen)
- [Aufgaben](#aufgaben)
    - [1. Die Reise beginnt](#1-die-reise-beginnt)
- [NPCs](#npcs)
    - [Elius](#elius)
        - [Standartsätze](#standartsätze)
            - [Vor der Quest](#vor-der-quest)
            - [Während der Quest](#während-der-quest)
            - [Nach der Quest](#nach-der-quest)
        - [Ausrüstung](#ausrüstung)
        - [Standort](#standort)
- [Items](#items)
- [Mobs](#mobs)
- [Belohnung](#belohnung)
- [Referenzen](#referenzen)

## Vorrausetzungen

[HQ Die Erlaubnis](../3-die-erlaubnis/README.md) - Abgeschlossen

## Aufgaben

### 1. Die Reise beginnt

Spieler spricht NPC Elius an.

```yml
Spieler: Meister Elius ich bin nun bereit mit euch zu kommen, wie weit seid Ihr mit dem Ballon?
Elius: Da seid Ihr ja wieder, gerade rechtzeitig. Wir können gleich los. Zunächst aber...
Spieler: Was denn? Was denn nun noch?
Elius: Es ist wichtig das Ihr versteht, dass wir nicht so schnell zurück kommen. Habt Ihr Euch ausgerüstet? Habt Ihr Proviant eingepackt?
Spieler: Ja ich denke ich habe alles.
Elius: Habt Ihr hier alle Aufgaben erledigt? 
```

> 1. Vielleicht sollte ich doch nochmal ein wenig herum schauen ob ich noch etwas zu tun finde.
> 2. Ja Meister Elius, ich bin bereit, nun mit euch zu kommen. Lasst uns losfahren.

**Weiter nach #1:**

```yml
Elius: Dann komme zu mir zurück sobald du bereit bist.
```

Spieler erledigt, was er erledigen möchte und spricht Elius wieder an.

```yml
Spieler: Nun sollte ich entgültig alles erledigt haben.
Elius: Seid ihr euch sicher? Wir können auch noch ein bisschen warten.
```

> Ja, ich bin mir sicher! `Nächster Schritt: Weiter nach #2:`  
> Nein, ich bin mir noch immer nicht sicher.

**Weiter nach #2:**

```yml
Elius: Na dann auf geht die Reise, ich hoffe ich muss nicht wieder notlanden und wir kommen heil in Jarmundshain an.
Spieler: Das hoffe ich doch auch.
```

Teleport

```yml
x: 495
y: 117
z: -1973
world: Faldoria .Frostak_Hochebene.Jarmundshain
```

`[QUEST UPDATE]` [Die Reise beginnt](#1.-die-reise-beginnt)
**QuestLog:** *Sprich mit Elius und höre was für eine Aufgabe er für dich hat.*

Elius spricht Spieler an.
```yml
Eluis: Noch rechtzeitig sicher gelandet.
Spieler: Wollten wir wirklich hier hin? Hier ist es ja noch kälter.
Elius: Ja hier wollten wir hin, ich hab den Brennstoff gerade noch so richtig eingeschätzt, weiter kommen wir nun nicht mehr.
```

`[QUEST ENDE]` [Die Reise beginnt](#1.-die-reise-beginnt) und erhält [Belohnung](#belohunung) 

## NPCs

### Elius

Er ist ein älterer Jorgendder und der eigentliche Großmeister der Gamos Historia. Mehr zu ihm im [Lore Dokument](https://onedrive.live.com/view.aspx?resid=D0C59DCD5578741F!1923&ithint=file%2cdocx&app=Word&authkey=!AAKBdECuqapbsOM).

#### Standartsätze

##### Vor der Quest

Nicht vorhanden

##### Während der Quest

Nicht vorhanden

##### Nach der Quest

Nicht vorhanden

#### Ausrüstung

Buch in der Hand

#### Standort

```yml
x: 3381
y: 125
z: -2664
world: faldoria.eisenküste
```

## Items

keine

## Mobs

Keine

## Belohnung

[Reparaturarbeiten](#1.-die-reise-beginnt)
> 30 Heller  
> 20 exp 

## Referenzen


