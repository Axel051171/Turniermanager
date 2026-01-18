# 🎱 Turniermanager v1.3

Professionelle Turnierverwaltung für **Pool** und **Karambol** Billard.

![Version](https://img.shields.io/badge/version-1.3-green)
![License](https://img.shields.io/badge/license-MIT-blue)

## ✨ Features

- **60 Turnier-Kombinationen** (5 Vorrunden × 4 Endrunden × 3 Disziplinen)
- **Manuelles Losverfahren** mit Zettel-Zuordnung (PA01, PB02, KB01...)
- **Spieler Import/Export** (CSV, JSON)
- **Automatische Tischzuweisung**
- **Live-Gruppentabellen** mit Punktestand
- **KO-Bracket Visualisierung**
- **Responsive Design** (Desktop + Mobile)
- **Offline-fähig** - keine Installation nötig!

### 🆕 Neu in v1.3

- 🔴 **Karambol-Statistiken**: Aufnahmen, Höchstserie (HS), Generaldurchschnitt (GD)
- ⏱️ **Spiel-Timer** mit wählbaren Signaltönen und Lautstärke
- 🔄 **Undo-Funktion** für Ergebnis-Korrekturen
- 📋 **Setzlisten-Editor** mit Drag & Drop
- 💾 **Mehrtages-Speicherung** für lange Turniere
- 📺 **TV-Ansicht** für zweiten Bildschirm/Beamer

## 🚀 Quick Start

1. `turniermanager.html` herunterladen
2. Im Browser öffnen
3. Fertig! 🎉

**[▶️ Live Demo](https://axel051171.github.io/Turniermanager/turniermanager.html)**

## 🔴 Karambol-Modus

Bei Karambol werden zusätzliche Statistiken erfasst:

| Statistik | Beschreibung |
|-----------|--------------|
| **Aufnahmen** | Anzahl der Spielzüge pro Spieler |
| **Höchstserie (HS)** | Beste Serie in einer Aufnahme |
| **Generaldurchschnitt (GD)** | Punkte ÷ Aufnahmen |

Die Tabellen zeigen automatisch diese Werte wenn Karambol gewählt ist.

## 📺 TV-Modus

Für Turniere mit Publikum:
1. Klick auf "📺 TV-Ansicht"
2. Neues Fenster auf zweiten Monitor/Beamer ziehen
3. "Vollbild" klicken

Die TV-Ansicht zeigt:
- Live-Timer
- Nächste Spiele mit Tischzuweisung
- Aktuelle Tabelle
- Gruppenübersicht

## 🎯 Turnier-Modi

### Vorrunde
| Modus | Beschreibung |
|-------|--------------|
| Gruppen | Klassische Gruppenphase (A, B, C, D) |
| Liga | Jeder gegen Jeden |
| Schweizer | Schweizer System |
| Handicap | Stark vs. Schwach Paarungen |
| Keine | Direkt ins KO |

### Endrunde
- Single KO
- Double KO

### Disziplinen
- 🎱 Pool
- 🔴 Karambol (mit Aufnahmen, HS, GD)
- 🏆 Dual (Pool + Karambol parallel)

## ⏱️ Timer-Signale

Wählbare Signaltöne:
- Piep (kurz)
- Doppel-Piep
- Glocke
- Sirene
- Horn (laut)
- Dreiklang

## 💾 Import-Formate

### CSV
```csv
Name,Handicap,Klasse,Pool,Karambol
Max Müller,35,B,true,false
```

### JSON
```json
{
  "spieler": [
    {"name": "Max Müller", "handicap": 35, "klasse": "B", "pool": true, "karambol": false}
  ]
}
```

## 📁 Dateien

| Datei | Beschreibung |
|-------|--------------|
| `turniermanager.html` | Die komplette App (Single-File) |
| `beispiel_spieler.csv` | Beispiel CSV-Import |
| `beispiel_spieler.json` | Beispiel JSON-Import |

## 🛠️ Technologie

- Pure HTML/CSS/JavaScript
- Keine Abhängigkeiten
- LocalStorage für Speicherung
- Single-File Application (~90 KB)

## 📄 Lizenz

MIT License - Frei verwendbar!

---

Made with ❤️ für Billard-Enthusiasten
