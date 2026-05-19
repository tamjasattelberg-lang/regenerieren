# Mein Regenerationsweg

Eine vollständig lokale, mobiloptimierte Web-App für Frauen 50+ zu den Themen emotionale Erschöpfung, Regeneration und innere Stärke.

Entwickelt als begleitendes Tool für den Kurs **„Mein Veränderungsweg"** von [veraenderungsweg.de](https://veraenderungsweg.de).

---

## Vorschau

Die App läuft direkt im Browser — kein Login, kein Backend, keine Installation.

**Bereiche:**
- Startseite mit Tagesimpuls und Stimmungs-Check-in
- Intensivkurs mit 9 Modulen
- 8 Mini-Kurse (5–12 Minuten)
- Soforthilfe bei Erschöpfung, Angst, Grübeln und Traurigkeit
- Energierad mit 7-Tage-Verlauf
- Geführte Atemübung (4-6-Atmung)
- Nachtmodus
- Journal-Funktion (lokal gespeichert)

---

## Technische Details

| Eigenschaft | Wert |
|---|---|
| Dateiformat | Einzelne HTML-Datei |
| Abhängigkeiten | Keine (außer Google Fonts via CDN) |
| Datenspeicherung | localStorage (nur lokal im Browser) |
| Backend | Keines |
| Login | Keines |
| Offlinefähig | Ja (nach erstem Laden) |
| Mobiloptimiert | Ja (Mobile First) |
| Schriftarten | Cormorant Garamond + Jost |

---

## Installation & Nutzung

### Option 1 — Direkt öffnen

1. Datei `regenerationsweg.html` herunterladen
2. Im Browser öffnen (Doppelklick oder Drag & Drop)
3. Fertig — die App läuft sofort

### Option 2 — GitHub Pages

1. Repository forken oder klonen
2. In den Repository-Einstellungen unter **Pages** den Branch `main` und den Ordner `/root` auswählen
3. Die App ist dann unter `https://[dein-username].github.io/[repo-name]/regenerationsweg.html` erreichbar

### Option 3 — Eigener Webserver / Webador / Systeme.io

Die HTML-Datei kann auf jeden Webserver hochgeladen oder per iFrame eingebettet werden.

```html
<iframe
  src="https://deine-domain.de/regenerationsweg.html"
  width="100%"
  height="800px"
  frameborder="0"
  style="border:none">
</iframe>
```

---

## Inhalte

### Intensivkurs — 9 Module

1. Warum bin ich so erschöpft?
2. Zur Ruhe kommen
3. Endlich wieder schlafen
4. Energie zurückholen
5. Bewegung ohne Druck
6. Emotionale Erschöpfung
7. Wieder Freude spüren
8. Das neue Lebensrad
9. Mein regeneratives Leben

Jedes Modul enthält: wissenschaftlich fundierte Erklärung, Reflexionsfragen, Journal und eine praktische Übung.

### Mini-Kurse

1. Wenn alles zu viel wird (5 Min)
2. Schuldgefühle loslassen (10 Min)
3. Schlafhilfe am Abend (8 Min)
4. Sanfte Morgenroutine (7 Min)
5. Selbstmitgefühl lernen (12 Min)
6. Nervensystem beruhigen (6 Min)
7. Wieder Freude fühlen (10 Min)
8. Kleine Hoffnungsschritte (8 Min)

### Soforthilfe

- Sofort beruhigen
- Wenn Angst aufsteigt
- Grübeln stoppen
- Wenn Traurigkeit kommt

---

## Design

- **Farben:** Creme, Sand, Salbeigrün, Warmgold, Altrosa, Nachtblau
- **Typographie:** Cormorant Garamond (Überschriften) + Jost (Fließtext)
- **Stil:** Warm, weich, feminin — keine klinische Ästhetik
- **Prinzip:** Keine Emojis, keine Leistungssprache, keine Überforderung

---

## Datenschutz

Alle Nutzerdaten (Journal-Einträge, Energierad-Verlauf, Fortschritt) werden ausschließlich im **localStorage des eigenen Browsers** gespeichert. Es werden keine Daten an externe Server übertragen.

---

## Lizenz

Dieses Projekt ist urheberrechtlich geschützt.  
© Tanja — Mein Veränderungsweg ([veraenderungsweg.de](https://veraenderungsweg.de))

Die Nutzung ist ausschließlich im Rahmen des Kursprogramms von **Mein Veränderungsweg** vorgesehen. Eine Weitergabe, Veränderung oder kommerzielle Nutzung ohne ausdrückliche schriftliche Genehmigung ist nicht gestattet.

---

## Kontakt

**Tanja**  
Systemische Beraterin & Coach  
[veraenderungsweg.de](https://veraenderungsweg.de)  
[info@veraenderungsweg.de](mailto:info@veraenderungsweg.de)
