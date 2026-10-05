# 🌹 MyOS – ein Web-Betriebssystem im Browser

**MyOS** ist ein Hobbyprojekt von *Nilty Media*: ein kleines Betriebssystem, das komplett im Browser läuft – nur mit HTML, CSS und JavaScript, ohne Frameworks und ohne Server.

> 📸 `boot.png`

## ✨ Features

- **Boot-Screen** mit Typewriter-Animation und einblendendem Logo
- **Login-Screen** mit Benutzerauswahl
- **Desktop** mit Taskleiste, Uhr, Start- und System-Menü
- **Fenstersystem** – Apps öffnen sich als eigene Fenster
- **Terminal** mit Befehlen: `help`, `ls`, `cd`, `pwd`, `cat`, `clear`, `whoami`
- **Virtuelles UNIX-Dateisystem** (`/bin`, `/etc`, `/home`, `/var`), das Terminal und Explorer teilen
- **Datei-Explorer** zum Durchklicken der Ordner
- **Einstellungen** mit wählbarer Akzentfarbe
- **Web-Browser** (iframe-basiert)
- **Herunterfahren / Neustarten / Abmelden**

## 🚀 Ausprobieren

1. Repository herunterladen oder klonen:
   ```bash
   git clone https://github.com/DEIN-NAME/MyOS.git
   ```
2. `Boot.html` im Browser öffnen (Doppelklick genügt, es wird nichts installiert).

## 📁 Projektstruktur

```
MyOS/
├── Boot.html              # Startpunkt: Boot-Animation
├── Login.html             # Benutzerauswahl
├── users/
│   └── user1.html         # Desktop von User 1
├── NiltyOswllpaper.jpg    # Hintergrundbild
├── rose.png               # Logo
└── *.png                  # Icons der Taskleiste
```

## 💻 Terminal-Befehle

| Befehl | Beschreibung |
|--------|--------------|
| `help` | Zeigt alle Befehle |
| `ls` | Ordnerinhalt anzeigen |
| `cd [ordner]` | Verzeichnis wechseln (`cd ..` für zurück) |
| `pwd` | Aktuellen Pfad anzeigen |
| `cat [datei]` | Dateiinhalt ausgeben |
| `clear` | Terminal leeren |
| `whoami` | Aktuellen Benutzer anzeigen |

## ⚠️ Bekannte Einschränkungen

- Der Browser nutzt ein `iframe`. Viele Seiten (Google, YouTube, GitHub …) verbieten das Einbetten. Dafür gibt es den ↗-Button, der die Seite in einem neuen Tab öffnet.
- User 2 und der Store sind noch Platzhalter.

## 🗺️ Geplant

- [ ] Fenster verschiebbar machen
- [ ] Texteditor
- [ ] Dateien im Terminal erstellen (`touch`, `mkdir`)
- [ ] Desktop für User 2
- [ ] Store-App

## 🛠️ Technik

HTML5 · CSS3 (Flexbox, Grid, `backdrop-filter`) · Vanilla JavaScript

## 🎨 Credits

Hintergrundbild und Icons: *hier Quellen und Lizenzen eintragen*

## 👤 Autor

**Ahmet Yasin Öztürk** – [Portfolio](https://ahmet-ozturk-portfolio.netlify.app/)

Ein Projekt von *Nilty Media* · Wien, 2026
