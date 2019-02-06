# Unheil am Horizont

Issue #85

Erstes Spawnen der Spielerin auf Ankanor. 
NPCs:
Noroni?

## Noch zu tun/Probleme

## Übersicht


## Ablauf
## Vorraussetzungen

keine / oder Aufforderung im Lobby-Gasthaus angenommen?

## Aufgaben/Ereignisse

**Sobald die Spielerin entweder das erste Mal von der Lobby her kommt oder auch direkt das Spiel betritt:**

# Cinematic!!!Flug um die Insel und durch den Baum 

Wielange?

### `Dialog 1`

@DAvId   
Die Spielerin spawnt in einem kleinen Zimmer, von dem aus sie Zugang zu einer Terrasse mit grandiosem Blick über die Insel hat. Der einzige Weg führt von hier aus nach unten, so dass die Spielerin gezwungen ist, auf die Terrasse zu gehen, um nach unten zu kommen. Auf dem Weg nach unten kann dann Shicho sie irgendwo abfangen.

**Noromi:** `[Name des Spielers], komm raus zu mir, es ist ein wunderschöner Tag heute!`   
*Die helle Stimme deiner Freundin Noromi reißt dich aus deinem Traum. Du schreckst auf und überlegst, ob du ihrer Aufforderung gleich folgen sollst oder erst etwas später und entscheidest dich für später. Erschöpft von der Anstrengung des Fliegens lässt du dich wieder ins Bett sinken.* 

**Noromi:** `[Name des Spielers]! * sehr laut*  Komm  endlich, du Faultier! Shicho wartet unten auf dich. Lass dir nicht zu viel Zeit, er scheint ungeduldig zu sein. Ich gehe schon mal vor uns sage ihm, das du kommst!`     

Bin ja schon unterwegs.. *murmelst du vor dich hin*

*Vielleicht solltest du dich doch auf den Weg machen.*







## NPCs


## `Name des NPCs`

### Standartsätze  


#### Vor der Quest

#### Während der Quest  


#### Nach der Quest
    
### Ausrüstung

Unter diesem Punkt soll angegeben werden welche Art Skin der NPC haben sollte, ob er etwas in der Hand hält oder gar Rüstung trägt.

#### Standort

Der Standort ist die einfache Angabe der Koordinaten des NPCs in einem bestimmten Format. 

```yml
x: 
y: 
z: 
world: faldoria.eisenküste
```

## Items


### Itemname

Nach dem exakten Namen des Items folgt eine kurze Beschreibung des Items, ob es dropt oder verkauft wird, bzw. die Relation zur Quest und wenn das Item schon vorhanden ist folgt die ID des Items. Des Weiteren folgt bei neuen Items eine Auflistung von Parametern in einem bestimmten Format.

```yml
ID: ?
name: Wolfskopf
type: QUEST
quality: RARE 
item: ?
lore: Die Zähne sind immer noch scharf.
max-stack-size: 1
```


Sollte es mehr als ein Item geben wird jedes einzelne getrennt angegeben.

## Mobs

Wie schon bei den Items finden sich hier alle in der Quest vorkommenden Mobs wieder. Ist der Mob schon vorhanden ist der Name und eine Referenz anzugeben, wo der Mob schon mal verwendet worden ist.

### Mobname

Dem Mobnamen folgen in einem bestimmten Format einige Parameter. Zu Beginn sind diese noch spekulativ einzutragen, mit der Zeit allerdings wird es gewisse Vorgaben bzw. Vorlagen geben zu welchem Zeitpunkt welche Parameter nicht über bzw. unterschritten werden sollten.

### Hungriger Wolf

```yml
name: Hungriger Wolf
type: wolf
aggro: true
passive: false
elite: true
min-level: 8
max-level: 8
```
```yml
x: 535
y: 101
z: -2121
world: faldoria.jarmundshain
radius: 5
```


#### Ausrüstung

Unter diesem Punkt kann angegeben werden, sofern dieser Art von Anpassung möglich ist, welche Waffe der Mob in der Hand hält, welchen Skin er haben soll oder welche Rüstungen er trägt.

## Belohnung

Und hey, für das Lesen dieses Markdowns erhälst auch du was.
> 250 Ruf bei `Gott TheFum`  
> Den Titel `Questschreiber GitLord`  
> 3000 EXP für Teammitglied

## Referenzen


## Issues


