# Hauptmann Marduk

Er schimpft sich zwar Hauptmann, es gibt aber eigentlich keine richtigen Truppen bei den Kaishi. Marduk ist ein sehr entspannter Typ, er hat keine Kampferfahrungen, soll sich aber um die Verteidigung kümmern.

- [Quest Dialoge](#quest-dialoge)
    - [Dialog 1](#dialog-1)
        - [Option 1](#option-1)
        - [Option 2](#option-2)
    - [Dialog 2](#dialog-2)
    - [Dialog 3](#dialog-3)
        - [Option 1](#option-1-1)
        - [Option 2](#option-2-1)
    - [Dialog 4](#dialog-4)
- [Standard Dialoge](#standard-dialoge)
    - [Während der Quest Was ist passiert](#w%C3%A4hrend-der-quest-was-ist-passiert)
    - [Nach der Quest Was ist passiert](#nach-der-quest-was-ist-passiert)
- [Ausrüstung](#ausr%C3%BCstung)
- [Standort](#standort)

## Quest Dialoge

### Dialog 1

Von Quest [Was ist passiert](1-was-ist-passiert/README.md)

#### Option 1

> Wenn [`ankanor.event.survivor`](1-was-ist-passiert/README.md#tag-1) gesetzt ist.

```yaml
Marduk: [Name des Spielers], bist du auch endlich wach, ja?
Spieler: Hauptmann Marduk hat uns dieser Aknetun erwischt oder warum sind wir plötzlich an einer Küste?
Marduk: Du scheinst einen sehr festen Schlaf zu haben, letzte Nacht tobte ein übler Sturm, der das Schiff zerstörte und uns hier angespült hat. Wir haben dich einfach aus dem Schiffwrack geholt und dachten du wärst ohnmächtig.
Spieler: Ist das dein Ernst? Hmm... und was machen wir nun?
```

#### Option 2

> Wenn [`ankanor.event.survivor`](1-was-ist-passiert/README.md#tag-1) **nicht** gesetzt ist.

```yml
Marduk: [Name des Spielers], bist du auch endlich wach, ja?
Spieler: Hauptmann Marduk hat uns dieser Aknetun erwischt? Sind wir alle tot?
Marduk: Nein, du wurdest ausgeknockt als du Agnatus Schergen bekämpft hast, man hat dich dann zum Schiff gebracht. Dort wurdest du versorgt.
Spieler: Und wo sind wir hier? Das sieht mir nicht nach Ankanor aus.
Marduk: Wo genau wir sind weiß keiner, aber nein es ist nicht mehr Ankanor. Der Sturm letzte Nacht hat unser Schiff zerstört und wir wurden hier angespült.
Spieler: Ist das dein Ernst? Hmm... und was machen wir nun?
```

### Dialog 2

Von Quest [Was ist passiert](1-was-ist-passiert/README.md)

Knüpft direkt an [Dialog 1](#dialog-1) an.

```yml
Marduk: Ich habe zwar schon die Gegend ein wenig erkundet und sie scheint weitgehend unbewohnt zu sein. Aber ich habe ein Licht auf dem Hügel gesehen, ich kann hier nicht weg, ich muss das Camp beschützen. Schau dir das mal an und berichte mir dann.
1: Jawohl!
```

### Dialog 3

Von Quest [Was ist passiert](1-was-ist-passiert/README.md)

#### Option 1

> Wenn die Quest [Reparaturarbeiten](2-reparaturarbeiten/README.md) abgeschlossen wurde.

```yaml
Marduk: Da bist du ja wieder! Hast du die Quelle des Lichts gefunden?
Spieler: Das habe ich. Es handelte sich dabei um einen abgestürzten Ballon. Der Pilot und ich haben ihn wieder repariert. 
Marduk: Was ist ein Ballon? 
Spieler: Ein Schiff, das in der Luft fährt. Er hat mir auch angeboten, da wir ja mehr über dieses Land herausfinden wollen, dass er mich mitnimmt. Das wäre phantastisch, bitte lasst mich mit.
Marduk: Ein Schiff, das in der Luft fährt, das klingt so als würden wir echt mehr erfahren müssen. Es ist ein großzügiges Angebot, dich mitzunehmen. 
Spieler: Also kann ich mit ihm mit?
Marduk: Nun denn, du hast meine Erlaubnis. Ziehe als Botschafter unseres Volkes los und finde mehr über dieses Land heraus. 
Spieler: Danke, Hauptmann!
```

`[QUEST ENDE]` [Was ist passiert](1-was-ist-passiert/README.md)

Dialog geht direkt mit [Dialog 4](#dialog-4) weiter.

#### Option 2

> Wenn [`eisenkueste.duty-start`](1-was-ist-passiert/README.md#tag-2) gesetzt ist und die Quest [Reparaturarbeiten](2-reparaturarbeiten/README.md) **nicht** abgeschlossen wurde.

```yaml
Marduk: Da bist du ja wieder! Hast du die Quelle des Lichts gefunden?
Spieler: Das habe ich. Es handelte sich dabei um einen abgestürzten Ballon und jemand namens Elius.
Marduk: Was ist ein Ballon?
Spieler: Ein Schiff, das in der Luft fährt.
Marduk: Ah, wir müssen viel mehr über dieses Land herausfinden. Weißt du denn noch mehr?
Spieler: Nein, aber dieser Elius möchte das ich ihm helfe, vielleicht erfahre ich dann mehr.
Marduk: Das klingt gar nicht so dumm, also hilf ihm.
```

`[QUEST ENDE]` [Was ist passiert](1.-was-ist-passiert/README.md)

Dialog geht direkt mit [Dialog 4](#dialog-4) weiter.

### Dialog 4

Von Quest [Die Erlaubnis](3-die-erlaubnis/README.md)

```yaml
Marduk: Ich hoffe, du weißt was du tust, aber du bist der Einzige, der gerade auf diese Reise gehen kann.
Spieler: Das ist etwas sehr Wichtiges, oder?
Marduk: Ja, du wirst es großartig machen. Nun gut, aber du solltest dich noch etwas besser vorbereiten bevor ich dir die Erlaubnis geben kann, von hier fort zu gehen.
Marduk: Außerdem hilf doch den anderen hier im Camp auch noch bitte.
Spieler: Das mache ich. Welche Aufgabe hast du für mich denn noch?
Marduk: Am Strand sind anscheinend einige Ruinen von Türmen, die einst wohl mal die Küste sichern sollten. Gehe doch dorthin und schaue ob du etwas Brauchbares findest.
```

## Standard Dialoge

### Während der Quest [Was ist passiert](1-was-ist-passiert/README.md)

1. Wir sind hier erstmal gestrandet und müssen so viel wie möglich erfahren, also finde alles heraus was du kannst.

### Nach der Quest [Was ist passiert](1-was-ist-passiert/README.md)

1. Ich hoffe, dass man diesem Elius vertrauen kann.

## Ausrüstung

Lederrüstung ohne Helm
Steinaxt in der Hand

## Standort

```yml
x: 3645
y: 63
z: -2829
world: faldoria
```