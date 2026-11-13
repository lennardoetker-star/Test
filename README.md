# Vokabel-Karteikasten

Vokabeln einfügen, als .txt/.csv hochladen oder aus einem Foto erkennen lassen, und wie Karteikarten lernen (5-Fächer-System).
Läuft als Web-App (PWA): zum Home-Bildschirm hinzufügen, dann startet sie im Vollbild und funktioniert auch offline.

## Online stellen (GitHub Pages)

1. Auf GitHub im Repository: **Settings → Pages**
2. Bei *Source* „Deploy from a branch" wählen, Branch `claude/tender-bell-ne4tou`, Ordner `/ (root)`, **Save**
3. Nach ca. 1 Minute ist die App unter `https://lennardoetker-star.github.io/Test/` erreichbar.

## Zum Home-Bildschirm hinzufügen

- **iPhone/iPad (Safari):** Teilen-Symbol → „Zum Home-Bildschirm"
- **Android (Chrome):** Menü ⋮ → „App installieren" bzw. „Zum Startbildschirm hinzufügen"

Die Vokabeln werden auf dem Gerät gespeichert (localStorage).

## KI (optional)

Unter **Einstellungen** einen kostenlosen Gemini-API-Schlüssel von https://aistudio.google.com/apikey eintragen. Dann liest Gemini die Fotos, ordnet Zeilen zu, korrigiert Fehler und entfernt Nicht-Vokabeln.
