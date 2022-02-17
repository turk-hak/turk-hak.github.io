
## Wie man einen Beitrag erstellt

Datei erstellen unter https://github.com/turk-hak/turk-hak.github.io:
- Gehe ins Verzeichnis "_posts", 
- dort dann per "Add File" eine neue Datei anlegen, 
  - man muss ihr einen Namen geben nach dem Muster "Datum-Überschriftstext", also z.B. 2022-12-31-Das-ist-die Überschrift"

Datei editieren:
Der ganz oben befindliche Text (ohne die vorangestellten ##) erscheint dann später als Überschrift des Blogeintrags. Falls eine Beitragsdatei nicht mit "## Überschriftstext" startet, wird der Teil hinter dem Datum im Dateinamen genommen

Um ein Bild in einen Blogeintrag einzufügen:
- in Github das Wurzel-Verzeichnis öffnen
- das Bild per Maus aus dem eigenen Rechnerordner dorthin verschieben, d.h. das Bild über das Verzeichnis ziehen, bis Upload erscheint
- "Commit changes" anklicken
- zum Beitrag gehen und ihn zum Schreiben öffnen
- an der Stelle wo das Bild erscheinen soll: ![Bildtitel](/Bildname)
  - also z.B. \![MeinBild](/meinBild.jpg)
- "Commit changes" anklicken

Relativer Pfad als Bildname (/Rocket_Raccoon.jpg):

![Guardians of the Galaxy: Rocket](/Rocket_Raccoon.jpg)


Absoluter Pfad als Bildname (https://raw.githubusercontent.com/turk-hak/turk-hak.github.io/main/Rocket_Raccoon.jpg):
![Guardians of the Galaxy: Rocket](https://raw.githubusercontent.com/turk-hak/turk-hak.github.io/main/Rocket_Raccoon.jpg)
