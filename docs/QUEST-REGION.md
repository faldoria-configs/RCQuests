# Quest Regionen

Quest Regionen dienen dazu mehrere Quests in einem Gebiet zusammen zufassen. Außerdem macht es das Testen der Quests leichter, da man durch folgenden Befehl alle Quests in einem Gebiet zurücksetzen kann. Jede Quest kann immer nur einem Gebiet zugeordnet werden.

> Befehl zum Zurücksetzen eines Quest Gebiets: `/rcqa purge -r <gebiet> [-t] <Spieler>`
> z.B.: /rcqa purge -r ankanor -t Silthus

Der Switch `-t` teleportiert den Spieler an den Startpunkt des Gebiets.


```yaml
# Quests werden im Quest Log nach Gebieten sortiert.
name: Name des Gebiets
# Zusammenfassung des Gebiets. Wird als Mouseover im Questlog angezeigt.
description: Super dupa Test Quest Gebiet
# Das ungefähre Level in dem das Quest Gebiet gemacht werden soll.
# Hat aktuell keine Auswirkung, wird aber vielleicht in Zukunft beeinflussen wie Quest Gebiete dargestellt werden.
min-level: 10
max-level: 20
# Der Startpunkt des Quest Gebiets.
# Kann beim Zurücksetzen der Quest genutzt werden um sich dorthin zu teleportieren.
location: this.meine-location
location:
  x: 1
  y: 2
  z: 3
```