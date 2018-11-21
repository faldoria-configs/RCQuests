# Mimi braucht dich


## Ablauf

1. Der Spieler trifft auf Mimi, ein 10-jhriges Waisenkind, das ihn anspricht und um Hilfe bittet
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
Mimi: Ich habe oben im Haus bei Tante Hilde meine Puppe vergessen und ich brauche sie wirklich dringend!
Spieler: Mimi, wieso gehst du denn nicht selber hinauf und holst sie?
Mimi: Aber siehst du denn nicht, dass ich einen wehen Fuß habe?  - Mimi hält dir ihr Bein hin, das mit ein paar losen Stoffstreifen umwickelt ist - 
Spieler: Nein, Mimi, wirklich nicht, ich lass mich von dir nicht auf den Arm nehmen. Geh und hold dir deine Puppe selbst und dann schau, dass du zum Schiff kommst. Weißt du nicht, dass wir alle weg müssen, weil Agnatus und seine bösen Männer kommen? Ich habe jetzt Wichtigeres zu tun. 
Mimi: Ich verrate dir auch ein Geheimnis, wenn du mir hilfst!
```
> 1. Du und deine Geheimnisse, behalte sie für dich selbst! [Ende]

> 2. Du nervst. Aber sag mir, wo deine Puppe ist, ich laufe schnell hoch. 

**Weiter nach #2**

```yml
Mimi: In der einzelnen Kiste, direkt neben der Treppe, die wieder nach unten zum Schlafzimmer führt. In dem obersten Haus, nicht dort, wo Onkel Fred wohnt. Danke, <Name des Spielers>, du bist einfach großartig! 
```
---> VLLt Schild am Haus anbringen mit einem Namen - z.B. Fred Schreiner, am anderen Hilde Ohnesorg

`[Quest START]` [Mimi braucht dich](#mimi-braucht-dich)

**QuestLog:** *Laufe ins oberste Haus von Ankanor, das Hilde Ohnesorg gehört, hole die Puppe und kehre zu Mimi zurück.*

Spieler läuft hoch und findet die Puppe in der Kiste, nimmt sie an sich und kehrt zu Mimi zurück. 

```yml
Spieler: Hier hast du deine Puppe, kleines armes Mädchen, aber jetzt mach dich auf zum Schiff! Wer weiß, wo Tante Hilde ist. 
Mimi: Sie ist schon dort, sie musste mit helfen und hat gesagt, ich soll nachkommen, aber ich brauchte doch meine Puppe! Da, du kannst die Hälfte meines Plätzchens haben. 
```
----> Mimi gibt dem Spieler ein angebissenes Plätzchen - Spieler hat im Inventar einen Keks der "angebissener Keks " heißt.

```yml
Spieler: Was, Tante Hilde ist schon weg? Na dann los! Aber schnell!
Mimi: Willst du nicht mein Geheimniss wissen?
Spieler: Nun sag schon!!! - du wirkst sehr ungeduldig - 
Mimi:  - Mimi zieht dich zu sich herunter und flüstert in dein Ohr - Junnar nmag dich! 
Spieler: Shichos Schwester? - du wirst rot und sagst sehr unwirsch - Verschwinde! Auf zum Schiff!
 ```
[Ende]

## NPC

### Mimi

Mimi looks like a nice, though dirty little girl, just as you would imagine any other little girl. Red curly hair frames a little pretty looking round face, which seems to need a cleaning almost every time. Especially around her mouth traces of the meals of today can be seen which melt easily with the freckles on her nose and cheeks. But her huge green eyes let you forget the dirt in her face. She wears her worn out dress, which might have been green once, like the daughter of the King himself and her lack of shoes comes in handy when she gets up and climbs up into the Tian tree. She is about a half a meter tall,  her small stature   often fools people who think she is much younger than she actual is. Her skin colour is  of a healthy tan, but what is really sunburned or dirt is not to be judged easily. She loves all yellow flowers and often carries a blossom in her hair or fixed to her bandana.

--> Übersetzung folgt noch. 

Nur zum Ansehen: https://i.imgur.com/KRhnMRN.jpg



### Standartsätze

#### Während der Quest


---> falls die Quest angenommen wurde:

1. Hast du meine Puppe schon?
2. Hey, wo bleibt meine Puppe!
3. <Name des Spielers>, du schaffst das!
4. <Name des Spielers>, du wirst doch nicht ein kleines Mädchen enttäuschen!



#### Nach der Quest

1. Na, was macht mein Held? 
2. Hey <Name des Spielers> Keine Angst, ich gehe schon rechtzeitig zum Schiff, du bist ja auch noch da. 


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


 #### Standort

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
x: 
y: 
z: 
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











