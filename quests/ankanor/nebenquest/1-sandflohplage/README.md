# Sandflohplage

An der südlichen Küste der Insel hat sich eine Königin von [Mobs Sandflöhen](#Sandflöhe) eingenistet und diese sind nun sehr Aggressiv, der Spieler soll die Sandflöhe für Angunt töten.

## Ablauf

1. Start: Spieler nähert sich Angunt
2. Spieler spricht [NPC Angunt](#Angunt) an welcher ihm die Aufgabe gibt 15 [Mobs Sandflöhe](#Sandflöhe) zu töten `Questbeginn:`[Sandfloh Plage](#sandfloh-plage)
3. Spieler kehrt zurück und erhält eine [Belohnung](#Belohnung)

## Vorrausetzungen

> 1. Erledigen der [HQ Klassenwahl](../../hauptquest/4-klassenwahl/README.md) bzw. es ist das Kämpfen / eine Klasse nötig.

## NPCs

### Angunt

Er ist ein neugieriger Kaishi welcher sehr viel über die Pflanzen und Tiere weiß. Ständig ist wandert er auf der Insel herum. 

##### Standartsätze  

**Vor der Quest**
1. Seid vorsichtig und tretet mir die Pflanzen nicht kaputt.
2. Sandflöhe sind sehr selten Aggressiv, irgendwas muss sie verärgert haben.

**Nach der Quest**
1. Ich hoffe eines Tages nistet sich die Sandflohkönigin woanders ein, es ist ein Graus das wir die Sandflöhe sonst komplett vernichten müssten.
2. Wusstet ihr das Sandflöhe viele Verwandte Arten haben? Zum Beispiel gibt es noch Kiesflöhe, die sind noch zäher als die Sandflöhe, aber sonst sind sie fast gleich.
    
#### Dialoge

##### Quest Dialog

##### Sandfloh Plage

```yml
Angunt: Hat dich der Bürgermeister geschickt ? Wenn ja dann bist du zur passender Zeit gekommen, wir haben ein Sandfloh Problem.
Spieler: Sandflöhe, das hört sich ekelhaft an.
Angunt: Wahrscheinlich hat sich am Strand eine Königin eingenistet. Deswegen sind sie so aggressiv
Spieler: Wie kann ich helfen?
Angunt: Als erstes könntest du 15 von diesen verdammten Sandflöhen töten.
```
> 1. Sandflöhe? Kein Problem! `[QUEST START]` [Sandfloh Plage](#sandfloh-plage)

`Angunt: Viel Glück!`

> 2. Darauf habe ich keine Lust. `[Ende]`


...


`Angunt: Hast du die 15 Sandflöhe getötet?`

> 1. Ja, es war wie ich schon sagte, kein Problem. `[QUEST ENDE]` [Sandfloh Plage](#sandfloh-plage)

`Angunt: Gute Leistung, das hast du schnell hinbekommen.`

>2. Nein ich bin noch dabei, die sind zäher als gedacht.

`Angunt: Beil dich mit der Aufgabe!`


#### Ausrüstung

#### Standort

```yml
x: 49
y: 70
z: 117
world: Ankanor
```

##Items

## Flohschuppen

Dropt von den Sandflöhen nach dem töten.

```yml
name: Flohschuppe
type: PLUNDER
quality: COMMON
item: COCO BEANS
lore: Eine leicht glänzende Schuppe eines Flohs die zu nichts zu gebrauchen ist.
max-stack-size: 64
```

## Stinkendes Fleisch

```yml
name: Stinkendes Fleisch
type: ROHSTOFF
quality: COMMON
item: RAW BEEF
lore: Dieses Fleisch kann man mit den richtigen Gewürzen noch nutzbar machen.
max-stack-size: 64
```

## Mobs

### Sandflöhe (Worldspawn)

```yml
name: Sandfloh
type: silverfish
min-level: 1
max-level: 2
min-health: 80
max-health: 88
min-damage: 3
max-damage: 5
spawn-chance: 1.0
spawning-naturally: false
loot-table: 
aggro: true
```

## Belohnung

[Sandfloh Plage](#sandfloh-plage)
> 8 Heller  
> 5 exp

## Referenzen