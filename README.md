# Parabel-Labor

Interaktive HTML-App zum Erkunden von f(x) = ax², optimiert für die Bedienung mit dem Finger auf dem iPad.

## Funktionen

- Normalparabel als ständiger Vergleich.
- Zufällige Aufgaben mit positiven und negativen rationalen Faktoren, ohne 0 und 1.
- Drei fehlende x- oder y-Werte (bei x wird jede passende der beiden Lösungen akzeptiert); Eingabe als Dezimalzahl mit Komma/Punkt oder als Bruch.
- Drei verschiedene Punkte durch Antippen setzen; erneutes Antippen entfernt einen Punkt.
- Lösungsprüfung und Einblendung der gesuchten Parabel bei richtigen Punkten.
- **Achsenskalierung immer 1:1:** Eine Einheit auf x und y ist gleich lang. Der sichtbare Ausschnitt passt sich an die Aufgabe an. Das gilt auch im Hoch- und Querformat.
- Aufklappbare „Tipps zum Rechenweg“ mit Beispielrechnungen.
- Hilfslinien auf beiden Achsen im Abstand 0,5; feinere Einrastschritte für exakte Bruchwerte.
- Tastaturbedienung: Koordinatensystem fokussieren, Pfeiltasten und Enter verwenden.

## Auf GitHub hochladen

1. Neues Repository auf GitHub erstellen oder ein vorhandenes öffnen.
2. Über **Add file → Upload files** die Dateien dieses Ordners hochladen. `index.html` gehört direkt in das Hauptverzeichnis des Repositorys, nicht in einen Unterordner.
3. Änderungen mit **Commit changes** speichern.
4. Unter **Settings → Pages → Build and deployment** die Quelle **Deploy from a branch** wählen.
5. Branch `main` und Ordner `/ (root)` auswählen und speichern.
6. Nach der Bereitstellung zeigt GitHub Pages dort die Adresse der App an. Diese in Safari auf dem iPad öffnen; optional über „Teilen → Zum Home-Bildschirm“ ablegen.

Die Verfügbarkeit von GitHub Pages für private Repositorys hängt vom GitHub-Tarif ab.

## Lokal verwenden

`index.html` in einem Browser öffnen. Die App besteht aus einer eigenständigen Datei und benötigt keine Installation, keine externen Bibliotheken und keinen Build-Schritt. Es werden keine Daten an einen Server gesendet.

## Dateien

- `index.html`: gesamte App inklusive Gestaltung und Logik
- `.nojekyll`: deaktiviert die Jekyll-Verarbeitung auf GitHub Pages
- `README.md`: diese Anleitung
