# admkrs · Hub

Das interne Plattform-Portal der **ADMKRS GmbH** — eine statische Seite, die alle Tools, Plattformen und Benefits als Kacheln an einem Ort bündelt. Dient zugleich als Onboarding-Startpunkt für neue Kolleg:innen.

**Live:** https://burakaz.github.io/admkrs-portal/

## Pflege

Der gesamte Inhalt steckt in `index.html` (eine einzige, selbst-enthaltene Datei).

Eine Plattform hinzufügen oder ändern: den passenden `<a class="tile …">`-Block in der jeweiligen Kategorie kopieren bzw. anpassen — Name, Beschreibung, URL, Domain und das Inline-SVG-Icon. Danach committen und pushen; GitHub Pages aktualisiert die Seite automatisch.

## Tech

- Eine statische `index.html` mit Inline-CSS und etwas Vanilla-JS (Live-Suche, Scroll-Spy, sanfte Reveal-Animationen) — **kein** Build-Schritt, keine Abhängigkeiten.
- Gehostet über **GitHub Pages** (Branch `main`, Root).
- Icons sind **Inline-SVGs**: echte Marken-Logos für Drittanbieter (Slack, Google Drive, ClickUp, Personio) und eigens gestaltete neon-grüne Glyphen für die internen Tools (Ad Agent, OKR Tracker, Vault) sowie Frame.io, Mitarbeiterangebote und pxtra.

---

Performance Marketing & High-Quality Creative — von und für ADMKRS.
