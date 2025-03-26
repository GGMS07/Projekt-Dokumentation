# Einrichtung des Projekts

## Projekt einrichten

1. **Repository klonen:**
   ```bash
   git clone https://github.com/dein-username/fussball-dokumentation.git
   cd fussball-dokumentation
   ```

2. **Abhaengigkeiten installieren:**
   ```bash
   npm install
   ```

3. **GitHub Pages aktivieren:**
   - Gehe zu den **Repository-Einstellungen** auf GitHub.
   - Scrolle zu **GitHub Pages**.
   - Waehle den Branch `main` oder den Ordner `docs` als Quelle.
   - Optional: Waehle ein Theme, z. B. "Cayman".

4. **Lokale Vorschau anzeigen:**
   Falls du MkDocs oder ein aehnliches Tool verwendest, kannst du eine lokale Vorschau starten:
   ```bash
   mkdocs serve
   ```
   Dann kannst du die Dokumentation unter `http://127.0.0.1:8000/` im Browser aufrufen.
