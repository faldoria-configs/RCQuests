# Sirina <!-- omit in toc -->

## Beschreibung
Sirina ist eine junge Frau, die um die Insel wandert und Melonen und andere Früchte verkauft, die sie selber zieht. Vielleicht auch das eine oder andere Plätzchen.

## Besonderheiten

Händlerin für Früchte und Süßigkeiten

## Übersicht
- [Beschreibung](#beschreibung)
- [Besonderheiten](#besonderheiten)
- [Übersicht](#%C3%BCbersicht)
- [Dialog 1 (mit Quest)](#dialog-1-mit-quest)
- [Dialog 2 (ohne Quest)](#dialog-2-ohne-quest)
- [Ein-Satz-Antwort](#ein-satz-antwort)
- [Ausrüstung](#ausr%C3%BCstung)
- [Standort](#standort)
- [Items im Inventar](#items-im-inventar)
  - [Süße Melonenscheibe (Geschenk)](#s%C3%BC%C3%9Fe-melonenscheibe-geschenk)
  - [Süße Melonenscheibe](#s%C3%BC%C3%9Fe-melonenscheibe)
  - [Roter Apfel](#roter-apfel)
  - [Rotes Rübchen](#rotes-r%C3%BCbchen)
  - [Honigplätzchen](#honigpl%C3%A4tzchen)
  - [Süßes Rübchen](#s%C3%BC%C3%9Fes-r%C3%BCbchen)



**Spieler begegnet der wandernden Händlerin Sirina**

## Dialog 1 (mit Quest)


> Wenn die Quest ... schon angenommen wurde
 
Hey Sirina, ich soll allen sagen, dass wir uns bereit machen sollen zu fliehen, weil der Agnamemnon kommen soll - ach nein, das war jemand anderes, also, du weißt schon..   
**Sirina:** `Ja, ich habe es schon gehört, aber ich habe nicht viel zu packen oder überhaupt mitzunehmen. Wenn man nur wüßte, wann man sich auf dem Schiff einzufinden hat. Aber ich hoffe, ich kann meine Runden schon noch eine Male gehen.`   
Ich weiß es nicht, aber du könntest, wenn du eh schon unterwegs bist, es allen sagen, die du triffst.    
**Sirina:** `Und was soll ich sagen, in drei Stunden oder drei Wochen?`   
Das weiß ich auch nicht.   
**Sirina:** `Sieh mal, der Baum wirkt ganz unruhig, die Blätter bewegen sich, als ob ein  Wind wehen würde, dabei ist es windstill .`   
Ja, das ist mir noch nicht aufgefallen, vielleicht ist das ein Zeichen für die nahe Ankunft?   
**Sirina:** `Hmm, ich werde drauf achten und wenn es noch schlimmer wird, dann eile ich zum Schiff!`   
Gute Idee, aber ich muss weiter.   
**Sirina:** `Halt, warte! *Sie grinst dich an*  da hast du eine Stück Melone, damit deine Kehle nicht einrostet, wenn du so viel reden musst!`   
Uh, danke..   
**Spieler erhält einen Stack Wassernelonenscheiben**   

## Dialog  2 (ohne Quest)

> Falls die Quest noch nicht angenommen wurde:

**Sirina:** `Hey, [Name des Spielers], was treibst denn du hier. Ein Stück Wassermelone gefällig, nur 5 Heller das Stück.`   

1. Ja bitte [Handelsmenue geht auf]   
    Die schaut lecker aus wie immer. Wieso sind deine Früchte soviel süßer als alles, was ich zu ziehen versucht habe?   
**Sirina:** ` *lacht* Ja, weil ich ihnen jeden Tag gut zurede und du ihnen nur drohst, dass du sie essen wirst.`   
Ach was, du wirst sie mit Honig gießen, das wird’s sein.   
**Sirina:** `Oh nein, dann müssten sie teuerer sein. Aber jetzt muss ich weiter.`   

2. Grade nicht, aber erzähle, wie geht es dir? Hast du schon von dem drohenden Unheil gehört?   
**Sirina:** `Ja, natürlich, aber ich kann’s nicht glauben, ich warte einfach ab, was passiert.`   
Na du bist lustig, aber, mach’s gut, ich hoffe, du hast recht und es wird nicht so schlimm.   
**Sirina:** `Wir werden sehen, und pass auf dich auf!`   

## Ein-Satz-Antwort
Falls ein weiteres Mal angeklickt wird:

**Sirina:** `Immer noch hier? Ich muss diesmal aber weiter, mach’s gut!`


## Ausrüstung
Melonenscheibe in der Hand
Skin: 
https://faldoria.de/board/thread/560-skins-ankanor/?postID=4355#post4355

## Standort

Läuft auf dem Hauptweg 

```yml
x: 
y: 
z: 
world: ankanor
```

## Items im Inventar

### Süße Melonenscheibe (Geschenk)

```yml
ID: 360
name: Süße Melonenscheibe
type: QUEST
quality:COMMON
item: melon_slice
lore: süß, saftig, tropfend
max-stack-size: 64
price: - 
```

### Süße Melonenscheibe

```yml
ID: 360
name: Süße Melonenscheibe
type: VENDOR
quality:COMMON
item: melon_slice
lore: süß, saftig, tropfend
max-stack-size: 16
price: 3 Heller
```

### Roter Apfel

```yml
ID: 
name: Roter Apfel
type: QUEST
quality: COMMON
item: apple
lore: knackig, saftig, rot
max-stack-size: 16
price: 3 Heller
```

### Rotes Rübchen

```yml
ID: 434
name: Rotes Rübchen
type: VENDOR
quality:COMMON
item: beetroot
lore: So lecker und frisch
max-stack-size: 16
price: 3 Heller
```

### Honigplätzchen

```yml
ID: 357
name: Honigplätzchen
type: VENDOR
quality:COMMON
item: cookie
lore: Reinbeißen und glücklich sein! 
max-stack-size: 16
price: 5 Heller
```

### Süßes Rübchen

```yml
ID: 391
name: Süßes Rübchen
type: VENDOR
quality: COMMON
item: carrot
lore: Da ist zuviel Zucker außen rum!
max-stack-size: 116
price: 5 Heller
```

