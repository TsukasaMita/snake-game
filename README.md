# Snake Game

Ein klassisches Snake-Spiel, das in Python mit dem `turtle`-Modul entwickelt wurde.

## 🐍 Über das Spiel

Sammle das Futter ein, um deine Schlange wachsen zu lassen und Punkte zu sammeln. Pass auf, dass du nicht gegen die Wände oder deinen eigenen Schwanz stößt, sonst ist das Spiel vorbei!

## 🎮 Steuerung

Das Spiel wird ganz einfach mit den Pfeiltasten auf deiner Tastatur gesteuert:
- **Pfeiltaste Oben (⬆️):** Nach oben bewegen
- **Pfeiltaste Unten (⬇️):** Nach unten bewegen
- **Pfeiltaste Links (⬅️):** Nach links bewegen
- **Pfeiltaste Rechts (➡️):** Nach rechts bewegen

## 🚀 Installation & Spielen (Für Spieler)

Du musst für dieses Spiel **nichts installieren** und benötigst auch kein Python. Lade dir einfach die fertige Datei für dein System herunter:

### Windows (.exe)
1. Gehe auf der rechten Seite dieser GitHub-Seite auf **"Releases"** (oder klicke auf die neueste Version).
2. Lade die Datei `snake-game-windows-latest.zip` herunter.
3. Entpacke die ZIP-Datei.
4. Starte das Spiel mit einem Doppelklick auf `snake-game.exe`.

### macOS (.app / Binary)
1. Gehe auf der rechten Seite dieser GitHub-Seite auf **"Releases"** (oder klicke auf die neueste Version).
2. Lade die Datei `snake-game-macos-latest.zip` herunter.
3. Entpacke die ZIP-Datei.
4. Starte das Spiel durch einen Klick auf die Spieldatei `snake-game`.
*(Hinweis für Mac-Nutzer: Da das Spiel nicht von Apple signiert ist, musst du beim ersten Mal einen **Rechtsklick** auf die Datei machen und **Öffnen** wählen, um es zu starten).*

---

## 🛠️ Für Entwickler (Ausführen aus dem Quellcode)

Wenn du den Code bearbeiten oder das Spiel direkt über Python ausführen möchtest:

1. **Voraussetzung:** Python (>= 3.12) und ein Paketmanager wie `uv` oder `pip` müssen installiert sein.
2. **Repository klonen / herunterladen:**
   ```bash
   git clone https://github.com/DeinBenutzername/snake-game.git
   cd snake-game
   ```
3. **Das Spiel starten:** Führe den folgenden Befehl im Terminal aus:
   ```bash
   python main.py
   # oder falls uv genutzt wird:
   uv run main.py
   ```

Viel Spaß beim Spielen! 🍎🐍