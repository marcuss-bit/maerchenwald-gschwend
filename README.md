# Die verfluchten Märchen von Gschwend – Hörspiel-Edition

## Dateien

- `index.html` – komplette interaktive Webseite mit sechs Stationen, Rätseln und moderner Oberfläche
- `bilder/station-1.webp` bis `bilder/station-6.webp` – sechs verschiedene Märchenszenen
- `audio/kapitel-1.mp3` bis `audio/kapitel-6.mp3` – vorproduzierte, synthetisch gesprochene Geschichten
- `audio/wald.mp3` – musikalische Waldatmosphäre mit Natur- und Mystery-Klängen
- `audio/ton-test.mp3` – drei klar hörbare Prüftöne
- `audio/finale.mp3` – vertonte Auflösung mit zusätzlicher musikalischer Untermalung
- `vorschau-desktop.png`, `vorschau-mobil.png` – Bildschirmansichten

## Auf GitHub Pages veröffentlichen

1. ZIP herunterladen und entpacken.
2. Das Repository `marcuss-bit/maerchenwald-gschwend` öffnen.
3. **Den Inhalt** dieses Pakets in den Stamm des `main`-Branches hochladen. `index.html` muss direkt im Repository-Hauptverzeichnis liegen.
4. **Beide Ordner `bilder` und `audio` mitsamt Inhalt** übernehmen (nicht nur `index.html` hochladen). Wenn die Ordner bereits vorhanden sind, Dateien entsprechend ersetzen.
5. Unter `Settings > Pages` die Einstellung `Deploy from a branch` / `main` / `/(root)` prüfen.
6. Nach dem grünen Pages-Deployment prüfen: https://marcuss-bit.github.io/maerchenwald-gschwend/

**Wichtig:** Die App greift ausschließlich auf relative, lokal mitgelieferte Bilder und MP3s zu. Es ist kein externer Audiodienst und keine installierte TTS-Stimme nötig. Die Erzählungen haben eine synthetische Computerstimme (kein professionelles Hörspielsprecher-Ensemble). Die Waldmusik ist ebenfalls synthetisch erzeugt. Ton startet erst nach einem Fingertipp, weil iOS und Android automatisches Abspielen oft blockieren.

## Erhalt der sechs QR-Adressen

- `#start` – Rotkäppchen
- `#hexenhaus` – Hänsel & Gretel
- `#dornroeschen` – Dornröschen
- `#laternen` – Die zwölf Lichter
- `#waldhueter` – Silvans Versprechen
- `#finale` – Die dreizehnte Seite

Auch `#rotkaeppchen` öffnet die erste Station.

## Funktionsprüfung

Unterstützte Abläufe: alle Stationen direkt aufrufbar, fünf Buchstaben L-I-C-H-T sammeln, Fortschritt im Browser speichern, Finalwort `LICHT` eingeben, finale Erzählung hören. Die Tasten `Ton testen`, `Waldklänge starten/pausieren` und `Geschichte anhören/pausieren` nutzen reguläre HTML5-MP3-Wiedergabe. Zusätzlich gibt es unter **„Kein Ton? Diagnose“** einen separaten System-Audioplayer zum Gegencheck.

**Bei keinem Ton:** Webseite direkt in Safari oder Chrome öffnen, über `Ton testen` starten, Mediendevice-Lautstärke prüfen, den alternativen Player ausprobieren. Falls die Browser-Seite einen MP3-Dateifehler anzeigt, prüfen, ob `audio` tatsächlich auf GitHub liegt. Auf iPhone muss der erste Audio-Start durch eine Interaktion erfolgen. Einige Geräte, Browser-Erweiterungen und Unternehmensrichtlinien können die Wiedergabe dennoch blockieren.

## Hinweis

Die Web-App enthält bewusst keinen Veranstalter-/Impressumsabschnitt. Ob für die spätere öffentliche Bereitstellung rechtliche Pflichtangaben nötig sind, muss vor dem tatsächlichen Einsatz separat geklärt werden. Die QR-Schilder, Wegpunkte und die Veranstaltungsgenehmigung gehören nicht zu diesem ZIP.
