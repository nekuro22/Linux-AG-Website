# Linux AG Website

Statische Webseite für die Linux / Server / Computer AG des Georg-Herwegh-Gymnasiums.
Reines HTML/CSS/JavaScript, kein Build-Prozess nötig.

## Lokal ansehen

`index.html` einfach im Browser öffnen, oder für einen lokalen Server:

```bash
python -m http.server 8000
```

und dann `http://localhost:8000` aufrufen.

## Struktur

```
index.html          Startseite (alle Inhalte als Sections)
impressum.html       Impressum (Platzhalter)
datenschutz.html      Datenschutzerklärung (Platzhalter)
css/style.css        Styles
js/main.js           Mobile-Navigation, Footer-Jahr, Terminal-Animation
```

## Platzhalter, die noch ausgefüllt werden müssen

- [ ] Betreuende Lehrkraft (Abschnitt "Team", `index.html`)
- [ ] Treffzeit & Raum (Abschnitt "Termine", `index.html`)
- [ ] Echte E-Mail-Adresse statt `linux-ag@herwegh-gymnasium.de` (Abschnitt "Kontakt" & Footer-Mail-Link)
- [ ] Adresse der Schule (Abschnitt "Kontakt")
- [ ] Echte Projekte statt Beispielprojekte (Abschnitt "Projekte")
- [ ] `impressum.html` mit den rechtlich vorgeschriebenen Angaben der Schule
- [ ] `datenschutz.html` mit den tatsächlichen Angaben (Hosting-Anbieter etc.)

## Deployment (z. B. GitHub Pages)

1. Repository auf GitHub pushen.
2. In den Repository-Einstellungen unter "Pages" den `main`-Branch (Ordner `/root`) als Quelle auswählen.
3. Die Seite ist danach unter `https://<benutzername>.github.io/<repo-name>/` erreichbar.
