# Spielhalle Frankfurt Website

Eine digitale Visitenkarte mit Leadgenerierung für die Spielhalle in Frankfurt.

## Live-URL
**[https://spielhalle-obm.netlify.app](https://spielhalle-obm.netlify.app)**

---

## Offene Punkte / TODO

### 🔴 Hochpriorität (Kunde muss liefern)

- [ ] **Logo**: `/images/logo.png` oder `/images/logo.svg`
- [ ] **10 Gerätefotos**: `/images/geraete/` (Format: JPG, 800x600px empfohlen)
- [ ] **Echte Adresse**: Momentan: Musterstraße 123, 60313 Frankfurt am Main
- [ ] **Echte Telefonnummer**: Momentan: +49 69 000 000
- [ ] **Echte E-Mail**: Momentan: info@spielhalle-frankfurt.de
- [ ] **Google Maps Einbindung**: In `/kontakt.html` Platzhalter `[Google Maps Einbindung]`
- [ ] **Echte Gerätebeschreibungen**: In `/geraete.html` die 10 Geräte mit realen Daten ergänzen

### 🟡 Mittelpriorität

- [ ] **Impressum erstellen**: `/impressum.html` (Seite existiert noch nicht)
- [ ] **Datenschutz erweitern**: `/datenschutz.html` (Seite existiert noch nicht)
- [ ] **Social Media Links**: Instagram & Facebook URLs eintragen
- [ ] **WhatsApp Business**: Aktuellen Link eintragen
- [ ] **Öffnungszeiten**: Falls vorhanden, auf Kontaktseite ergänzen

### 🟢optional

- [ ] **Unsplash-Bilder austauschen**: Aktuell genützte Bilder:
  - `slot-machine-1.jpg`
  - `slot-machine-2.jpg`
  - `slot-machine-3.jpg`
  - `casino-interior.jpg`
  - `gold-coins.jpg`
  - `slots-row.jpg`
- [ ] **Favicon erstellen**
- [ ] **Meta-Bilder ergänzen**: Open Graph Bilder für bessere Social Sharing

---

## Dateistruktur

```
spielhalle-website/
├── index.html              # Startseite
├── vermietung.html         # Automatenvermietung
├── geraete.html            # 10 Geräte mit Platzhaltern
├── kontakt.html            # Kontaktformular
├── impressum.html          # [TODO]
├── datenschutz.html        # [TODO]
├── css/
│   └── style.css           # Casino-Theme (Schwarz/Gold)
├── js/
│   └── main.js             # Mobile Menu, Smooth Scroll
├── images/
│   ├── unsplash/           # Stockfotos
│   │   ├── slot-machine-1.jpg
│   │   ├── slot-machine-2.jpg
│   │   ├── slot-machine-3.jpg
│   │   ├── casino-interior.jpg
│   │   ├── gold-coins.jpg
│   │   └── slots-row.jpg
│   └── geraete/            # [KUNDENLIEFERUNG - leer]
│       └── [GERAETEFOTO-1] ... [GERAETEFOTO-10]
├── netlify.toml            # Netlify Konfiguration
└── README.md               # Diese Datei
```

---

## Technische Details

### Design
- **Farben**: Schwarz (#0D0D0D, #1A1A1A) / Gold (#D4AF37, #FFD700)
- **Schriftarten**: Montserrat (Headings), Inter (Body)
- **Framework**: Reines HTML/CSS/JS – keine Abhängigkeiten

### Features
- ✅ Responsive Design (Mobile-first)
- ✅ Mobile Navigation mit Burger-Menu
- ✅ Netlify Forms (Kontaktformular)
- ✅ SEO-Grundlagen (Meta-Tags, Open Graph)
- ✅ Smooth Scroll, Header-Animationen

### Netlify
- **Site-Name**: spielhalle-obm
- **Formular-Handling**: Aktiviert
- **Custom Domain**: Optional

---

## Bearbeiten

### Inhalt anpassen
1. HTML-Dateien direkt bearbeiten
2. Texte sind gut sichtbar markiert
3. Platzhalter sind `[SUCHEN]...

### CSS anpassen
- Farben: `css/style.css` – `:root`-Variablen oben
- Abstände: `--space-*` Variablen

### Bilder austauschen
- Eigene Bilder einfach nach `/images/` kopieren
- In HTML Dateien den Pfad anpassen

---

## Kontakt

Bei Fragen zur Website:
- Erstellt: 2025-03-10
- Framework: Static HTML
- Hosting: Netlify

---

## Rechtliches

⚠️ **Wichtig**: Die Website enthält Platzhalter für:
- Adresse
- Telefonnummer
- E-Mail
- Gerätebilder

**Vor dem Livegang muss der Kunde eigene Inhalte liefern!**

---

*Letzte Aktualisierung: 2025-03-10*
