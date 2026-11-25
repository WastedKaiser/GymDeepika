# GymDeepika 💖

Deepikas 4er-Split als Handy-App (Web-App/PWA): Trainingstag antippen, durch die Übungen scrollen, Technik-Tipps lesen, MuscleWiki-Video öffnen, Gewichte eintragen, Pause-Timer nutzen.

## Online stellen (GitHub Pages)
1. Auf github.com ein neues Repository **GymDeepika** anlegen (Public).
2. „Add file → Upload files“ → alle Dateien aus diesem Ordner hochladen (inkl. Ordner `icons`) → Commit.
3. **Settings → Pages** → Source: „Deploy from a branch“, Branch `main`, Ordner `/ (root)` → Save.
4. Nach ca. 1 Minute läuft die App unter `https://<dein-name>.github.io/GymDeepika/`.

## Auf dem iPhone installieren
Link in **Safari** öffnen → Teilen-Symbol → **„Zum Home-Bildschirm“** → Hinzufügen. Die App startet dann im Vollbild wie eine echte App und funktioniert auch offline.

## Anpassen
- Übungen, Tipps und Aufwärmen stehen in `data.js`.
- Für ein Video direkt in der App: bei einer Übung `video: "https://…/datei.mp4"` eintragen.
- Nach Änderungen in `sw.js` die Version (`gymdeepika-v1` → `v2`) erhöhen, damit das iPhone die neue Version lädt.

Gewichte werden nur lokal auf dem Handy gespeichert.
