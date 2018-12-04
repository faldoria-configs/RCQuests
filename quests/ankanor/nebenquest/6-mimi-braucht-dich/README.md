# Mimi braucht dich

Issue 51


## Ablauf

1. Der Spieler trifft auf Mimi, ein 11-jähriges Waisenkind, das ihn anspricht und um Hilfe bittet.
2. Er soll Mimis Puppe aus dem höchsten Haus auf Ankanor holen.
3. Der Spieler tut das und erfährt als Belohnung ein 'Geheimnis'


## Vorraussetzungen

Keine

## Aufgaben

Der Spieler soll Mimis Puppe aus dem höchstgelegenen Haus von Ankanor holen.

### 1.  Mimi braucht dich (#mimi-braucht-dich)

Mimi sitzt auf der Treppe, die zu den oberen Häusern Ankanors führt und ruft dem Spieler zu, sobald er vorbeikommt: (5 Block oder mehr?)

```yml
Mimi: Hey, <Name des Spielers>, du willst doch sicherlich einem armen kleinen Mädchen helfen? 
- du drehst dich um und siehst auf der Treppe Mimi sitzen, ein etwa 10-jähriges Mädchen, das du vom Sehen her kennst -
Spieler: Was will denn das arme kleine Mädchen von mir? 
Mimi: Ich habe oben im Haus bei Tante Mairi meine Puppe vergessen und ich brauche sie wirklich dringend!
Spieler: Mimi, wieso gehst du denn nicht selber hinauf und holst sie?
Mimi: Aber siehst du denn nicht, dass ich einen wehen Fuß habe?  - Mimi hält dir ihr Bein hin, das mit ein paar losen Stoffstreifen umwickelt ist - 
Spieler: Nein, Mimi, wirklich nicht, ich lass mich von dir nicht auf den Arm nehmen. Geh und hold dir deine Puppe selbst und dann schau, dass du zum Schiff kommst. Weißt du nicht, dass wir alle weg müssen, weil Agnatus und seine bösen Männer kommen? Ich habe jetzt Wichtigeres zu tun. 
Mimi: Ich verrate dir auch ein Geheimnis, wenn du mir hilfst!
```
> 1. Du und deine Geheimnisse, behalte sie für dich selbst! [Ende]

> 2. Du nervst. Aber sag mir, wo deine Puppe ist, ich laufe schnell hoch. 

**Weiter nach #2**

```yml
Mimi: In der Kiste unter der Treppe, die nach oben führt. In dem Haus ganz oben, nicht dort, wo Bürgermeister Roschick wohnt. Danke, <Name des Spielers>, du bist einfach großartig! 
```
---> VLLt Schild am Haus anbringen mit einem Namen - z.B. {Name NPC Eisenküste}, am anderen Mairi

`[Quest START]` [Mimi braucht dich](#mimi-braucht-dich)

**QuestLog:** *Laufe ins oberste Haus von Ankanor, das Mairi gehört, hole die Puppe und kehre zu Mimi zurück.*

Spieler läuft hoch und findet die Puppe in der Kiste, nimmt sie an sich und kehrt zu Mimi zurück. 

```yml
Spieler: Hier hast du deine Puppe, aber jetzt mach dich auf zum Schiff!  
Mimi: Ja, ich lauf' doch schon, aber ich brauchte doch meine Puppe! Da, du kannst die Hälfte meines Plätzchens haben. 
```
----> Mimi gibt dem Spieler ein angebissenes Plätzchen - Spieler hat im Inventar einen Keks der [Angebissenes Plätzchen](#angebissenes-plaetzchen) heißt.

```yml
Spieler: Was, du kannst doch laufen? Na dann los! Aber schnell!
Mimi: Willst du nicht mein Geheimniss wissen?
Spieler: Nun sag schon!!! - du wirkst sehr ungeduldig - 
Mimi:  - Mimi zieht dich zu sich herunter und flüstert in dein Ohr - Junnar nmag dich! 
Spieler: Shichos Schwester? - du wirst rot und sagst sehr unwirsch - Verschwinde! Auf zum Schiff!
 ```
[Ende]

## NPC

### Mimi

Mimi ist ein Kind, das im Alter von ca 3 Jahren auf der Insel Ankanor in einem kleinen Boot angespült wurde, das eigentlich nicht seetauglich war. Sie besaß nichts außer zerissene Kleidung, eine Puppe, ein Amulet um den Hals und etwas Verpflegung. Mairi nahm sie in ihre Familie auf.

Mimi ist inzwischen ein hübsches, rothaariges Mädchen mit einem rundlichen Gesicht und grünen Augen. Meist kleben einige Krümel in ihrem Gesicht, da sie sich trotz Mairies Bemühungen, sie gesund zu ernähren, von Kiakeksen zu leben scheint. Sie ist vom vielen spielen im Freien braungebrannt und liebt es, sich bunte Blumen ins Haar zu flechten.

Gerne trägt sie grüne oder blaue Kleidchen, Schuhe jedoch mag sie nicht, da sie hinderlich beim Klettern im Tianbaum sind. Sie ist für ihr Alter von 10 Jahren ziemlich klein, und erscheint manchen viel jünger als sie wirklich ist. 


### Standartsätze

#### Während der Quest


1. Hast du meine Puppe schon?
2. Hey, wo bleibt meine Puppe!
3. < Name des Spielers >, du schaffst das!
4. < Name des Spielers >, du wirst doch nicht ein kleines Mädchen enttäuschen!



#### Nach der Quest

1. Na, was macht mein Held? 
2. Hey < Name des Spielers > Keine Angst, ich gehe schon rechtzeitig zum Schiff, du bist ja auch noch da. 


+++++

#### Falls die Quest das erste Mal nicht angenommen wurde

1. Na, hast du es dir doch anders überlegt?

```yml
Spieler: Ja, nun sag mir schnell noch mal, wo ich die Puppe finde. 
```

**Weiter nach #2**  --->Interner Link nach oben

### Ausrüstung

 - Skin eines kleinen Mädchens, 
 - hält in der Hand:  ein Plätzchen
 ----> vor der Questabgabe : Plätzchen, danach Puppe? Dazu bräuchte es aber Phasing, oder?)


### Standort

```yml
x: 38
y: 88
z: -32
world: Ankanor
``` 

## Items

### Angebissenes Plätzchen

Ist ein angebissenes Plätzchen, wird nur von Mimi verschenkt.

```yml
name: Angebissenes Plätzchen
type: FOOD
quality: RARE
item: cookie
lore: Dieser Keks ist etwas zerkrümelt.
max-stack-size: 1
```

### Puppe

Puppe aus Stoff und anderen natürlichen Materialien.

Zu finden in Kiste bei --> kann ich grad nicht nachsehen

``yml
x: 18
y: 115
z: -19
world: Ankanor
``` 

```yml
name: Aneli
type: totem
quality: RARE
item: totem_of_undying
lore: Diese Puppe wird sehr geliebt.
max-stack-size: 1
```

## Belohnung

xxx Ruf bei den Kaishi
1 Stack Cookies
5 Exp
1 totem_of_undying   (falls es nicht doch noch eine Quest mit Mimi im Event gibt)


## Referenzen

Link zur ersten Quest, in der Junnar erwähnt wird











