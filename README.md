# Die verfluchten Märchen von Gschwend – interaktives Hörspiel

## Installation auf GitHub Pages

1. Im Repository `marcuss-bit/maerchenwald-gschwend` die vorhandene `index.html` durch diese Version ersetzen.
2. Den **gesamten Ordner `bilder`** mit `station-1.webp` bis `station-6.webp` ins Hauptverzeichnis des Repositorys hochladen (Pfad muss `bilder/station-1.webp` sein).
3. Unter Settings → Pages `Deploy from a branch`, `main`, `/ (root)` aktivieren.
4. Die sechs Links `#start`, `#hexenhaus`, `#dornroeschen`, `#laternen`, `#waldhueter`, `#finale` testen.

## Audio

Die Waldgeräusche und unheimlichen Melodien werden **im Browser synthetisiert** (Web Audio API), nicht als aufgenommene Musikdateien geliefert. Die Geschichte wird über die auf dem jeweiligen Gerät verfügbare deutsche Sprachausgabe gesprochen (Web Speech API). Stimme und Qualität unterscheiden sich je nach Gerät; ohne deutsche Stimme kann die Aussprache abweichen. Auf Mobilgeräten startet Audio nur nach Tipp auf den Startknopf. Vorlesen ist separat startbar; der Ton ist abschaltbar. Bei langsamer Verbindung bleiben Text und Rätsel benutzbar.

## Bilder

Sechs atmosphärische Szenenausschnitte aus einer für dieses Projekt erzeugten Illustration. Keine externen Bildserver nötig.

## Wichtig

Diese Version ist noch ein Teststand. Vor öffentlichem Einsatz Veranstalterkontakt, Genehmigungen und sichere Schilderstandorte ergänzen. Keine Hinweise, die Besucher vom offiziellen Weg führen. QR-Codes aus der bestehenden Druckvorlage verweisen auf dieselben Stations-URLs.
