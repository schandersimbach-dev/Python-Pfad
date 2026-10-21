# Python-Pfad auf dem iPhone installieren

## Voraussetzung

Die App muss unter einer HTTPS-Adresse erreichbar sein. Die aktuelle Datei-Adresse (`file:///…`) funktioniert nur auf diesem Computer und kann nicht auf dem iPhone installiert werden. Der Ordner kann auf einen statischen Webhost gelegt werden; dafür sind keine App-Store-Veröffentlichung und kein Apple-Developer-Konto nötig.

Zum Veröffentlichen müssen diese Dateien zusammen im selben Web-Ordner liegen:

- `index.html`
- `manifest.webmanifest`
- `sw.js`
- `icon.svg`
- der Ordner `icons/`

## Auf dem iPhone hinzufügen

1. Die HTTPS-Adresse in **Safari** öffnen.
2. Auf **Teilen** tippen.
3. **Zum Home-Bildschirm** auswählen.
4. Falls angeboten, **Als Web-App öffnen** eingeschaltet lassen und auf **Hinzufügen** tippen.

Danach startet Python-Pfad über das neue Home-Bildschirm-Symbol. Nach dem ersten Laden kann die App dank Service Worker auch ohne Internetverbindung geöffnet werden.
