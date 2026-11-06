# Flow – persönlicher Habittracker

Version 11 – Vorhaben & Jahreszeiten. Statische App, vorbereitet für GitHub Pages.

## Veröffentlichung
Den Inhalt dieses Ordners im Repository-Root ablegen. index.html, app.js, styles.css, sw.js, manifest.webmanifest, beide Icons und leinenruhe.jpg gehören zusammen.
Settings > Pages > Deploy from a branch > main > / (root) > Save.
Die veröffentlichte Adresse steht unter Settings > Pages.

## Persönliche Daten NICHT ins Repository
Keine JSON-Backups, Stimmungsnotizen, privaten Fotos oder Zugangsdaten hochladen. Auf GitHub Free ist das für Pages verwendete Repository öffentlich. Die App speichert persönliche Eingaben lokal im jeweiligen Browser und überträgt sie nicht an einen eigenen App-Server. Ein Website-Link ist kein Passwortschutz.

## Umzug von Netlify
Alte App im bisherigen Handy-Browser öffnen, unter Zahnrad ein Backup herunterladen. Neue GitHub-Pages-Adresse im selben Handy-Browser öffnen, unter Zahnrad Backup importieren. Nicht in GitHub hochladen! Import ersetzt den lokalen Stand der neuen Adresse. Alte Seite erst nach Kontrolle aufgeben.

## Funktionen
Routinen, To-dos, Mengen/Minuten, Unteraufgaben, Kalender, Ziehsortierung, Stimmung mit vier Segmenten, individuelle Hintergründe, Abzeichen, Routine-Challenges und neue einmalige/saisonale Vorhaben sowie eine 21-Tage-Challenge. Alle Dialoge haben oben rechts ein X.
Die neuen Vorhaben werden getrennt von den bisherigen Routine-Logs unter journeys gespeichert. Alte Datenfelder und Badge-IDs bleiben erhalten.

## Grenzen
Kein Cloud-Sync, keine Benachrichtigungen, keine nativen Widgets. Lokale Daten können bei Browserbereinigung verloren gehen: extern sichern. Kein auf echtem Android/Opera abgeschlossener visueller Test. Offline nach vollständigem Online-Laden selbst prüfen.

## Technischer Aufbau
index.html: Grundstruktur und Dialog-X.
styles.css: Gestaltung.
app.js: App und lokale Daten.
sw.js: Offline-Grundlage, relative URLs und Cache je Projektpfad.
manifest.webmanifest: relative Startadresse für GitHub-Projektseiten.
leinenruhe.jpg: integrierter Hintergrund.
.nojekyll: statische Veröffentlichung ohne Jekyll-Verarbeitung.

## Quellen zur Veröffentlichung
https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages
