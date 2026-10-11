# Die verfluchten Märchen von Gschwend – Horror-Update

GitHub Pages: **Den gesamten Inhalt dieses Ordners direkt in das Stammverzeichnis des bestehenden Repositories hochladen.** Die vorhandenen QR-Codes und deren Freischaltschlüssel bleiben unverändert.

## Neu
- Sieben **unterschiedliche**, eigens synthetisierte, beklemmende Loop-Klangkulissen (Badsee, Hexenhaus, Schneiderin, Friedhof, Waldhüter, Kreuzstein, Finale).
- Sound-Testschaltflächen und Diagnosetestplayer aus der Oberfläche entfernt.
- Hexenlachen tiefer, mit mehr Hall und Echo aus dem bisherigen Audio bearbeitet (kein neues eingesprochenes Lachen).
- Animierte Siegerurkunde nach erfolgreichem Finale; Rücksicht auf `prefers-reduced-motion`.
- Einzelnes Rätsel zurücksetzen: behält QR-Freischaltung, entfernt das zugehörige Siegel; bei Rücksetzen einer Voraussetzung wird das Finale wieder gesperrt.
- Gesamten Fortschritt löschen: löscht auch QR-Freischaltungen; alle Codes müssen neu gescannt werden. Zwei Sicherheitsabfragen.

## Beibehalten
Sieben Stationen, Badsee-Start, Lösungswort ERLÖSUNG, Rätselantworten, QR-SHA256-Prüfung, lokale Speicherung, Mobilbrowser-Audio-Fallback, Vorlesefunktion, Erfolgs-/Fehleranimationen und vorhandene übrige Audiodateien.

## Hinweis
Mobilbrowser können automatischen Ton beim QR-Scan blockieren. Der sichtbare Knopf **Stationsklänge starten** ist deshalb bewusst erhalten – er ist kein Sound-Testknopf. Bitte die sieben Stationen und den finalen Ablauf auf echten Android- und iPhone-Geräten testen.


## Schreckeffekte (Update)

Die Web-App bietet jetzt vier Schreckstufen: Aus, Sanft, Gruselig (Standard) und Extrem.
Jede Station zeigt bei falscher Antwort einen eigenen visuellen Effekt. In der Stufe Sanft
wird kein Hexenlachen abgespielt; bei Aus sind die zusätzlichen Schreckeffekte deaktiviert.
Die Einstellung wird lokal im Browser gespeichert und kann jederzeit geändert werden.
Die Lautstärke des Hexenlachens ist begrenzt; es gibt keine Stroboskopeffekte.
Alle QR-Schlüssel, Antworten, Speicherstände und vorhandenen Audiodateien bleiben unverändert.
