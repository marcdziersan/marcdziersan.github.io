# Marcus Dziersan · Filmografisches Onefile-Portfolio

![Status](https://img.shields.io/badge/status-portfolio--ready-brightgreen)
![Tech](https://img.shields.io/badge/stack-HTML5%20%7C%20CSS3%20%7C%20JavaScript-blue)
![Layout](https://img.shields.io/badge/layout-mobile--first-lightgrey)
![Dependencies](https://img.shields.io/badge/dependencies-none-success)

Ein filmografisches, animiertes und vollständig eigenständiges Portfolio als **Onefile-HTML**. Die Seite stellt Marcus Dziersan als angehenden Fachinformatiker für Anwendungsentwicklung vor und verbindet persönlichen Werdegang, Umschulung, technische Haltung und reale Lern-/Portfolio-Projekte in einer modernen Präsentationsseite.

Die Seite ist bewusst ohne Frameworks, ohne externe Libraries und ohne Build-Prozess umgesetzt. Sie kann direkt als `index.html` auf GitHub Pages, einem Webspace oder einer eigenen Domain veröffentlicht werden.

---

## Vorschau

**Konzept:** Kino-/Terminal-Optik, filmische Kapitelstruktur, mobile-first Layout, animierte Projektkarten und klare Entwicklerpositionierung.

**Inhaltlicher Fokus:**

- Umschulung zum Fachinformatiker Anwendungsentwicklung
- Praxisorientierte Softwareprojekte
- PHP, OOP, MVC, SQL, JSON, JavaScript, Java und Python
- Dokumentation, saubere Struktur und nachvollziehbare Lernkurve
- Digitalisierung mit Blick auf Menschen, Nutzbarkeit und Wartbarkeit

---

## Features

- **Onefile-Portfolio**: HTML, CSS und JavaScript in einer Datei
- **Mobile-first Design** mit responsivem Desktop-Layout
- **Filmografische Optik** mit Szenen, Glow, Filmgrain, Timeline und Terminal-Elementen
- **Animierte Scroll-Reveals** über IntersectionObserver
- **Scroll-Fortschrittsbalken**
- **Projektfilter** für unterschiedliche Projektbereiche
- **Projektkarten** mit realen Portfolio- und Lernprojekten
- **Skill-Matrix** für Web, Backend, Frontend, Daten, Desktop, Python und Hardware
- **Profilbild mit Fallback**:
  - externes LinkedIn-Bild als Primärquelle
  - eingebettetes Base64-Bild als JavaScript- und CSS-Fallback
- **SEO-Basis**:
  - Meta Description
  - OpenGraph-Daten
  - Canonical URL
  - JSON-LD Person Schema
- **Rechtlicher Footer**:
  - Impressum
  - Datenschutz
  - Hinweise zu Tracking, Cookies, Server-Logs und Kontaktaufnahme
- **Keine externen Abhängigkeiten**:
  - keine CDN-Dateien
  - keine externen Fonts
  - keine Frameworks
  - kein Docker

---

## Projektstruktur

Da es sich um ein Onefile-Projekt handelt, ist die Struktur bewusst minimal:

```text
.
├── index.html      # vollständige Portfolio-Seite
└── README.md       # Projektdokumentation
```

Optional kann die HTML-Datei auch anders benannt sein, zum Beispiel:

```text
marcus-filmportfolio-onefile.html
```

Für GitHub Pages oder klassischen Webspace empfiehlt sich jedoch:

```text
index.html
```

---

## Technischer Stack

| Bereich | Umsetzung |
|---|---|
| Markup | HTML5 |
| Styling | CSS3, Custom Properties, Grid, Flexbox, Media Queries |
| Interaktion | Vanilla JavaScript |
| Animation | CSS-Keyframes, IntersectionObserver, Scroll-Progress |
| Bilder | externes Profilbild plus Base64-Fallback |
| SEO | Meta-Tags, OpenGraph, JSON-LD |
| Deployment | statisches Hosting, GitHub Pages, Webspace |

---

## Inhaltliche Kapitel

Die Seite ist wie eine filmische Vorstellung aufgebaut:

1. **Hero / Intro**  
   Kurze Positionierung: Entwicklerprofil, Stack, Motto und Profilbild.

2. **Profil**  
   Vorstellung: Wer bin ich? Was mache ich? Warum Softwareentwicklung?

3. **Timeline**  
   Entwicklung von frühen Web-Erfahrungen über berufliche Umwege bis zur Umschulung FIAE.

4. **Projekte**  
   Projektgalerie mit praktischen Anwendungen, Frameworks, Tools, Lernprojekten und Hardware-Projekten.

5. **Skills**  
   Technische Schwerpunkte und Kompetenzfelder.

6. **Haltung**  
   Grundsätze zu Digitalisierung, Sicherheit, Dokumentation, UX und Lernkurve.

7. **Kontakt**  
   Verweise auf GitHub, Portfolio-Domain und berufliche Anschlussfähigkeit.

8. **Rechtliches**  
   Impressum und Datenschutz direkt in der Seite.

---

## Enthaltene Projektbeispiele

Die Portfolio-Seite nennt unter anderem folgende Projekte:

- **HaushaltsPilot** – Haushalts-, Todo-, Kalender- und Einkaufslisten-Anwendung
- **O2DB Modern Framework** – PHP-8+-Datenbankframework mit PDO, MySQLi und SQLite
- **Kanban Light** – Aufgabenverwaltung und IHK-/Umschulungsprojekt-Kontext
- **Marbyte / AP2 Lernplattform** – Lern- und Prüfungsplattform
- **JSON Harbor** – JSON-Validator, Comparator und Lernprojekt ohne externe Libraries
- **ICE Notfall QR System** – Demo für online verwaltbare Notfallinformationen
- **Thermo Printer Tool** – Python-Tool für Text- und QR-Druck
- **DOS Banana** – Java/Swing-Gameprojekt
- **Winpolis / Hausverwalter** – Desktop- und Simulationsprojekte
- **FireKids** – Lernspiel-/Quizidee für Kinder
- **YGO Local Catalog** – Python/Tk/SQLite-Kartenkatalog
- **Rheinturm Uhr & NavPocket** – Arduino-/ESP32-/GPS-/LED-Projekte

---

## Lokale Nutzung

### Variante 1: Direkt öffnen

Die Datei kann direkt im Browser geöffnet werden:

```text
index.html doppelklicken
```

### Variante 2: Lokaler PHP-Server

Falls du ohnehin mit PHP arbeitest:

```bash
php -S localhost:8000
```

Danach im Browser öffnen:

```text
http://localhost:8000
```

### Variante 3: Python-Server

```bash
python -m http.server 8000
```

Danach:

```text
http://localhost:8000
```

---

## Veröffentlichung auf GitHub Pages

1. Repository erstellen oder bestehendes Portfolio-Repository nutzen.
2. Datei als `index.html` in den Hauptordner legen.
3. `README.md` hinzufügen.
4. Änderungen committen und pushen:

```bash
git add index.html README.md
git commit -m "Add cinematic onefile portfolio"
git push
```

5. In GitHub unter **Settings → Pages** die Veröffentlichung aktivieren.
6. Branch und Ordner auswählen, zum Beispiel `main` und `/root`.

---

## Anpassung

### Name, Titel und Beschreibung

Im `<head>` können angepasst werden:

```html
<title>Marcus Dziersan | Filmografisches Portfolio · Fachinformatiker AE</title>
<meta name="description" content="...">
<meta name="author" content="Marcus Dziersan">
```

### Farben

Die wichtigsten Farben liegen zentral in CSS-Variablen:

```css
:root {
  --bg: #07111f;
  --accent: #82e6ff;
  --accent-2: #ffd166;
  --accent-3: #b7ff8a;
}
```

### Projekte

Projektkarten können direkt im HTML-Bereich der Projektsektion ergänzt, entfernt oder umsortiert werden.

### Profilbild

Das Profilbild nutzt aktuell eine externe Quelle plus Base64-Fallback. Für eine vollständig autarke Version kann das `src`-Attribut direkt auf den Base64-Wert gesetzt werden.

---

## Datenschutz und externe Ressourcen

Die Seite ist bewusst datensparsam umgesetzt:

- kein Tracking
- keine Analytics
- keine externen JavaScript-Bibliotheken
- keine externen CSS-Dateien
- keine externen Fonts
- keine Cookies durch die Seite selbst

Ein externer Abruf kann entstehen, wenn das Profilbild über die LinkedIn-Media-URL geladen wird. Der eingebaute Base64-Fallback reduziert die Abhängigkeit von dieser externen Quelle. Für maximale Datenschutz- und Ausfallsicherheit sollte das Profilbild vollständig lokal beziehungsweise direkt als Base64 verwendet werden.

---

## Barrierefreiheit und UX

Umgesetzt beziehungsweise berücksichtigt:

- semantische HTML-Struktur
- Skip-Link
- sinnvolle Alt-Texte
- sichtbare Fokuszustände
- responsive Navigation
- lesbare Kontraste
- mobile-first Layout
- reduzierte Abhängigkeit von Hover-only-Interaktionen

Mögliche weitere Verbesserungen:

- vollständiger Lighthouse-Check
- Prüfung mit Screenreader
- `prefers-reduced-motion` stärker ausbauen
- manuelles Tastatur-Navigations-Audit

---

## Roadmap

Sinnvolle nächste Erweiterungen:

- vollständig autarke Profilbild-Version ohne externes LinkedIn-Bild
- Dark-/Light-Theme-Schalter
- Projektkarten aus JSON laden
- kleine Druckversion als Lebenslauf-/Projektübersicht
- separate `projects.json` für wartbare Inhalte
- optionale Mehrsprachigkeit DE/EN
- Lighthouse-Optimierung
- Kontaktbereich mit klarer Bewerbungs-/Projektanfrage-Struktur

---

## Warum dieses Projekt?

Dieses Portfolio ist kein Standard-Lebenslauf als Webseite. Es zeigt eine Entwicklungslinie: von frühen Web-Erfahrungen über berufliche Umwege bis zur strukturierten Umschulung und zu eigenen Softwareprojekten.

Der Schwerpunkt liegt auf nachvollziehbarer Praxis:

- nicht nur Technologien aufzählen
- echte Projekte zeigen
- Entscheidungen dokumentieren
- Lernkurve sichtbar machen
- Code, UI und Nutzbarkeit zusammen denken

---

## Lizenz / Nutzung

Dieses Portfolio enthält persönliche Inhalte, Namen, Projektbezüge und Profilinformationen von Marcus Dziersan. Die technische Struktur kann als Inspiration dienen, persönliche Inhalte sollten jedoch nicht ungefragt kopiert oder wiederverwendet werden.

Empfohlene Trennung:

- **Code/Struktur:** frei als Lern- und Portfolio-Inspiration nutzbar
- **Persönliche Inhalte/Bild/Adresse:** nicht ohne Zustimmung verwenden

---

## Autor

**Marcus Dziersan**  
Angehender Fachinformatiker Anwendungsentwicklung  
Schwerpunkt: PHP, OOP, MVC, SQL, JSON, JavaScript, Java, Python, Dokumentation und praxisnahe Softwareprojekte

- Portfolio: `https://mdwebdev.de/`
- GitHub: `https://github.com/marcdziersan`
