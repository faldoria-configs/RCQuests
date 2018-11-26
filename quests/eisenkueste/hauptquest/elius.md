# Elius

Er ist ein älterer Jorgendder und der eigentliche Großmeister der Gamos Historia. Mehr zu ihm im Lore Dokument.

## Quest Dialoge

### Dialog 1

Von Quest [Was ist passiert](1-was-ist-passiert/README.md)

```yaml
Spieler: Hallo du, ich bin [Spielername], wer bist du?
Elius: Oh ein Fremder, was macht ihr denn hier in der Wildnis? Ich bin Elius und ich bin hier notgelandet.
Spieler: Notgelandet? Ach, seid ihr auch schiffbrüchig so wie ich und meine Leute?
Elius: Kann man so sagen. Mein Ballon hat einen Riss, aber vielleicht könntet ihr mir helfen. Ich bin alt und nicht mehr so fit. 
Spieler: Wie kann ich euch denn helfen?
Elius: Ich brauche ein paar Materialien, ich erkläre Euch genau was ich brauche und wo Ihr es wahrscheinlich finden könnt.
1: Ok, ich helfe gerne.
    # Start von Dialog 2
2: Ich muss aber erst mal Hauptmann Marduk Bericht erstatten.
    Elius: Ok, dann hoffe ich, dass ihr bald wieder hier seid.
    # Vergabe des Tags `eisenkueste.duty-start`
```

### Dialog 2

#### Option 1

Von Quest [Reparaturarbeiten](2-reparaturarbeiten/README.md)

```yaml
Elius: Wunderbar! Ich brauche [1 Klebstoff], [5 Holzbretter], [5 Spinnenseide], [1 Feuerstein] und [5 Stoffe]. 
Spieler: Und wo finde ich das alles?
Elius: Auf alles weiß ich auch keine Antwort, aber einige Tipps kann ich Euch geben.
Elius: Hinter dem Hügel im Süden gibt es eine Mine, ich bin mir sicher da sind Spinnen, gut für Spinnenseide.
Spieler: Ok und weiter?
Elius: Ich schätze, dass sich hier irgendwo Schmuggler niedergelassen haben, vielleicht am Strand, die haben sicher Stoffe und Holzbretter.
Spieler: Und das geben die mir einfach? 
Elius: Ich schätze nicht, ihr müsst sie überzeugen. Klebstoff ist schwierig, es kann aus bestimmten Monstern gewonnen werden. Aber in der Schifffahrt hat man auch oft welches dabei.
Spieler: Ich werde schon einen Weg finden. Feuerstein kann ich sicher irgendwo am Strand finden.
Elius: Das ist sehr gut möglich.
```