- [Katera](#katera)
  - [Funktionen](#funktionen)
  - [Szene - Debut](#szene---debut)
    - [Dialoge](#dialoge)
      - [Ankanor](#ankanor)
      - [Faldoria](#faldoria)
    - [Standort](#standort)
    - [Skin](#skin)

# Katera

Friedenswächterin Katera: So wird sie genannt von denen die wissen, wer sie ist. Sie gehört zu den Friedenswächtern, die in den [Vincul-Lehren](https://git.faldoria.de/tof/story/blob/master/Religionen-Goetter-Erschaffung/Kaishi-Vincul-Lehren.md) erwähnt werden. Wie in den Lehren beschrieben fand sie wie die anderen Friedenswächter den Tod, doch sie manifestierte sich wieder in einer körperlichen Form um die Welt weiterhin zu lehren.  
Auf ihren Reisen fand sie das Gasthaus zum kosmischen Wanderer, merkte welchen zentralen und mystischen Punkt dieses Gasthaus inne hatte und beschloss von hier aus alle Reisenden, die hier unterkamen, insbesondere Kaishi, anzuleiten und zu unterstützen.

## Funktionen

* Verbindung nach Ankanor
* Hat Hinweise auf den Verbleib anderer Kaishi in der gesamten Welt.
* *Quest: Hoffnung Ankanors* - Gibt eine Quest, die den Spieler zurück nach Ankanor bringt. Ob Vergangenheit, Zukunft, Gegenwart sehen wir dann wenn die Quest eine Idee hat beziehungsweise entwickelt wird.

## Szene - Debut

### Dialoge

#### Ankanor

Tag: *ankanor.end = false*

Spieler: Seid gegrüßt.  
Katera: Möge der Frieden mit Euch sein, wie kann ich Euch helfen?  
  * Spieler: Kenne ich Euch von irgendwoher, Ihr kommt mir bekannt vor?
    * Katera: Ich bin Katera, auf dem Pfad der Bindung sind wir uns alle schon einmal begegnet. Wenn Ihr wollt, erzähle ich Euch mehr vom Pfad der Bindung. 
      * Spieler: Das ist nett, doch dafür habe ich gerade keine Zeit. *(Gespräch beendet)*
      * Spieler: Der Pfad der Bindung. *schaut nachdenklich* Sicher, erzählt mir bitte etwas davon.
        * Katera: **[Platzhalter]!!!!!!!!!!**
      * Spieler: Vielleicht ein anderes Mal, ich habe andere Fragen.
        * Katera: Scheut Euch nicht zu Fragen.
        * Spieler: Da ihr Euch mit Pfaden auszukennen scheint: Kennt Ihr einen Pfad von hier weg, ich möchte etwas erleben.
          * Katera: Ihr könnt viele Wege einschlagen, was Ihr sucht, findet Ihr vielleicht auf einer kleinen Insel namens Ankanor.
          * Spieler: Ankanor, das klingt schön. Was werde ich dort erleben, wenn ich diesen Pfad beschreite? 
          * Katera: Dies liegt in Euerer Hand. Ihr werdet dort aber als Kaishi wiedergeboren. Es ist der Beginn Eurer Reise in eine fantastische Welt voller Möglichkeiten. 
          * Spieler: Ich fange also ein neues Leben an? Das klingt super, diesen Pfad möchte ich gehen.
          * Katera: Seid ihr Euch sicher? 
            * Spieler: Ja, ich möchte diesem Pfad folgen. *(Teleport nach Ankanor)* 
            * Spieler: Nein, ich bin mir doch nicht sicher, ich überlege es mir noch einmal. *(Gespräch beendet)*
          * Spieler: Ein neues Leben? Dafür bin ich im Moment nicht bereit. *(Gespräch beendet)*
        * Spieler: Ich hörte schon einmal von der Reise nach Ankanor, bringt mich dort hin. 
        * Katera: Seid ihr Euch sicher? 
          * Spieler: Ja, ich möchte dorthin. *(Teleport nach Ankanor)* 
          * Spieler: Nein, ich bin mir nicht sicher, ich überlege es mir noch einmal. *(Gespräch beendet)*


#### Faldoria

Tag: *ankanor.end = true*

Spieler: Katera, ich brauche eure Hilfe.   
Katera: Möge der Frieden mit Euch sein, wie kann ich Euch helfen?
  * Spieler: Könnt Ihr mir nochmal vom Pfad der Bindung erzählen?
    * Katera: Es ist mir eine Freude, Euch noch einmal davon zu erzählen.
    * Katera: **[Platzhalter]!!!!!!!!!!**
  * Spieler: Ihr habt sicher von der Tragödie gehört, dass wir Kaishi nun auf Faldoria verweilen. 
    * Katera: Gewiss, der Pfad der Bindung offenbarte es mir.
    * Spieler: Wenn wir alle durch den Pfad verbunden sind, sind mehr Kaishi auf Faldoria als jene, die an der Eisenküste angespült worden sind?
    * Katera: Ja $Spielername$, es leben mehr auf Faldoria als jene, die Ihr von der Eisenküste her kennt.
    * Spieler: Helft Ihr mir sie zu finden? Wo sind sie?
    * Katera: Folgt einfach weiter Euren Pfad und kommt später wieder, dann habe ich Informationen über die anderen sammeln können. *(Gespräch beendet)*
  * Spieler: Kennt Ihr einen Weg zurück nach Ankanor?
    * Katera: Der Pfad nach Ankanor kann derzeit nicht beschritten werden. Vielleicht finden wir gemeinsam irgendwann einen Weg zurück . *(Gespräch beendet)*

### Standort
```yml
x: 60
y: 170
z: 127
world: Lobby
```

### Skin
ID: 55