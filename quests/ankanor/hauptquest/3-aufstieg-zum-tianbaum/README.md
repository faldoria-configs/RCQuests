# Aufstieg zum Tianbaum

Der Spieler hat nun auch die Vorräte für das Schiff gesammelt und soll nun zurück zu Roschik um sich weiter vorzubereiten. Dies soll er tun in dem er in die Krone des Tianbaumes geht um dort seinen Pfad zu wählen. Auf dem Weg zur Krone trifft er noch einen Wächter.

## Ablauf

1. Start: Der Spieler wird von [Kapitän Mafei](#kapitän-mafei) zurück zu Roschik geschickt.
2. Dort bekommt er die Aufgabe hinauf in die Baumkrone zu gehen. 
3. Auf der anderen Seite des Baumes wo der Eingang zum Weg hinauf ist, steht ein Wächter welcher den Spieler kurz aufhält.
4. Spieler steigt den Tianbaum hinauf und spricht mit Lious.

## Vorraussetzungen

> 1. Erledigen der [HQ Vorräte für das Schiff](../2-vorraete-fuer-das-schiff/README.md)

## NPCs

### Roschik

Er ist der Bürgermeister des Dorfes in dem die Kaishi wohnen. Roschik ist ein sehr gütiger Kaishi und wird von allen Respektiert.

### Dialoge

#### Standartsätze  

**Vor der Quest**
1. Nicht vorhanden

**Während der Quest**  
1. Du solltest dich sputen und den Tianbaum hinauf gehen. Dort ist deine nächste Aufgabe.

**Nach der Quest**
1. Du hast also deinen Pfad gewählt, ich bin stolz auf dich und bin sicher, du wirst eines Tages diese Welt zu einer besseren machen.
    
#### Quest Dialog

##### Aufstieg zum Tianbaum 1

```yml
Roschik: Sehr gut. Nunja,  jetzt musst du dich selbst vorbereiten.
Spieler: Wie meinst du das? Soll ich mein Haus sauber machen?
Roschik: Nein Dummkopf, es könnte zum Kampf kommen und darauf musst du dich vorbereiten. 
Spieler: Was muss ich tun?
Roschik: Steige den Tianbaum hinauf, dort wirst du jemanden treffen der dich unterrichtet.
Spieler: Wie ihr wollt, ich werde zur Krone des Baumes hinauf steigen.. 
```

> 1. Spieler: Wie ihr wollt, ich werde zur Krone des Baumes hinauf steigen.. `[QUEST START]` [Aufstieg zum Tianbaum](#aufstieg-zum-tianbaum)  
**Questlog**: *Folge den Weg um den Tianbaum herum auf die andere Seite, triff den Wächter des Heiligtums und steige den Tianbaum hinauf. **Dort wird dir Lious weiterhelfen** *

> Weiter bei [NPC Wächter](#aufstieg-zum-tianbaum-2)

#### Ausrüstung

#### Standort

```yml
x: 100
y: 82
z: -85
world: Ankanor
```

### Wächter des Heiligtums

Der Wächter des Heiligtums ist dazu aufgefordert niemanden den Baum hinauf zu lassen und dies meint er sehr ernst.

### Dialoge

#### Standartsätze  

**Vor der Quest**  
Wenn Spieler die benötigte Quest noch nicht hat und sich dem Eingang zum Baum nähert passiert folgendens
```yml
Genam: Du bist noch nicht soweit diesen Weg zu beschreiten.
```
Spieler wird außerdem nach folgenden Koordinaten teleportiert.
```yml
x: 3
y: 94
z: 84
world: Ankanor
``` 

**Während der Quest**  
1. Du musst großes Vertrauen genießen das du dort hoch darfst. Oder es ist Dummheit!
2. Pass auf deine Füße auf, nicht das du stolperst und hinunter fällst.

**Nach der Quest**
1. Auch wenn ich diesen Pfad schon lange bewache, ich war noch nie am Ende dieses. Ich hoffe das ich dort eines Tages hinauf darf.
    
#### Quest Dialog

##### Aufstieg zum Tianbaum 2

```yml
Wächter: Halt! Was ist dein Begehr?
Spieler: Ich soll den Tianbaum hinauf steigen und dort mit jemanden reden.
Wächter: Wer hat dir das aufgetragen?
Spieler: Bürgermeister Roschik. Es ist von höchster Wichtigkeit, sagte er.
Wächter: Hmmm… Sagte er auch, warum du dort hinauf sollst?
Spieler: Nein, nur das ich jemanden treffen soll. Er sagte, es wird zum Kampf kommen.
Wächter: In diesem Fall darfst du passieren. Sei vorsichtig, dass du nicht runterfällst!
Spieler: Hab Dank!
```

Spieler betritt den Baum und erhält einen Buff.
> Speed 20% 3 Minuten

> Weiter bei [NPC Lious](#aufstieg-zum-tianbaum-3)

#### Ausrüstung

> Hält einen Bogen in der Hand

#### Standort

```yml
x: 11
y: 95
z: 79
world: Ankanor
```

### Lious

Lious ist der Geist eines Verstorbenen Helden, er ist eine Art Schutzpatron für die Kaishi geworden.

### Dialoge

#### Standartsätze  

**Vor der Quest**
1. nicht vorhanden

**Während der Quest**  
1. nicht vorhanden

**Nach der Quest**
1. nicht vorhanden
    
#### Quest Dialog

##### Aufstieg zum Tianbaum 3

```yml
Lious: Willkommen im in der Krone des Tianbaumes.
Spieler: Was bedeutet das alles? Roshik sprach von einem Pfad? Was kann ich wählen?
Lious: Übe dich in Geduld, junger Kaishi. Ich bin Lious, du solltest mir nun gut zuhören.
Spieler: Ich glaube wir haben aber keine Zeit für lang anhaltende Geduld.
Lious: Wir haben alle Zeit die wir benötigen, damit du deine Wahl treffen kannst, die dein restliches Leben bestimmen wird.
```
> `[QUEST ENDE]` [Aufstieg zum Tianbaum](#aufstieg-zum-tianbaum) und erhält
[Belohnung](#Belohnung)

> Weiter bei [Klassenwahl](../4-klassenwahl/README.md)

#### Ausrüstung

#### Standort

```yml
x: 9
y: 183
z: 21
world: Ankanor
```

## Items

nicht vorhanden

## Mobs

nicht vorhanden

## Belohnung

[Aufstieg zum Tianbaum](#aufstieg-zum-tianbaum)  
> 5 Heller  


## Referenzen

Vorquest: [Ein neuer Start](../2-vorraete-fuer-das-schiff/README.md)  
Folgequest: [Klassenwahl](../4-klassenwahl/README.md)