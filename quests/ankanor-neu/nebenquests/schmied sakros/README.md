# Schmied Sakros  <!-- omit in toc -->

Issue #97


## Noch zu tun/Probleme

Skin, Standort

## Ablauf

Zwei Quests!
[Eisen für die Schmiede](#eisen-fuer-die-schmiede)
[Schwerter schmieden](#schwerter-schmieden)   <-----  Doch extra machen


1. Die Spielerin läuft zum Schmied und fragt, ob er Arbeit hat.
2. Sacros braucht Eisen und schickt die Spielerin zu einer Höhle, in der alte Schwerter sind.
3. Die Spielerin wird vor der Höhle von Genam aufgehlten und bekommt eine extra Quest.
4. Die Spielerin bringt die Schwerter und das Eisen zu Sakros zurück.
5. Darauf hat Sakros eine weitere Aufgabe (nächste Quest:)

## Übersicht

## Vorraussetzungen
HQ [Einübung der Waffe](../../5-einübung-der-waffe/ReADME-md) angenommen

## Aufgaben

### `Dialog 1`

Die Spielerin wird schon von 5 Block Entfernung angerufen: 

**Sakros:** ` [Name des Spielers], komm sofort her, sofort!`   
Ja, ich komme ja schon, wollte ja fragen, ob du mich brauchst.   
**Sakros:** `Bla bla, wer's glaubt wird selig und so weiter. Ich muss Schwerter machen und brauche dazu Materialien!`   
Und wo soll ich deine Materialien herbekommen, ich bin doch kein Bergmann.   
**Sakros:**  `Nein, so schaust du nicht aus, das ist wahr.. `   
Wieso schickst du nicht jemand anders oder gehst selber.    
**Sakros:** `Weil ich keine Lust habe und weil ich ein gutes Argument habe, nämlich meine Faust.`   
`*Sakros hält sie dir unter die Nase, sie riecht nach Schmiedefeuer und Stärke*`   
Na gut, Was brauchst du?     
**Sakros:**  `Eisen und rostige Schwerter aus der Höhle auf der anderen Seite des Dorfes. Da sollten noch Kisten rumstehen.`   
Das alte Piratenzeug oder wer das auch immer war?   
**Sakros:**  `Ja,das alte Zeug und jetzt los, sonst setzt´s was!`  

1. Ich geh' ja schon, auch wenn Höhlen nicht so meins sind.

### `[Quest Start]`[Eisen für die Schmiede]
**Questlog:**  *Besorge in der Höhle auf der anderen Seite der Insel 7 Eisenbarren und 7 Schwerter*

2.  Nein vergiss es! Höhlen sind nichts für mich. `[Ende]`
 
**Die Spielerin läuft zur Höhle und trifft dort auf Genam, der ihr eine extra Quest gibt. Mit Schwertern und Eisen kommt sie zu Sakros zurück.**


### Dialog 2

Ich bin wieder da! Und habe Schwerter und Eisen!    
`[Quest Ende:]`[Eisen für die Schmiede](#eisen-fuer-die-schmiede)   
**Belohnung:**  XP   


**Sakros:** ` Wieso hat das so lange gedauert??`   
Da waren Skelette in der Höhle! Außerdem musste ich einmal um die ganze Insel rum, also beschwer dich nicht!          
**Sakros:** `Dann los, mach mir die Schwerter!`   
Äh, was?!?   
**Sakros:** ` Irgendwann musst du es schließlich lernen. Also los, es ist einfach. Zieh den Hebel, drück den Knopf und betätige den Hebel erneut.`   
Ermm... na gut.

`[Quest Start:]`[Schwerter schmieden](#schwerter-schmieden)

**QuestLog:** *Stelle 3 Schwerter her, indem du den Hebel ziehst, den Knopf drückst und nochmal den Hebel betätigst.*

** Der Spieler macht die gegebene Aufgabe, bis Sakros nach dem dritten Schwert sagt:**

**Sakros:** `Gut, das sollte reichen.`   
Und? Bist du zufrieden mit der Arbeit?   
**Sakros:** `Hab schon besseres gesehen, aber für den ersten Versuch ist das schon recht gut.`  
Und warum konntest du das selbst nicht machen?   
**Sakros:** `Hab mir nen Nagel eingerissen. Und jetzt hau ab!`

`[QUEST ENDE]` [Schwerter schmieden](#schwerter-schmieden)    
[Belohnung](#Belohnung)





## NPCs

## `Schmied Sakros`

Schmied von Ankanor. Ein sehr rauer und ungeduldiger Geselle.

## Standartsätze  

### **Vor der Quest**   

Wenn Quest  [Einübung der Waffe] noch nicht angenommen wurde (alternativ):    

**Sakros:** ` Nur mit einer starken Faust kann man etwas in seinem Leben erreichen.`   
**Sakros:** `Puh, ich hasse diese Hitze am Schmelzofen!  Geh nicht zu nah ran! Wärst nicht der Erste, der mit einer Brandwunde wieder weggeht! *lacht lauthals* `    
  
Wenn Quest [Eisen für die Schmiede](#eisen-fuer-die-schmiede) das erste Mal abgelehnt wurde:

**Sakros:** `Wie, du kommst wieder? Es gibt noch Zeichen und Wunder! Du willst jetzt doch gehen?`   
Ja, ich habe es mir anders überlegt.   

`[Quest Start]`[Eisen für die Schmiede](#eisen-fuer-die-schmiede)   
**Questlog:**  *Besorge in der Höhle auf der anderen Seite der Insel 7 Eisenbarren und 7 Schwerter*

### **Während der Quest**  
**Sakros:** ` Du bist ja noch immer hier, beeil dich und hol mir die Materialien für die Schwerter! Aber etwas plötzlich!`

### **Nach der Quest**  
- Nicht vorhanden bzw. Questdialog [Schwerter schmieden](#schwerter-schmieden)
**Sakros:** `Was bist du noch hier? Die Schwerter braucht jemand! Lauf!
    
### **Ausrüstung**
Schwert in der Hand
Skin ID
### **Standort**

```yml
x: 
y: 
z: 
world: ankanor
```

## Items

### Eisenbarren

Dropt von den Verwitterten Skeletten, wird später gebraucht, um Schwerter zu schmieden.

```yml
ID: 
name: Eisenbarren
type: QUEST
quality: COMMON
item: IRON INGOT
lore: Dieser Eisenbarren ist völlig angerostet, ob der noch verwendet werden kann ist fraglich.
max-stack-size: 64
```


### Rostiges Schwert

Dropt von den Skeletten.

```yml
ID: 
name: Rostiges Schwert
type: QUEST
quality: COMMON
item: IRON SWORD
lore: Ein vom Meersalz angerostetes Schwert.
max-stack-size: 1
```

## Belohnung


## Referenzen
Verbunden mit [Genam](../skelette/README.md) 



