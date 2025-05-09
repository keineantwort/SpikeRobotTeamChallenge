# Spike Robot Team Challenge

Im folgenden werden die Aufgaben zur Spike Robot Team Challenge beschrieben.

## Was?

Die Teams müssen einen Roboter bauen, welcher mittels Micropython programmiert wird. Der Roboter soll ein selbst gebautes Objekt in einen Zielbereich fahren. Dabei wird der Ablageort (Felder 3) von der Jury kurz vor Start des Wertungslaufs zufällig festgelegt.

1. Das Startfeld ist cyan.
1. Das Zielfeld ist leuchtgelb.
1. Die möglichen Platzierungen für das Objekt sind violett.

![Spielfeld](img/Spielfeld.svg)

## Wer?

Jedes Team hat 8-9 Teammitglieder (s. Namensschild). Die Teams strukturieren sich selbst.

## Womit?

Jedes Team bekommt [Lego Education SPIKE Prime](https://education.lego.com/de-de/products/lego-education-spike-prime-set/45678/) Set. Aus diesem Set wird der Roboter, das Zielfeld und das Objekt gebaut.

Programmiert wird in Micropython. Die SPIKE Steine sind mit [PyBricks](https://docs.pybricks.com/en/stable/) versehen.

Als IDE kann jede beliebige IDE zur Entwicklung mit Micropython verwendet werden. Beispielsweise [PyCharm](https://www.jetbrains.com/de-de/pycharm/download/) oder [VS Code](https://pybricks.com/project/pybricks-other-editors/) verwendet werden.
Wir empfehlen aber [PyBricks Web Editor](https://code.pybricks.com/).

_**Am Ende muss alles wieder auseinander gebaut und wieder in den Kästen verstaut sein.**_

## Bewertung

Es finden 2 Wertungsläufe statt. Der erste Lauf startet direkt nach dem Mittagessen. Der zweite Lauf 1h vor dem Ende. Die Wertungsläufe finden in zufälliger Reihenfolge statt. Pünktlich zum Wertungslauf müssen die Roboter startbereit auf dem Tisch im Startfeld des eigenen Spielfelds stehen.

_**Die Punkte des besseren Laufs zählen am Ende.**_

### Aufgabe Schnelligkeit

Für Schnelligkeit gibt es Punkte: Der schnellste Roboter erhält 10 Punkte, der zweit schnellste 5 Punkte.

### Aufgabe Objekt

Das Team muss ein Objekt entwerfen und bauen, welches vom Roboter aufgenommen werden kann und in das Zielfeld passt. Der Roboter muss dieses Objekt an einem der beiden violetten Felder einsammeln und zum Zielfeld bringen. Das Objekt wird von der Jury direkt vor dem Lauf zufällig auf einem der beiden Felder platziert.

**Anforderungen Objekt:**

| Akzeptanzkriterium | Punkte |
| ------------------ | ------ |
| Objekt auf Basis konstruiert | 5 |
| Basis liegt flach | 5 |
| Objekt außerhalb des Objektfelds ohne Bodenkontakt | 5 |
| **Gesamt** | **max. 15** |

![Basis](img/Basis-Objekt.jpg)

![Objekt im Zielfeld](img/Objekt-im-Zielfeld.jpg)

### Aufgabe Zielfeld

Es wird ein Zielfeld gebaut, welches wie folgt aufgebaut ist:

![Zielfeld](img/Zielfeld_1.jpg)

![Zielfeld](img/Zielfeld_2.jpg)

![Zielfeld](img/Zielfeld_3.jpg)

Das Zielfeld wird spätestens zum Start des Wertungslauf auf dem Spielfeld im dafür vorgesehenen Feld platziert.

Das Objekt muss zum Zielfeld transportiert werden und **in** diesem abgelegt werden. Dabei darf das Zielfeld nicht verschoben werden.

| Akzeptanzkriterium | Punkte |
| ------------------ | ------ |
| Objekt vollständig im Zielfeld | 10 |
| Objekt teilweise im Zielfeld | 5 |
| Zielfeld nicht verschoben | 5 |
| **Gesamt** | **max. 20** |

### Aufgabe Parkposition

Nachdem der Roboter das Objekt abgesetzt hat, muss er zurück zur Startposition fahren und dort stehen bleiben.

| Akzeptanzkriterium | Punkte |
| ------------------ | ------ |
| Roboter vollständig im Startfeld | 10 |
| Roboter berührt das Startfeld | 5 |
| **Gesamt** | **max. 10** |

### Überraschungsaufgabe

Die Überraschungsaufgabe wird 1:00h nach Beginn der Challenge bekannt gegeben und bringt bis zu 10 weitere Punkte.

| Akzeptanzkriterium | Punkte |
| ------------------ | ------ |
| Überraschungsaufgabe Top 1 | 10 |
| Überraschungsaufgabe Top 2 |  6 |
| Überraschungsaufgabe Top 3 |  3 |
| **Gesamt** | **max. 10** |

## Entwicklungs-Umgebung

Entwickelt wird in Micropython mit PyBricks
  
### Python Virtual Environment

- [PyBricks](https://pybricks.com/) Version 3.6.0
- pybricksdev Version 1.0.1 um via BT zu installieren

### IDE Hilfe

- [PyBricks Code](https://code.pybricks.com/) (**empfohlen**)
- PyCharm
  - [PyCharm Download](https://www.jetbrains.com/de-de/pycharm/download/)
  - ![PyCharm RunConfig](img/PyCharm-Bluetooth-RunConfig.png)
- Visual Studio Code
  - [VS Code](https://pybricks.com/project/pybricks-other-editors/)
  - [PyBricks VS Code Anleitung](https://pybricks.com/project/pybricks-other-editors/)
