# Silas Maissen – Website (SILAS)

**Sofort auf GitHub Pages veröffentlichbare, professionelle Onepager-Website für Silas Maissen.**

---

## INHALT / CONTENTS

- [index.html](index.html)
- [images/](images/)
  - hero-mountain.svg, silas-portrait-placeholder.jpg, portfolio-before-x.jpg, portfolio-after-x.jpg, map-disentis-placeholder.jpg
- [LICENSE](LICENSE) (MIT)
- [CNAME](CNAME) (leer, für Ihre eigene Domain)
- [README.md](README.md) (dieses Dokument, Anleitungen in Deutsch und Englisch)

---

## Bearbeiten & Anpassen (DE)

### Texte ändern

- **ALLE Texte finden Sie strukturiert in `index.html`!**
- Inline in HTML gibt es `<!-- DEUTSCHER HINWEIS ... -->`-Kommentare, <br>
  die genau darauf hinweisen, wo Sie etwas editieren können: Titel, Einleitung, Dienstleistung, Kontakt, Impressum etc.
- Öffnen Sie `index.html` mit einem Texteditor und passen Sie alle Texte direkt vor Ort an.

### Bilder ersetzen

- **Bilder liegen in `images/`.**
- `silas-portrait-placeholder.jpg`: Portrait-Foto (optimale Größe: 320x400px, jpg, weboptimiert).
- `portfolio-before-1.jpg` / `portfolio-after-1.jpg` / ...: Eigene Fotos für Portfolio (max 800px Breite, jpg).
- `map-disentis-placeholder.jpg`: Ausschnitt von Disentis (z.B. Screenshot von Google Maps). <br>
  (Hinweis: Google verlangt einen Quellenvermerk bei direktem Screenshot – siehe images/README.txt).
- Alt-Attribute in `index.html` anpassen/nachpflegen.

### Farben, Links, Telefonnummer

- Farben können Sie im `<style>`-Abschnitt in `index.html` oben editieren (`:root`).
- Telefonnummer/WhatsApp im Header + Kontaktbereich (`tel:` / `wa.me`) ändern – Einträge gut markiert mit Kommentar.
- Social-Links im Footer editieren oder entfernen.

### Deployment auf GitHub Pages

1. Repository auf GitHub anlegen, z.B. `SILAS`.
2. Alle Dateien hochladen (`index.html`, `images/` usw.).<br>
   (Am einfachsten: alles mit Git pushen oder per Drag & Drop in den GitHub-Webeditor).
3. Auf GitHub: Repository → „Settings“ → „Pages“ → Branch auswählen (z.B. `main`), Ordner `/root` setzen.
4. Nach ca. 2 min ist Ihre Seite online (z.B. https://USERNAME.github.io/SILAS).

### Eigene Domain einrichten

- Tragen Sie die gewünschte Domain einfach **in die `CNAME`-Datei** (ohne `https://`), speichern, und GitHub Pages erkennt dies.
- DNS-Einstellungen bei Ihrem Provider entsprechend anpassen. Siehe [GitHub Docs](https://docs.github.com/pages/configuring-a-custom-domain-for-your-github-pages-site).

### Accessibility / Barrierefreiheit

- Alle Bereiche sind mit Landmarken und sinnvollen `aria-`-Attributen versehen.
- Alle Bilder haben `alt`-Attribute mit Hinweisen zur Anpassung.
- Fokus-Rahmen, Tastaturnavigation und ausreichende Farbkontraste sind sichergestellt.

### Datenschutz / DSGVO

- Die Website **setzt keine Cookies und verwendet keine externen Tracking- oder Analytics-Skripte.**
- Im Footer findet sich ein Hinweistext. Für eigene Datenschutzerklärungen können Sie das beiliegende [datenschutz-template.txt](datenschutz-template.txt) verwenden/weiterentwickeln.
- Für Kontaktformulare via `mailto` muss der Datenschutz trotzdem beachtet werden.

---

## Edit & Deploy Instructions (ENGLISH)

### Editing Content

- **ALL content is in `index.html`!**
- Look for `<!-- DEUTSCHER HINWEIS ... -->` HTML comments showing exactly where to change each text (intro, services, contact info, privacy etc.).
- You may use any text editor to open and edit `index.html`.

### Replacing Images

- Place your images inside the `images/` folder:
  - `silas-portrait-placeholder.jpg`: Swap with a real portrait (optimal: 320x400px, web-optimized JPG).
  - `portfolio-before-1.jpg`/`portfolio-after-1.jpg` etc: Photos of your projects (max 800px wide).
  - `map-disentis-placeholder.jpg`: Custom map image; see images/README.txt for guidance.
- Update alt texts in `index.html` and README.txt if needed.

### Changing Colors, Phone/WhatsApp

- Edit the color palette in the `<style>` of `index.html` in the `:root` section at the top.
- Change the telephone and WhatsApp numbers & links in the header/contact – each place is marked with a clear comment.
- Update or remove social media links and icons in the footer.

### Deploy to GitHub Pages

1. Create a repository on GitHub (e.g., `SILAS`).
2. Upload all files (`index.html`, `images/` folder, etc). You can use drag-and-drop or Git push.
3. In GitHub → Repository → Settings → Pages: select a branch (e.g. `main`), directory `/root`.
4. In 2-3 minutes, the site is live (e.g. https://USERNAME.github.io/SILAS).

### Setting Up a Custom Domain

- Enter your desired domain name in the `CNAME` file (delete any existing contents).
- Adjust DNS records at your registrar as needed. See [GitHub Docs](https://docs.github.com/pages/configuring-a-custom-domain-for-your-github-pages-site).

### Accessibility

- All page regions have ARIA landmarks and meaningful landmark roles.
- Every image has descriptive `alt`-text. Replace when you swap images.
- Focus outlines, keyboard navigation and high-contrast color scheme are built in.

### Privacy / GDPR

- The website **does NOT use any cookies, analytics, or user tracking**.
- A privacy statement and template is included. Adjust and include your own if required, especially when using contact forms.

### Other Customization

- If you prefer separate files for CSS/JS, you may extract the `<style>` and `<script>` into `styles.css`/`script.js` and reference them in `index.html`.
- All sections, links, and features can be freely edited in one file.

---

## Attribution

- All images in `images/` are sample/placeholder only. Please replace for production.
- Mountain SVG is custom (or generated with undraw.co, see images/README.txt).
- No icon fonts, all icons are inline SVG for best accessibility.

---

## LICENSE

MIT License (see LICENSE file).
