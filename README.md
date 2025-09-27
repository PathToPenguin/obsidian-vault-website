# Obsidian Vault Website

Ein adaptiv erweiterbares Obsidian Vault mit automatischer Website-Veröffentlichung über GitHub Pages.

## 🚀 Features

- **Automatische Veröffentlichung**: Jeder Push löst eine automatische Konvertierung zu HTML aus
- **Vollständige Obsidian-Unterstützung**: Wikilinks, Tags, Backlinks, Math, Mermaid
- **Strukturierte Organisation**: Vordefinierte Ordner für Notes, Templates, Projekte
- **Responsive Design**: Optimiert für Desktop und Mobile
- **GitHub Pages**: Kostenlose Hosting-Lösung

## 📋 Struktur

```
├── .github/workflows/    # GitHub Actions für automatisches Publishing
├── vault/               # Hauptverzeichnis des Obsidian Vaults
│   ├── .obsidian/        # Obsidian-Konfiguration
│   ├── index.md          # Startseite der Website
│   ├── Notes/            # Hauptbereich für Notizen
│   ├── Templates/        # Vorlagen für neue Notizen  
│   ├── Attachments/      # Medien und Dateianhänge
│   └── Projects/         # Projektdokumentation
└── README.md            # Diese Datei
```

## ⚙️ Setup

### 1. Repository klonen
```bash
git clone https://github.com/PathToPenguin/obsidian-vault-website.git
cd obsidian-vault-website
```

### 2. Obsidian Vault öffnen
1. Obsidian starten
2. "Vault öffnen" wählen
3. Den `vault/` Ordner auswählen

### 3. GitHub Pages aktivieren
1. Gehe zu Repository Settings
2. Scrolle zu "Pages" Sektion
3. Wähle "GitHub Actions" als Source
4. Der erste Push aktiviert automatisch den Workflow

## 📝 Verwendung

### Neue Notizen erstellen
1. Erstelle `.md` Dateien im entsprechenden Unterordner
2. Verwende Wikilinks: `[[Andere Notiz]]`
3. Füge Tags hinzu: `#beispiel #tag`
4. Nutze Frontmatter für Metadata:

```yaml
---
title: Meine Notiz
date: 2025-09-22
tags: [beispiel, notiz]
---
```

### Website aktualisieren
```bash
git add .
git commit -m "Neue Notizen hinzugefügt"
git push
```

Die Website wird automatisch in wenigen Minuten aktualisiert.

## 🛠️ Anpassung

### Workflow anpassen
Bearbeite `.github/workflows/publish.yml` für:
- Andere Obsidian-to-HTML Converter
- Zusätzliche Build-Schritte
- Custom Styling

### Obsidian-Konfiguration
Passe `vault/.obsidian/config` an für:
- Theme-Einstellungen
- Plugin-Konfiguration
- Workspace-Layout

### Vault-Struktur erweitern
Füge neue Ordner hinzu:
```
vault/
├── Knowledge-Base/
├── Daily-Notes/
├── References/
└── Archive/
```

## 🔗 Website

Die generierte Website ist verfügbar unter:
**https://pathtopenguin.github.io/obsidian-vault-website/**

## 📚 Unterstützte Features

- ✅ Wikilinks und Backlinks
- ✅ Tags und Tag-Seiten
- ✅ LaTeX Math: $E = mc^2$
- ✅ Mermaid Diagramme
- ✅ Callouts und Admonitions
- ✅ Code-Highlighting
- ✅ Bilder und Medien
- ✅ Tabellen und Listen
- ✅ Frontmatter Metadata

## 🤝 Beitragen

1. Fork das Repository
2. Erstelle einen Feature-Branch
3. Committe deine Änderungen
4. Erstelle einen Pull Request

## 📝 Lizenz

Dieses Projekt steht unter der MIT-Lizenz. Siehe [LICENSE](LICENSE) für Details.

---

💬 **Fragen?** Erstelle ein [Issue](https://github.com/PathToPenguin/obsidian-vault-website/issues)
