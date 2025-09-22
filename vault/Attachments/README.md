---
title: Attachments Verwaltung
date: 2025-09-22
tags: [attachments, media, files]
---

# Attachments Verwaltung

Dieser Ordner ist für Medien und Dateien vorgesehen, die in den Notizen verwendet werden.

## Organisation

### Ordnerstruktur
```
Attachments/
├── images/          # Bilder und Screenshots
├── documents/       # PDFs und andere Dokumente  
├── audio/           # Audiodateien
├── video/           # Videodateien
└── misc/            # Sonstige Dateien
```

### Namenskonventionen
- Verwende beschreibende Dateinamen
- Nutze ISO-Datum-Format: `2025-09-22-screenshot.png`
- Vermeide Leerzeichen und Sonderzeichen
- Verwende Bindestriche als Trennzeichen

## Unterstützte Dateiformate

### Bilder
- **PNG** - Für Screenshots und Grafiken
- **JPG/JPEG** - Für Fotos
- **SVG** - Für Vektorgrafiken
- **WebP** - Für optimierte Webbilder

### Dokumente
- **PDF** - Für Dokumente und Präsentationen
- **MD** - Für Markdown-Dokumente
- **TXT** - Für einfache Textdateien

### Media
- **MP3, WAV** - Für Audiodateien
- **MP4, WebM** - Für Videos

## Einbindung in Notizen

### Bilder
```markdown
![Beschreibung](Attachments/images/beispiel.png)

# Oder mit Obsidian-Syntax:
![[Attachments/images/beispiel.png]]
```

### Dokumente
```markdown
[Dokument öffnen](Attachments/documents/beispiel.pdf)

# Oder mit Obsidian-Syntax:
![[Attachments/documents/beispiel.pdf]]
```

## Web-Optimierung

### Bilder
- Komprimiere Bilder vor dem Upload
- Verwende WebP für bessere Performance
- Optimale Auflösung: max. 1920px Breite

### Dateigröße
- Halte Dateien unter 10MB für bessere Ladezeiten
- Verwende externe Links für sehr große Dateien

Zurück zur [[index|Startseite]]