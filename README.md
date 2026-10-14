# 🚀 Nils Bauch – Persönliche Portfolio Landing Page

Moderne, performante und responsive Portfolio-Landing-Page für **Dipl.-Ing. (FH) Nils Bauch** (Senior Embedded Software Architekt & AI / Data Specialist).

Die Seite wurde vollständig mit modernem HTML5, CSS3 (Vanilla Design System) und JavaScript umgesetzt – optimiert für ein nahtloses und schnelles Hosting über **[GitHub Pages](https://docs.github.com/de/pages/quickstart)**.

---

## 🌟 Highlights & Funktionen

- **Echtes Profilbild & Branding**: Hochauflösendes Porträtbild aus dem Lebenslauf mit dynamischem Leuchtrand und animierten Schwebekarten.
- **5 Erteilte Patente (DE & EP)**: Prominenter Bereich mit detaillierten Kurzbeschreibungen, Technologie-Tags und **direkten Verlinkungen zu den Patentschriften auf Google Patents**.
  - `DE 10 2014 207 093 A1`: Car2X-Kommunikation mit einheitlichem Transmitter
  - `DE 10 2015 200 801 A1`: Elektronische Steuerungsvorrichtung mit Firewallpartition
  - `DE 10 2017 214 191 A1`: Satelliten-synchronisierte Zeit mittels kontinuierlichem Zähler
  - `EP 3 610 588 A1`: Fahrzeug-zu-X-Kommunikationssystem – Selbsttest
  - `EP 3 138 304 A1`: Zeitstempelerzeugung ohne GNSS-Signal
- **GitHub Repositories**: Interaktive Filterfunktion (*Alle*, *Deep & Machine Learning*, *Data Engineering & Pipelines*, *SQL & Datenbanken*) mit Direktlinks zu:
  - `beeswarm_pre_detection` (Deep Learning, CNN / LSTM)
  - `blutdruck_data_engineer_training` (Data Engineering, DWH Star-Schema, ETL)
  - `ml_project_diabetic_prediction` (Machine Learning Klassifikation)
  - `care_sense_ai` (Smart Healthcare / Ambient Assisted Living)
  - `SchiedsrichterDB` (T-SQL, Relationale Datenbanken)
  - `ZentraleSQLKontaktdatenbank` (SQL RDBMS)
- **Werdegang & Meilensteine**: Interaktive Zeitleiste über 24+ Jahre Erfahrung (Aumovio, Continental Automotive, Siemens VDO) inklusive aller Serienprojekte (Mercedes-Benz C-Klasse, VW Golf, Ford, FIAT, China TCU).
- **Zertifikate & Qualifikationen**: Akademischer Diplom-Ingenieur Abschluss (Note 1,9), alfatraining-Abschlüsse (*mit Auszeichnung* in Data Engineering, Deep Learning, Machine Learning, SQL) sowie SAFe for Architects und Continental Academy Zertifikate.
- **Interaktive Kontaktmöglichkeiten**:
  - 1-Click Zwischenablage für E-Mail und Rufnummern mit visueller Toast-Benachrichtigung.
  - Dynamischer **vCard (.vcf) Generator** zum direkten Speichern im Adressbuch.
  - Direkter Downloadlink des Original-Lebenslaufs (`LebenslaufNilsBauch.pdf`).
- **Dark / Light Mode**: Elegantes Theme-Switching mit Speicherfunktion (`localStorage`).
- **Interaktiver Canvas-Hintergrund**: Reaktive Partikelanimation, die dezent auf Mausbewegungen reagiert.

---

## 📁 Projektstruktur

```
NilsLandingPage/
├── index.html              # Haupt-Landingpage (semantisches HTML5)
├── .nojekyll               # Deaktiviert Jekyll auf GitHub Pages (Best Practice)
├── README.md               # Projektdokumentation & Deployment-Anleitung
├── css/
│   └── style.css           # Modernes Glassmorphic Design System (Vanilla CSS)
├── js/
│   └── main.js             # Canvas, Filter, Theme-Switch, vCard & Clipboard
├── assets/
│   └── img/
│       ├── nils-bauch.png  # Profilporträt
│       └── favicon.svg     # SVG-Favicon
├── lebenslauf/
│   └── LebenslaufNilsBauch.pdf
└── zeugnisse/
    ├── Diplom_NilsBauch.pdf
    ├── Zertifikat_182688_SQL_20260216.pdf
    ├── Zertifikat_186281_Data_Engineer_20260316.pdf
    ├── Zertifikat_189057_Machine_Learning_20260413.pdf
    ├── Zertifikat_189840_Deep_Learning_20260511.pdf
    ├── Zertifikat_Jenkins.pdf
    ├── Zertifikat_Python.pdf
    ├── Zertifikat_REST_API.pdf
    └── Zertifikat_SAFe_Architect.pdf
```

---

## 🌐 Anleitung: Hosting auf GitHub Pages

Gemäß der offiziellen Anleitung auf **[GitHub Pages Quickstart](https://docs.github.com/de/pages/quickstart)** kann diese Seite in wenigen Schritten kostenlos gehostet werden:

### Schritt 1: Git-Repository initialisieren und committen

Öffne ein Terminal (z. B. PowerShell) in diesem Verzeichnis (`NilsLandingPage`):

```bash
# 1. Git-Repository initialisieren
git init

# 2. Alle Dateien hinzufügen
git add .

# 3. Ersten Commit erstellen
git commit -m "Initial commit: Nils Bauch Landing Page"

# 4. Standardbranch auf 'main' setzen
git branch -M main
```

### Schritt 2: GitHub Repository erstellen und pushen

1. Melde dich auf **[GitHub](https://github.com/)** an.
2. Erstelle ein neues Repository:
   - **Variante A (Empfohlen als persönliche Hauptseite)**: Nenne das Repository exakt `NilsBauch.github.io` (öffentlich).
   - **Variante B (Als Unterprojekt)**: Beliebiger Name, z. B. `nils-landing-page` (öffentlich).
3. Verknüpfe und pushe deine lokalen Dateien:

```bash
# Ersetze <DEIN-REPO-NAME> durch den gewählten Namen (z.B. NilsBauch.github.io):
git remote add origin https://github.com/NilsBauch/<DEIN-REPO-NAME>.git
git push -u origin main
```

### Schritt 3: GitHub Pages aktivieren

1. Gehe auf GitHub in dein Repository.
2. Klicke auf **Settings** (oben im Menü).
3. Klicke in der linken Seitenleiste auf **Pages**.
4. Unter **Build and deployment**:
   - **Source**: Wähle `Deploy from a branch`.
   - **Branch**: Wähle `main` und als Ordner `/ (root)`.
5. Klicke auf **Save**.

Nach circa 1–2 Minuten ist deine Website weltweit erreichbar unter:
👉 **`https://NilsBauch.github.io/`** (bzw. `https://NilsBauch.github.io/<DEIN-REPO-NAME>/`)
