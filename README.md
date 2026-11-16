# contextfilm.com

Statische Website von Contextfilm (HTML, ohne Build-Schritt), gehostet über GitHub Pages mit IONOS-Domain.

## Vor dem Livegang
1. **Impressum** (`impressum.html`) und **Datenschutz** (`datenschutz.html`): alle Angaben in `[eckigen Klammern]` ausfüllen und die orange Hinweisbox löschen. Beides rechtlich prüfen lassen.
2. **Kontaktformular**: In Notion die Datenbank „Contextfilm Kontaktanfragen“ → Ansicht „Website-Formular“ → Teilen → „Jeder mit dem Link kann ausfüllen“. Den Link in `index.html` statt `https://DEIN-NOTION-FORMULAR-LINK` einsetzen.
3. **Schriftarten**: Google Fonts werden extern geladen. Besser lokal einbinden (siehe Hinweis in `datenschutz.html`).

## GitHub Pages
Settings → Pages → Source: „Deploy from a branch“ → diesen Branch, Ordner `/ (root)`.
Eigene Domain: unter „Custom domain“ `contextfilm.com` eintragen und bei IONOS die DNS-Einträge von GitHub Pages setzen.

## Inhalt
- `index.html` – Startseite mit Erklärfilm, Ablauf, FAQ, Kontakt
- `impressum.html`, `datenschutz.html` – Entwürfe
- `img/` – Logo, Favicon, Video-Poster
- `videos/contextfilm-erklaerfilm.mp4` – Erklärfilm (ca. 7,8 MB)
