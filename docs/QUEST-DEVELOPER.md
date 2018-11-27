# Quest Entwickler

Als Quest Entwickler transferiert man die fertig entworfenen Quests der Quest Schreiber in Konfigurationen. Diese Konfigurationen werden dann vom [RCQuests](../README.md) Plugin geladen und ermöglichen es Spielern die Quests im Spiel zu erleben.

## Getting Started

Alle Quests werden in [YAML](https://de.wikipedia.org/wiki/YAML) geschrieben, daher wird ein ordentlicher Editor, wie z.B. [Visual Studio Code](https://code.visualstudio.com/) oder [Notepad++](https://notepad-plus-plus.org/) empfohlen.
Außerdem werden alle Quest Configs mit dem [Versionskontroll-System Git](https://git-scm.com/downloads) verwaltet.

Um die Quest Configs auschecken und bearbeiten zu können wird ein Account im [Gitlab von Faldoria](https://git.faldoria.de/) benötigt. Für einen Zugang bitte an `xanily` wenden.

Als erstes muss das Git Repository mit den Quest Configs ausgecheckt werden.

```sh
git clone https://git.faldoria.de/tof/plugin-configs/quests.git
```

Anschließend den gesamten Config Ordner z.B. mit VS Code öffnen.

```sh
cd quests
code .
```

### Bestandteile

Eine Quest besteht aus mehreren YAML Dateien (Endung `.yml`) die alle verschiedene Funktionen innerhalb der Quest übernehmen. In fast jedem der Module wird die [ART API](https://git.faldoria.de/tof/plugins/raidcraft/raidcraft-api/blob/master/docs/ART-API.md) verwendet.

| Bestandteil                                                                                                               | Datei-Endung                       | Beschreibung                                                                                                                       |
| ------------------------------------------------------------------------------------------------------------------------- | ---------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| [Quest](QUEST-CONFIG.md)                                                                                                  | `.quest.yml`                       | Die Hauptdatei einer Quest in welcher der Ablauf und die Aufgaben definiert werden.                                                |
| [Quest Gebiet](QUEST-REGION.md)                                                                                           | `.region.yml`                      | Mit Quest Regionen können mehere Quests in ein Gebiet gruppiert werden.                                                            |
| [Host/NPC](https://git.faldoria.de/tof/plugins/raidcraft/conversations/blob/master/docs/ADMIN.md#hosts)                   | `.host.yml`                        | NPCs die beim Laden der Quest gespawnt werden und mit denen interagiert werden kann.                                               |
| [Conversation](https://git.faldoria.de/tof/plugins/raidcraft/conversations/blob/master/docs/ADMIN.md)                     | `.conv.yml`                        | Eine Unterhaltung die während der Quest durch einen NPC oder anderweitig ausgeführt wird.                                          |
| [Custom Items](https://git.faldoria.de/tof/plugins/raidcraft/rcitems/blob/master/docs/ADMIN.md#config-dateien)            | `.item.yml`                        | Ein Custom Item das temporär für die Quest existiert. Belohnungen sollten als normale Items über das Webinterface angelegt werden. |
| [Item Aliase](https://git.faldoria.de/tof/plugins/raidcraft/rcitems/blob/master/docs/ADMIN.md#alias-items)                | `.items.yml`                       | Eine Gruppierung von Items mit Referenz auf deren Datenbank IDs.                                                                   |
| [Mobs](https://git.faldoria.de/tof/plugins/raidcraft/rcmobs/blob/master/docs/ADMIN.md)                                    | `.mob.yml`                         | Custom Mobs die nur für die Quest relevant sind.                                                                                   |
| [Mob Gruppen](https://git.faldoria.de/tof/plugins/raidcraft/rcmobs/blob/master/docs/ADMIN.md#mob-gruppen)                 | `.mob-group.yml`                   | Eine Gruppierung von Custom Mobs um das Tracking und Spawnen zu erleichtern.                                                       |
| [Loot-Tabellen](https://git.faldoria.de/tof/plugins/raidcraft/rcloot/blob/master/docs/ADMIN.md)                           | `.loot.yml`                        | Eine Loot Tabelle speziell für die Quest um z.B. die definierten Custom Items zu droppen wenn die Quest aktiv ist.                 |
| [Locations](https://git.faldoria.de/tof/plugins/raidcraft/rclocations/blob/master/README.md)                              | `.location.yml` & `.locations.yml` | Ermöglicht es Order der Welt in Dateien zu speichern und dann in Actions auf den Namen anstatt die Koordinaten zu referenzieren.   |
| [Trigger Groups](https://git.faldoria.de/tof/plugins/raidcraft/raidcraft-api/blob/master/docs/ART-API.md#trigger-gruppen) | `.trigger.yml`                     | Ermöglicht es mehere Trigger (und deren Bedingungen) zu einem Trigger zusammen zu fassen.                                          |
| [Skills](https://git.faldoria.de/tof/plugins/raidcraft/rcskills/blob/master/docs/Skills.md#skills-in-quests)              | `.skill.yml`                       | Ermöglicht es Skills die nicht Spieler gebunden sind für Quests zu erstellen.                                                      |
| [Events](https://git.faldoria.de/tof/plugins/raidcraft/rcevents/blob/master/README.md)                                    | `.event.yml`                       | Ermöglicht es von Quests unabhängige Events zu erstellen, die auf die Ereignise in der Welt reagieren.                             |

> Klicke auf den Namen der Quest Komponente in der Tabelle um Details zur Konfiguration des jeweiligen Bestandteils zu erhalten.

