# Sandflohkleber <!-- omit in toc -->
Issue #96

## Noch zu tun/Probleme

Standort, Skin, Satz ergänzen: ` Vor der Quest

## Ablauf

1. Der Spieler nähert sich Angunt
2. NPC [Angunt](#Angunt) ruft dem Spieler zu, dass er Hilfe braucht
3. Spieler nimmt an.
4. Angunt gibt ihm die Aufgabe [Mobs Sandflöhe](#Sandflöhe) zu töten, bis er 10 Kleber hat.
5.  `Questbeginn:`[Sandflohkleber](#sandflohkleber)
6. Spieler kehrt zurück und erhält eine [Belohnung](#Belohnung)
   
## Übersicht

## Vorraussetzungen

HQ [Einübung der Waffe](../../5-einübung-der-waffe/ReADME-md) angenommen

## Aufgaben

### `Dialog 1`

Angunt ruft dem Spieler schon von Weitem zu (7 Blocks):   

**Angunt:** `Hey, Jungspund, ich brauche dich mal. Du musst mir mit den Sandflöhen helfen!`      
Wozu musst du Sandflöhe platt machen, wenn alle zusammen helfen, damit wir das Schiff fertig bekommen?            
**Angunt:** `Schlaumeier, der Kapität braucht Kleber oder Teer für die Schiffsplanken, deshalb bemühe ich mich so. Aber die Biester sind heute aufgebracht. Wahrscheinlich hat sich eine Königin eingenistet.`      
Oder es sind auch schon Atagnus Ausdünstungen, die sie spüren.      
**Angunt:** `Hä, was meinst du? Egal, ich sehe, du hast ja eine Waffe, dann wird es dir ein Einfaches sein, mir so ungefähr genau 10 Kleber zu besorgen.`   

1. Sandflöhe? Kein Problem!
   
###  `[QUEST START]` [Sandflohkleber](#sandflohkleber)

2. Also ne, das soll das Erste sein, an dem ich meine Waffe ausprobiere? Da komme ich lieber später wieder. `[Ende]`




## NPCs

## `Agunt`

Er ist ein neugieriger Kaishi, der sehr viel über Pflanzen und Tiere weiß. Ständig ist er unterwegs und wandert auf der Insel herum.


## Standartsätze  
#### Vor der Quest
`Grüß dich, was bringt dich des Weges? Hast du schon das ... (je nach dem, wo er steht) da drüben gesehen, das ist ausgesprochen interessant, das ist bestimmt eine neue Variation, die Blätter sind nämlich etwas mehr geschlitzt als sonst ... du bist nicht dran interessiert? Schade..`
#### Während der Quest  
**Agunt:** `Nun, hast du schon genug vom Kleber?`   
Nein, noch nicht ganz, die Viecher sind doch etwas zäher, als ich dachte.   
**Agunt:** `Na, dann hopp, hopp, sonst wird das nie was mit dem Schiff.`   
Ich tue mein Bestes!

#### Nach der Quest
 **Agunt:** `Gut gemacht, aber was willst du noch hier? Hattest du es nicht eilig? Ich komme auch schon gleich.`

### Ausrüstung
Skin
Stock in der Hand
### Standort

```yml
x: 
y: 
z: 
world: ankanor
```
## Items

### Sandflohkleber

```yml
ID: 351:8
name: Sandflohkleber
type: QUEST
quality: COMMON
item: gray_dye
lore: max-stack-size: 16
```



## Mobs

### Sandfloh

name: Sandfloh
type: silverfish
min-level: 1
max-level: 2
min-health: 80
max-health: 88
min-damage: 3
max-damage: 5
elite: false
spawn-chance: 1.0
passive: false
baby: false
reset-health: true
ranged: false
rare: false
spawn-radius: 50
spawning-naturally: false
aggro: true


## Belohnung

Geld, XP

## Referenzen
## Issues


