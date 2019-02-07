# Blüte des Lebens <!-- omit in toc -->
Issue #86   
Idee und erste Ausführung: LilianaVess   
Ausarbeitung: Kirilit

## Noch zu tun/Probleme

## Ablauf

1. Die Spielerin trifft während der Suche nach Arbeit auf Jan, den Weber.
2. Nach einer ersten Ablehnung rückt er nach kurzen Dialog mit einer Aufgabe heraus.
3. Der Spieler soll eine blaue Blume suchen, die hoch oben in den Bergen wächst.
4. Jan will der Spielerin aber nicht sagen, warum er sie braucht, aber er verweist sie zu Ingeborg.
5. Die Spielerin kann entscheiden, ob sie gleich geht, ablehnt, oder erst Ingeborg aufsucht. 
6. Der Spieler holt die blaue Blume.
7. Je nach vorherigem Verlauf erfährt er jetzt, wozu sie gut ist, war er bei Ingeborg, weiß er es schon. 
8. Bei Ingeborg erhält er keinen Zettl, er hat ja nichts für sie getan. 

## Übersicht <!-- omit in toc -->

## Vorraussetzungen

[Vinnans helfende Hand](../2-vinnans-helfende-hand) <--- falscher Link


## Aufgaben

### `Dialog 1`

**Der Spieler trifft auf Jan, den Weber des Dorfes**

**Jan:** `Hallo Fremder, Ihr wollt sicher meine Webarbeiten begutachten. Einen Moment bitte, ich mache gerade Pause.`   
Eigentlich suche ich eher etwas Arbeit.   
**Jan:** `*Jan schaut dich enttäuscht an, da du dich nicht für seine Teppiche interessiert*    
Ich wüßte nicht, was ich Euch für Arbeit geben könnte.`  

1. Na dann, schade, dann suche ich wo anders. `[Ende]`
2. *Du zeigst dich nun doch am Teppich interessiert*   
Hmm, ja, Ihr verwendet schöne Farben, so bunt wie ich es gewohnt bin.   
**Jan:**  `Ihr kommt von weit her?  Wie hat es Euch denn in diese verlassenen Gegend verschlagen?`  
Ja, ich bin vom Volk der Kaishi und komme von Ankanor, von dort wurden wir von Agnitos Schergen vertrieben.   
**Jan:** `Agnitos?`   
Ich meine....    
**Jan:** `Ihr meint Agnatus! Das ist schlimm, wohin dieser finstere Geist überall Elend und Leid bringt.`  
`*Jan scheint für einen Augenblick geistesabwesend zu sein*`  
`Ich hätte vielleicht doch eine Aufgabe für Euch…`  
Und das wäre..?         
**Jan:** `Ich brauche eine  bestimmte blaue Blume, aber sie wächst nur an sehr schwierig zu erreichenden Stellen, Ihr müsstet den Berg dafür erklimmen. Wenn Euch das nicht zu gefährlich ist?`

1. Lieber nicht, dünne Luft vertrage ich nicht so gut. `[Ende]`   
2. Blumen pflücken? Ich habe mir mal an einem Blatt  in die Hand geschnitten, ich glaube das ist mir zu gefährlich. `[Ende]`   
3. Blumen zu pflücken kann doch nicht so schwer sein.   
    **Jan:** ` Das freut mich, dass Ihr das für mich tun wollt.` 

### **[Quest Start]** [Blüte des Lebens]   
**Questlog:** *Sammle 4 Biosnablüten und bringe sie Jan und seiner Frau Lucia*

4.    Wozu braucht Ihr diese spezielle Blume?   
**Jan:** ` *wirkt verlegen* Das ...   fragt Ingeborg, die kann das besser erklären als ich.`   
4.1 Ach ja, ich habe schon mit ihr gesprochen. Deshalb! Warum sagt Ihr das nicht gleich! Ich springe, ich eile!   
     **`[Quest Start]`** [Blüte des Lebens] ---> Wenn Spieler schon vorher mit Ingeborg geredet hat.   
4.2 Gut, ich suche sie auf, werde sie schon finden.

###   **[Quest Start]** [Was weiß Ingeborg?]   
**Questlog:** *Gehe zu Ingeborg und sieh zu, was du erfährst* 


4.3 Nein, so sehr interessiert es mich jetzt auch wieder nicht.   
    **Jan:** `Werdet Ihr nun die Blume für mich suchen?` 

4.3.1. Na klar, so ein Blümchen kann nicht so schwierig zum Pflücken sein.    
*Du summst vor dich hin:* Blümchen am Wege, Blümchen am Stege, Blümchen, blüh, Frühjahr ist hie!   
**Jan:** `*Jan schaut dich sehr verdutzt an*`      
*Du lachst* Ich geh ja schon!   

4.3.2. Ich rede doch erst mal mit Ingeborg, ich klettere doch nicht wegen einer Marotte einen Berg hinauf! 
   
**[Quest Start]** [Was weiß Ingeborg?]    
**Questlog:** *Gehe zu Ingeborg und sieh zu, was du erfährst*  
   



## NPCs


## `Name des NPCs`

### Standartsätze  


#### Vor der Quest

#### Während der Quest  


#### Nach der Quest
    
### Ausrüstung



#### Standort



```yml
x: 
y: 
z: 
world: faldoria.eisenküste
```

## Items


### Itemname

Nach dem exakten Namen des Items folgt eine kurze Beschreibung des Items, ob es dropt oder verkauft wird, bzw. die Relation zur Quest und wenn das Item schon vorhanden ist folgt die ID des Items. 

```yml
ID: ?
name: 
type: QUEST
quality: RARE /COMMON
item: 
lore: max-stack-size: 1
```




## Mobs


### Mobname



### Hungriger Wolf

```yml
name: Hungriger Wolf
type: wolf
aggro: true
passive: false
elite: true
min-level: 8
max-level: 8
```
```yml
x: 535
y: 101
z: -2121
world: faldoria.jarmundshain
radius: 5
```


#### Ausrüstung



## Belohnung



## Referenzen


## Issues


