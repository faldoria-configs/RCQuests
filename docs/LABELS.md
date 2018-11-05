# Issue Labels

Um die ganzen [Issues](https://git.faldoria.de/groups/tof/-/issues) besser zu verwalten sollten alle Issues mit entsprechenden Labels versehen werden. Das Labeln von Issues kann von jedem vorgenommen werden und ist nicht Team exklusiv.

Jedes Issue sollte mindestens eins der folgenden Labels haben:

* Typ: ~"feature-proposal", ~"feature", ~"bug", ~"config", ~"docs", etc.
* Projekt: ~"quest", ~"conversations", ~"server", ~"loot", ~"mobs", ~"items", ~"docker", ~"admin-web", etc.
* Team: ~"SuQ", ~"Developer", ~"Quest Scripter", ~Builder, ~Web, ~CM, ~Admin
* Priorität: ~P1, ~P2, ~P3, ~P4
* Auswirkung: ~A1, ~A2, ~A3, ~A4

## Typ Labels

Jedes Issue sollte mindestens ein Typ Label haben. Je nach Typ werden Issues anders priorisiert und automatisch oben angezeigt.

Beispiele für Typ Labels sind: ~"feature-proposal", ~"feature", ~"bug", ~"config", ~"docs", etc.

Typ Labels können jede Farbe außer blau (reserviert für Projekt Labels) und türkis (reserviert für Team Labels) haben.

Typ Labels sind immer in Kleinbuchstaben angegeben.

## Projekt Labels

Wenn möglich sollte ein Issue einem Projekt, bzw. Gebiet zugeordnet werden. Das macht es leichter passende Issues im eigenen Experten Gebiet zu finden.

Beispiele für Projekt Labels sind: ~"quest", ~"conversations", ~"server", ~"loot", ~"mobs", ~"items", ~"docker", ~"admin-web", etc.

Projekt Labels sollen immer die Farbe blau haben und klei geschrieben werden.

## Team Labels

Team Labels dienen dazu Issues einem Team zuzuordnen und sie somit noch besser zu kategorisieren. Team Labels können sich im Lauf eines Issues verändern. Ein klassisches Beispiel hierfür ist das Schreiben und Entwicklen einer neuen Quest.

Folgende Teams gibt es aktuell:

* ~SuQ - Das Story und Quest Entwickler Team ist für das Schreiben von Quests zuständig.
* ~"Quest Scripter" - Das Quest Scripting Team übernimmt die Implementierung der Quest Configs.
* ~Developer - Das Developer Team übernimmt die Programmierung von Plugins.
* ~Builder - Das Builder Team kümmert sich um den Bau der Welt von Faldoria.
* ~Web - Das Web Developer Team kümmert sich um die Programmierung der Web Oberflächen.
* ~CM - Das Community Management Team kümmert sich um diverse Aufgaben was die Organisation der ToF Community betrifft.
* ~Admin - Das Admin Team kümmert sich um die Wartung und Konfiguration der Server.

Team Labels sind in türkis und der erste Buchstabe sollte immer groß geschrieben werden damit die Labels als erstes in der Issue Liste auftauchen.

## Priorisierung von Issues

Damit Issues leichter priorisiert werden können gibt es Labels für die Auswirkung und Priorität eines Issues.

### Priorität

Die Priorität soll eingrenzen wie schnell ein Issue implementiert und den Spielern bereitgestellt werden soll. Je niedriger die Priorität umso wichtiger ein Issue.

| Label | Priorität | Beschreibung |
| ----- | --------- | ------------ |
| ~P1 | Priorität 1 - Sehr Hoch | Issue muss in das aktuelle Release und so schnell wie möglich live gestellt werden. |
| ~P2 | Priorität 2 - Hoch | Issue soll in das nächste Release. |
| ~P3 | Priorität 3 - Mittel | Issue soll in eins der nächsten Releases. Muss aber nicht in das nächste Release. |
| ~P4 | Priorität 4 - Niedrig | Issue ist nicht sehr wichtig und kann in Zukunft irgendwann kommen. |

### Auswirkung

Die Auswirkung eines Issue bestimmt die Kritikalität des Issues auf das Spielgeschehen. Je höher die Auswirkung umso wichtiger ist ein Issue. Das Auswirkungs Label betrifft hauptsächlich nur Issues mit dem ~bug Label.

| Label | Auswirkung | Beschreibung | Beispiel |
| ----- | ---------- | ------------ | -------- |
| ~A1   | Blocker    | Ausfall oder kaputtes Feature ohne Workaround. | Der Server crasht jedesmal wenn ein Spieler joint. Spieler können keine Skills verwenden oder Quests annehmen. |
| ~A2 | Kritisch | Kaputtes Feature für das der Workaround zu komplex oder inaktzeptabel ist. | Spieler können Skills nur über Commands ausführen. |
| ~A3 | Hoch | Kaputtes Feature mit existierendem Workaround. | Das Abbrechen von Quests funktioniert nicht direkt über das Questlog sondern nur über den Befehl. |
| ~A4 | Gering | Funktionelle Unanehmlichkeit oder kosmetisches Issue. | Alle Skills werden als Bücher dargestellt. Falsche Formattierung von Quests im Questlog. |
