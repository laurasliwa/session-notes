# Shell Basics

Statt mit einem User Interface, arbeiten Entwickler häufig mit CLIs (Command Line Interfaces), welche textbasierte Interfaces sind. Durch eingegeben Kommandos (Commands) kann mit dem Computer interagiert werden.

**Vorteile:**

- Viele Tools haben kein GUI (Graphical User Interface) und können nur durch CLI bedient werden.
- Dadurch können Skripte (scripts), die eine Anzahl von Commands beinhalten, geschrieben werden um Prozesse und wiederholende Aufgaben zu automatisieren, sowie sicherstellen, dass diese jedes Mal exakt gleich ausgeführt werden.

Auf macOS benutzen wir zsh (z shell) als den Command Interpretierer.

Dies läuft standardmäßig in der Terminal App. Für diesen Kurs benutzen wir iTerm und Visual Studio Code als alternative Terminal Emulatoren.

- Ein shell (wie z. B. zsh) ist ein Command Interpretierer, welches Commands ausführt auf dem Computer und zeigt die Ergebnisse an.
- Ein Terminal (wie z. B. Terminal, iTerm, Visual Studio Code) ist ein Umfeld für Textein- und -ausgabe, welches Commands an das Shell sendet und die Ausgabe anzeigt.

## Basic Shell commands

| command                    | functionality                                            |
| -------------------------- | -------------------------------------------------------- |
| ls                         | listet den Inhalt in dem aktuellen Ordner an             |
| cd <foldername>            | wechselt zum genannten Ordner                            |
| cd ..                      | wechselt in den übergeordneten Ordner                    |
| cd ~                       | wechselt in die Home Directory                           |
| pwd                        | zeigt den aktuellen Ordner Pfad an                       |
| touch <Dateinname>         | erstellt eine Datei mit dem entsprechenden Namen         |
| mkdir <Ordnername>         | erstellt einen Ordner mit dem entsprechenden Namen       |
| mv <alterName> <neuerName> | verschiebt oder benennt eine Datei um                    |
| rm <Dateinname>            | löscht eine Datei permanent (keine Datei im Papierkorb!) |
| open .                     | öffnet den aktuellen Ordner im Finder                    |
| cat <Dateiname>            | zeigt den Inhalt der Datei an                            |
| curl <url>                 | zeigt den übermittelteten Inhalt der Url an              |

> Es gibt noch viel mehr Commands für jede mögliche Aktion, die eins durchführen möchte. Hier ein [Cheat Sheet](https://github.com/RehanSaeed/Bash-Cheat-Sheet) zum weiter einlesen.
