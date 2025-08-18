# FrameCalc v16.3

Single-file web app for Fenster-Aufmaß (Innenanschlag) mit:
- Profil-/Kastenlogik (70/80 mm, RAE 185/210)
- Vorbaurollladen (Laibung) Regeln
- Einheitliches Spiegelmaß
- Fotos je Fenster + PDF-Export inkl. Fotos
- Projektkopf (Kommission, Anschrift, Gebäudeart, Zugang, Mauerwerk, …)

## Nutzung lokal
Einfach `index.html` im Browser öffnen.

## GitHub Pages Deploy
1. Neues GitHub-Repo erstellen, z. B. `framecalc`.
2. Diese Dateien committen/pushen (nur `index.html` reicht).
3. **Settings → Pages → Build and deployment**:
   - **Source:** Deploy from a branch
   - **Branch:** `main` (root)
4. Nach dem Build ist die App hier erreichbar:
   `https://<dein-user>.github.io/<repo-name>/`

## Optional
- In `index.html` kannst du den Titel/Logo-Text anpassen.
- Für PWA/Offline später: `manifest.json` + `service worker` ergänzen.
