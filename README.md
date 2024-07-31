# Abfrage der SRU-Schnittstelle des VD17 und Visualisierung
Das Verzeichnis der Drucke des deutschprachigen Raumes (VD17) verzeichnet alle Drucke des 17. Jahrhunderts in deutschen Einrichtungen.
Der Code dieses Notebooks basiert auf https://github.com/F-Quaasdorf/VD17sru und beschreibt, wie die Schnittstelle des VD17 abgefragt werden kann.

### SRU-Schnittstelle des VD17
Die Schnittstelle ist hierunter erreichbar: http://sru.k10plus.de/vd17
Gesucht wird über die PICA-Abfrage:
- `pica.tit` für den Titel
- `pica.jah` für Jahresangaben
- `pica.per` für Personen
- `pica.vlo` für Ortsangaben

Die Treffer werden als MARC21-XML abgefragt und ausgewertet.

### Visualisierung
Der Code für die Visualisierung umfasst:
- Anzahl der Treffer in den haltenden Einrichtungen
- Verteilung der Treffer auf die Jahre
- Verteilung der Treffer auf die Sprachen der Werke
- Verteilung der Sprache der Werke nach Jahren
