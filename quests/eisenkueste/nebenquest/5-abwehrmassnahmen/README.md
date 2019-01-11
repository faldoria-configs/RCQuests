# Abwehrmaßnahmen

Issue 23

NPC: Terry

> **Geändert**

'Junge' entfernt und neutral geschrieben

'Krone' der Kiesfloh Königin ersetzt. Welcher Kiesfloh hat eine Krone?

## Übersicht

- [Abwehrmaßnahmen](#abwehrma%C3%9Fnahmen)
  - [Übersicht](#%C3%BCbersicht)
  - [Ablauf](#ablauf)
  - [Questdialoge](#questdialoge)
  - [Npc](#npc)
    - [Terry](#terry)
      - [Standartsätze](#standarts%C3%A4tze)
        - [Vor der Quest](#vor-der-quest)
        - [Während der Quest: 1. Abwehrmaßnahmen](#w%C3%A4hrend-der-quest-1-abwehrma%C3%9Fnahmen)
        - [Während der Quest: 2. Freie Bahn](#w%C3%A4hrend-der-quest-2-freie-bahn)
        - [Nach der Quest:](#nach-der-quest)
      - [Ausrüstung](#ausr%C3%BCstung)
      - [Standort](#standort)
  - [Items:](#items)
    - [Krone der Kiesflohkönigin](#krone-der-kiesflohk%C3%B6nigin)
  - [Belohnung:](#belohnung)
## Ablauf

1. Der Spieler geht auf Terry zu und spricht ihn an
2. Der Spieler kehrt zurück
3. Freie Bahn - Kiesfloh Königin getötet
4. Spieler kehrt zurück



##Voraussetzungen

lvl

Ausrüstung

Waffe

## Questdialoge

```yml
Spieler: Hallo Terry, hast du Arbeit für einen mutigen Kaishi?
Terry: Seh' ich so aus als hätte ich jemanden Mutiges nötig? - er kratzt sich hinter dem Ohr - 
Terry: Außerdem siehst du eher wie ein Grünschnabel aus.
Spieler: Naja...
Terry: Aber wenn du wirklich Arbeit brauchst, dann habe ich eine Aufgabe für dich.
Spieler: Ich mache im Moment alles. Also, worum gehts?
Terry: Unser Lager wird seit letzter Nacht ständig von diesen ekelerregenden Kiesflöhen angegriffen. Unsere Leute haben was anderes zu tun als dieses Viezeug fernzuhalten.  Aber es hindert die Fischer, ihrer Arbeit nachzugehen. Deshalb sollst du ihnen einen ernsthaften Schlag verpassen.
Terry: Töte genug von ihnen, damit eingeschüchtert sind und fernbleiben.
Und bitte beeile dich, denn wir sind auf den Fisch angewiesen. Nimm dich aber in Acht, sie mögen klein sein, aber sie greifen in Scharen an.
```

> 1. Spieler: Sandflöhe, tut mir leid, die sind nicht so meins. `[Ende]`

> 2. Spieler: Keine Sorge, das werde ich schon schaffen.

`[Quest START]` [1. Abwehrmaßnahmen](#abwehrmassnahmen)

`**QuestLog:**` *Töte fünfzehn [15] Kiesflöhe*

Spieler begibt sich zum Strand tötet 15 Kiesflöhe `[Ende]`

und kehrt zu Terry zurück.

`[Quest START]` [2. Kehre zu Terry zurück](#kehre-zu-terry-zurueck)


```yml
Terry: Hast du alles Benötigte?
Spieler: Klar, was dachtest du denn. 
Terry: Wunderbar, aber es gibt ein Problem. Die Kiesfloh Königin hat bemerkt, dass du ihre Jungen angegriffen hast und randaliert am Strand.
Spieler: Inwiefern behindert uns das?
Terry: Niemand traut sich mehr hin.  Wir können so nicht mit den Arbeiten beginnen.
Spieler: Ich werde sehen was ich tun kann.
Terry: Vielen Dank.
Terry: Aber warte - man sagt, sie hat etwas auf dem Kopf, was wie eine Krone aussieht. Wenn möglich, bringe mir das. Vielleicht können wir das als Abschreckung benutzen.
Spieler: Wo finde ich sie?
Terry: Sie hat ihr Versteck in Richtung Norden. Du wirst sie kaum übersehen.
- Du bist schon am Gehen, als Terry dich zurückhält - 
Terry: Warte noch, das hier könntest du brauchen.
```
> Spieler erhält Gesundheitstrank [Heilung?] und/oder Stärketrank [Stärke?]

```yml
Terry: Nehm dich in Acht, junge Kaishi.
Spieler: Keine Sorge, ich bin bald zurück.
```

`[Quest START]` [Freie Bahn](#freie-bahn)

`**QuestLog:**` *Töte die Kiesfloh Königin*

Spieler begibt sich zur Königin und tötet sie. 
Die Königin droppt [Goldener_Helm]

`[Ende]`

`[Quest START]` [2. Kehre zu Terry zurück](#kehre-zu-terry-zurueck)


```yml
Terry: Ich danke dir, vielleicht bist du ja doch kein Grünschnabel. - lacht -
Spieler:  - du grinst ihn nur an - 
NPC: Deine Bemühungen bleiben nicht unbelohnt. Hier nimm das, du brauchst sie nötiger als ich. 
Spieler: Dankeschön!
```

`[Ende]`



## Npc

### Terry

Beschreibung!

#### Standartsätze 

##### Vor der Quest

*Terry brummelt vor sich hin und nimmt dich nicht wahr*

##### Während der Quest: 1. Abwehrmaßnahmen

> 1.  Nun, schon zurück? Du bist schon fertig? Nein? Doch ein Grünschnabel? - lacht - 

> 2.  Terry: Was, du bist schon fertig?
      
      Spieler: Leider nein, ich brauchte eine Pause.
      Terry: Ja, die Viecher darf man nicht unterschätzen. 

##### Während der Quest: 2. Freie Bahn

> 1. Terry: Sag bloß, du hast die Königin schon erledigt? 
     Spieler: Nein, sie war mir zu stark, ich musste rennen. Hast du noch einen Heiltrank für mich? Dann probiere ich es nochmals.


     ----> Spieler erhält nochmals einen Heiltrank, wenn er keinen mehr im Inventar hat. 

##### Nach der Quest: 

> Hey, Kiesflohjäger, auf dem Weg zu neuem Ruhm?

> Na, <Name des Spielers>, welche Pläne hast du?

> Na, <Name des Spielers>, welche Pläne hast du?

#### Ausrüstung 

...........


#### Standort

```yml
x: 3656
y: 65
z: -2809
world: Faldoria, Eisenküste

``` 

## Items:

### Krone der Kiesflohkönigin

```yml
name: Krone der Kiesflohkönigin
type: QUEST
quality: COMMON
item: golden_helmet
lore: Die Krone einer verwunschenen Prinzessin.
max-stack-size: 1
```


## Belohnung:

3 Heiltränke





















