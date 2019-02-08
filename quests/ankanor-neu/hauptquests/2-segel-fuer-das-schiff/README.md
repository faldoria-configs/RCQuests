# Segel für das Schiff <!-- omit in toc -->
Issue #87

## Noch zu tun/Probleme

## Ablauf

## Übersicht


## Ablauf
1. Start: Spieler bekommt von [NPC Roschik](#Roschik) die Aufgabe [Kapitän Mafei](#kapitän-mafei) zu finden und ihm zu helfen.
2. Spieler geht zum Steg beim Schiff und spricht Mafei an.
3. Dieser gibt ihm verschiedene Aufgaben:
   - Material zur Reparatur des Schiffes aus dem Lager bei der Versammlunghalle zu besorgen.
   - zum Schneider zu gehen und bestellten Stoff für ein neues Segel zu holen
   - Kansa in der Lagerhalle ansprechen. 

## Vorraussetzungen

HQ [Unheil am Horizont](../unheil-am-horizont.md)

## Aufgaben

### `Dialog 1` (Roschik)

**Roschik:** ` Wir werden Vorbereitungen treffen müssen und du musst dabei helfen.`   
Was soll ich tun?    
**Roschik:** `Zuerst müssen wir das Schiff klar machen. Geh und suche den Kapitän, er ist bestimmt an der Küste und angelt.`   
Ich mache mich sofort auf den Weg.   

### **[QUEST START]** [Segel für das Schiff](#segel-fuer-das-schiff-1)  
**Questlog**: *Sprich mit Kapitän Mafei, du wirst ihn an der Küste beim Schiff finden. Folge seinen Anweisungen und kehre dann zu Roschik zurück.*

**Weiter bei [NPC Kapitän Mafei](#kapitän-mafei)**

### Dialog 2 (Mafei)

**Mafei:** ` Und der Tag ist perfekt.`   
Was hast du gesagt Mafei?   
**Mafei:** ` Nichts, sag mir schnell was du willst und geh dann wieder. `   
Roschik schickt mich, du sollst das Schiff klar machen. Irgendwas von Weltuntergang oder so.   
**Mafei:** `Wie bitte? Verarsch mich nicht.`    
Nein, nein ehrlich, Agmagnum, der Nekrodingsda, hat Schiffe in unsere Richtung geschickt.   
**Mafei:** `Wer? Wenn das einer deiner Späße wird, werde ich dich den Fischen zum Fraß vorwerfen.`   
So glaub mir doch, du sollst das Schiff klar machen.   
**Mafei:** `Bei der großen Seeschlange, wer rechnet mit sowas. Gut, dass ich schon vorgesorgt habe, aber es muss noch etliches repariert werden. Dabei kannst du mir behilflich sein. Ich brauche etliches Material zum Reparieren.`   
Na, dann sag schon, ich wachse ja schon hier an.    
**Mafei:** `*schaut dich leicht erzürnt an* `   
**Mafei:** `Also, da wäre mal der Segelstoff, den habe ich schon bei Janis bestellt, dem Schneider gleich da hinter der Brücke. Den brauchst du bloss abholen. Dann wäre da noch die Segelschnur und der Kleber aus dem Lager. Und wenn du schon dort bist, fragst du Kansa, wie es mit den Essensvorräten aussieht. Das wird schon noch etwas Zeit haben.`   
Das ist aber eine ganze Menge!   
**Mafei:** `Was, kannst du dir nicht drei Sachen merken? Los mit dir!`

> Liste einfügen?

### **[QUEST Update]** [Segel für das Schiff](#segel-fuer-das-schiff-2)
**Questlog:** *Hole den Segelstoff bei Schneider Janis, besorge im Lager Segelschnur und Kleber und frage dort Kansa, wie es mit den Essensvorräten steht.*

**Die Spielerin erfüllt nun alle diese Aufgaben und kehrt dann zu Mafei zurück.**

> Schneider ist ein Händler, der aber nicht handelt, der Spieler kann den stoff so nehmen.
> Bei Kansa erhält dann der Spieler eine weitere Quest, die er gleichzeitig machen kann oder auch nicht.

**Mafei:** ` Hast du alles erledigt?`
1. Nein, ich habe noch nicht alles erledigt.   
   **Mafei:**  `   Dann solltest du dich beeilen.`

2. Ja hier hast du sie.   
   **Mafei:** `Vielen Dank! Dann lass dich nochmal bei Roschik sehen,er hat bestimmt noch mehr Aufgaben für dich.`   

**QUEST UPDATE:** [Segel für das Schiff](#segel-fuer-das-schiff)   
**Questlog** *Gehe zurück zum Ältesten Roshik in die Versammlungshalle*


**Spielerin geht zurück zu [Roschik](#roschik)**

Weiter bei [NPC Roschik](#segel-fuer-das-schiff-3)

### Dialog 3 (Roschik)

**Roschik:** ` Hast du Kapitän Mafei über die Situation informiert?`   
Ja, auch wenn er mir anfangs nicht glauben wollte, ich habe sogar geholfen, das Schiff zu reparieren - indirekt.    
**Roschik:** `Das freut mich. Noromi hat einige Kürbiskuchen dagelassen, ich denke, du magst die, nicht wahr?`   
Uhmm, ja, sehr gerne.

**`[Quest Ende]`** [Segel für das Schiff](#segel-fuer-das-schiff)

**Belohnung:**
XP + Kürbiskuchen 



## NPCs


## `Roschik`
Beschreibung ergänzen

### Standartsätze  

#### Vor der Quest
1. Nicht vorhanden
#### Während der Quest  
1. Hast du Mafei gefunden? Er ist sicher am Steg beim Schiff.
#### Nach der Quest
1. Es ist sehr wichtig, dass du keinen Unsinn machst, wir brauchen jeden jetzt um uns vorzubereiten.
2. Ich hoffe du verstehst, dass ich gerade keine Zeit habe für dich
### Ausrüstung
#### Standort

```yml
x: 
y: 
z: 
world: ankanor
```
## `Kapitän Mafei`

### Standartsätze  


#### Vor der Quest

#### Während der Quest  


#### Nach der Quest
    
### Ausrüstung



#### Standort



```yml
x: 
y: 
z: 
world: faldoria.eisenküste
```


## Items


### Itemname

Nach dem exakten Namen des Items folgt eine kurze Beschreibung des Items, ob es dropt oder verkauft wird, bzw. die Relation zur Quest und wenn das Item schon vorhanden ist folgt die ID des Items. 

```yml
ID: ?
name: 
type: QUEST
quality: RARE /COMMON
item: 
lore: max-stack-size: 1
```




## Mobs


### Mobname



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



## Belohnung



## Referenzen


## Issues


