# Jonas Blog (Deutsches README)

Willkommen zu Jonas Blog!

Dies ist ein einfaches Blog-Projekt, das für das Hosting auf GitHub Pages entwickelt wurde. Es ermöglicht Benutzern, ihre eigenen Blogbeiträge zu erstellen und zu verwalten, indem sie einfache HTML-Dateien verwenden.

## Über das Projekt

**JonasBlog** ist ein Projekt, das dir ermöglicht, schnell und unkompliziert einen eigenen Blog zu erstellen und online zu stellen. Es ist ideal für alle, die nach einer einfachen Lösung suchen, um ihre Gedanken, Erfahrungen oder ihr Wissen mit der Welt zu teilen.

## So funktioniert’s

1. **Blog-Dateien erstellen:**
   - Für jeden Blogeintrag, den du erstellen möchtest, musst du eine eigene HTML-Datei anlegen (z. B. `blog1.html`, `blog2.html`, `meine-reisen.html` usw.).
   - Diese Dateien enthalten den jeweiligen Inhalt deiner Blogbeiträge.
   - Achte darauf, in jeder Datei eine saubere HTML-Struktur zu verwenden.

2. **Blogs in `index.html` verlinken:**
   - Öffne die Datei `index.html`.
   - Füge für jeden Blogeintrag einen Link zur jeweiligen HTML-Datei hinzu. So gelangt man von der Startseite zu den Blogposts.
   - Jeder Link sollte in folgendem Format stehen:

     ```html
     <a href="blog1.html">Mein erster Blogbeitrag</a>
     ```

     Ersetze `blog1.html` mit dem tatsächlichen Dateinamen und „Mein erster Blogbeitrag“ mit dem Titel deines Beitrags.

3. **Dateien im `JONASBLOG`-Ordner ablegen:**
   - Alle HTML-Dateien (`index.html`, `blog1.html`, `blog2.html` usw.) müssen im Ordner `JONASBLOG` gespeichert werden.
   - Auch die CSS-Datei muss im gleichen Ordner liegen.
   - Wenn du einen neuen Blogbeitrag hinzufügst, erstelle die entsprechende Datei ebenfalls in diesem Ordner.

## Beispiel

Wenn du einen Blogpost namens `mein-italien-trip.html` erstellst, dann fügst du Folgendes zu deiner `index.html` hinzu:

```html
<a href="mein-italien-trip.html">Mein Italien-Trip</a>
