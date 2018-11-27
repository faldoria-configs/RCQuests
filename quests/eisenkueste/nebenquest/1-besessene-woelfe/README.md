# Besessene Woelfe

Im Camp steht [NPC Hauptmann Marduk](#hauptmann-marduk). Er möchte, dass der Spieler aggressive Woelfe für ihn tötet. 

## Ablauf

1. Start: Spieler nähert sich Hauptmann Marduk und wird von ihm angesprochen und gefragt, ob er Arbeit benötige.
2. Der Spieler ist hilfsbereit/unwillig.
3. Hauptmann Marduk versucht, den Spieler zu gewinnen, ihm zu helfen.
4. Der Spieler stimmt zu/lehnt ab. 
5. Hauptmann Marduk schickt den Spieler in den Wald, um die Wölfe zu töten. 

## Vorraussetzungen

>keine Vorraussetzungen
>keine Folgequest  - noch nicht

## Aufgaben

### 1. Besessene Woelfe

Spieler wird von Hauptmann Marduk angesprochen sobald er in der Nähe (3 Blocks) vorbei läuft.

```yml
Hauptmann Marduk: Hey du! Du siehst aus, als könntest du ein wenig Arbeit vertragen!
```

> 1. Wie kann ich dir helfen?  
> 2. Was? Was geht denn dich das an!?

** Weiter nach #2: **

```yml
Hauptmann Marduk: Wenn du nicht auch noch beinahe gefressen werden willst, hörst du mir besser zu.
```

> 3. Worauf willst du hinaus?
> 4. Na gut, was willst du?
> 5. Ich komme schon klar, such dir wen anders. `[Ende]`

**Weiter nach #1, #3, #4:**

```yml
Hauptmann Marduk: Hörzu:Ich habe kein Problem mit Tieren, aber wenn sie eins mit mir haben, ist das sehr wohl ein Problem! 
```
```yml
Hauptmann Marduk: Pass auf, normalerweise halten sich fast alle Viecher von uns fern. Aber hier gibt es Wölfe, die nicht zögern jeden anzugreifen, der ihnen zu nahe kommt. Wer weiß ob da nicht Magie im Spiel ist.
```

> Und ich soll die Wölfe jetzt töten, natürlich. Wo finde ich sie?

```yml
Hauptmann Marduk: Ein Stück südwestlich von hier im Wald ist ein alter Schrein an einer eingestürzten Brücke. Dort in der Nähe haben sie mich schon einmal angegriffen. Schau am besten dort. 
```

> Na schön, ich werde mich um diese Biester kümmern.

```yml
Hauptmann Marduk: Du würdest dem Lager damit sehr helfen! Komm wieder zu mir, wenn du sie erledigt hast.
```

`[QUEST START]` [Besessenen Woelfe](#besessene-woelfe)

> **QuestLog:** Suche die Wölfe südwestlich des Lagers, die sich an der alten Brücke beim Schrein breitmachen, und töte sie.
- Töte [20] Wölfe

*Spieler hat 20 Wölfe getötet und muss dann zum Questgeber zurück kehren.*

> **Questlog:** *Geh zurück zu Hauptmann Marduk und berichte ihm von deinem Erfolg.*


Spieler geht zurück zu Hauptmann Marduk.


```yml
Hauptmann Marduk: Sind die Biester tot?
```

> 1. Ja, sie hatten keine Chance.
> 2. NEIN, das muss ich noch erledigen.


**Weiter nach #1:**

```yml
Hauptmann Marduk: Gut gemacht! Hoffen wir, dass das die einzigen waren.... Nimm dies als Dank. [ENDE]
```

**Weiter nach #2:**

```yml
Hauptmann Marduk: Dann verschwende nicht meine Zeit und mach dich an die Arbeit! 
```


## NPCs

### Hauptmann Marduk

Er nennt sich zwar Hauptmann, es gibt aber eigentlich keine richtigen Truppen bei den Kaishi. Marduk ist ein sehr entspannter Typ, er hat keine Kampferfahrungen, soll sich aber um die Verteidigung kümmern.

#### Standardsätze

**Vor der Quest**  
1.  Keine

**Während der Quest**  
1. Marduk: Nun, sind schon alle Wölfe tot?
   1.1 Spieler: Eh..., noch nicht
   1.2 Nein, leider nicht, wo finde ich die Wölfe?
       Marduk: Ein Stück südwestlich von hier im Wald ist ein alter Schrein an einer eingestürzten Brücke. Dort in der Nähe. 
       
2. Marduk: Das ging aber schnell, gibt's heute Abend Wolfsbraten?
   1.1 Spieler: Eh..., noch nicht
   1.2 Nein, leider nicht, wo finde ich die Wölfe?
       Marduk: Ein Stück südwestlich von hier im Wald ist ein alter Schrein an einer eingestürzten Brücke. Dort in der Nähe.

**Nach der Quest**  
1. Noch nicht genug vom Wölfe jagen? Wie kann man Emotes hinzufügen wie - lacht laut?
2. Ah, sieh da, unser Wolfsjäger! 

#### Ausrüstung

Lederrüstung ohne Helm
Steinaxt in der Hand

#### Standort

```yml
x: 3645
y: 63
z: -2829
world: faldoria
```

## Items
### Itemname

## Mobs
### Mobname
Wolf
#### Ausrüstung

## Belohnung

[Besessene Wölfe](#besessene-woelfe)

> 10 Heller
> 10 XP
> Item: Schwarze Lederjacke, Itemname: Umhang aus Wolfspelz



## Referenzen

## Issues  etc







