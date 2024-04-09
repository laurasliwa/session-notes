# Github und Markdown

## Markdown

Mit Markdown Syntaxen können Texte formattiert werden. Zum Beispiel können so Listen, Überschriften und vieles mehr erstellt werden. Die Formattierung erfolgt durch bestimmte Zeichen.

### Beispiele

| Element                              | Markdown Syntax                        |
| ------------------------------------ | -------------------------------------- |
| Level 1 headline                     | `# Level 1 headline`                   |
| Level 2 headline                     | `## Level 2 headline`                  |
| Level 5 headline                     | `##### Level 5 headline`               |
| Listen item                          | `- Listen item`                        |
| [ ] to do                            | `[ ] checkbox`                         |
| [x] erledigt                         | `[x] checkbox`                         |
| **fetter Text**                      | `**fetter Text**                       |
| _italicized Text_                    | `_italicized text_`                    |
| [link text](https://www.example.com) | `[link text](https://www.example.com)` |
| Bild                                 | `![Bildbeschreibung](Bild url)`        |
| block quote                          | `> block quote`                        |
| Trennlinie                           | ---                                    |
| `inline code block`                  | `inline code block`                    |
| `code block`                         | `code block`                           |

In diesem [Markdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) sind noch mehr Syntaxen.

## Git und commits

Git ist ein Open-Source-Version-Kontrollsystem welches:

- verfolgt alle Änderungen welche am Source Code vorgenommen wurden
- ermöglicht Developern eine einfache Zusammenarbeit am selben Projekt und Austausch von Updates
- ermöglicht Developern zu einer früheren Version des Source Codes zurück zu gehen

### Git Repositories

Ein Git Repository ist ein Ort an dem ein Projekt gespeichert wird und verfolgt alle Versionen der Projekt Datei. Mehrere Personen haben Zugang zu dem selben Repository und können auch gleichzeitig dran arbeiten.

### Commits

Ein Commit ist **ein Schnappschuss des Repository** zu einem spezifischen Zeitpunkt. Einen Commit erstellen in den Projekt Dateien ist ähnlich wie in einem Videospiel zu **speichern**.

Es kann jederzeit zu jedem vorigen Commit zurückgekehrt werden. Die Projekt Dateien sind dann in dem Zustand in dem sie zu dem Zeitpunkt waren.

Jeder Commit wird mit einer Nachricht erstellt, welche einen beschreibenden Text beinhaltet. Dadurch kann von jeder Person nachvollziehen welche Änderungen in dem entsprechenden Commit enthalten sind.

### Gute Commit Nachrichten

Folgende Regeln sollten beim Commit Nachrichten beachtet werden:

- kurz halten und beschreibend
- immer Englisch benutzen
- das erste Wort sollte immer ein Verb sein (z. B. "add", "fix", "remove", etc.)
- Imperativ und Präsens nutzen: "add shop page" statt "added shop page"
- am Ende der Commit Message soll kein Punkt gesetzt werden
- im Zweifel beschreibe warum etwas geändert wurde, statt wie: "fix typo" statt "replaced the letter a with an e in the second word"

Commit Nachrichten sind Protokolle von allen Änderungen die im Code Base durchgeführt wurden. Andere Developer sollten in der Lage sein zu verstehen was verändert wurde durch das lesen dieser.

## GitHub

GitHub ist eine online Plattform auf der git Repositories gelagert, geteilt und zusammen gearbeitet werden können. Mit GitHub kann der gleiche Codebase von vielen verschiedenen Developern bearbeitet und geteilt werden. Viele Repositories sind Open Source, wodurch eins sich den Code anschauen, kopieren, modifizieren oder für das eigene Projekt nutzen kann.

> Hinweis: Hier gibt es eine [lange Liste an GitHub Repositories](https://github.com/pawelborkar/awesome-repos) zum durchklicken.

Gleichzeitg ist GitHub aber auch ein soziales Netzwerk for Developer und Unternehmen. Ein GitHub Profil wird ein wertvolles Mittel sein in der zukünftigen Karriere.

> Auch wenn GitHub die beliebteste Online Plattform ist, gibt es noch viele weitere. Beispielsweise Gitlab oder Bitbucket.
