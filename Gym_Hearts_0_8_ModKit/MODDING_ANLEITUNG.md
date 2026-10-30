# Gym Hearts 0.8 – Eigene Bilder einsetzen

1. ZIP komplett entpacken. Die `index.html` muss neben dem Ordner `assets` bleiben.
2. Die gewünschte PNG in `assets/characters/rina/` (oder `mio/` bzw. `sakura/`) kopieren.
3. **Schnellster Weg:** `sprite.png` ersetzen – dann wird dein Bild überall als Standard angezeigt.
4. **Automatische Varianten:** `training.png`, `mma.png`, `casual.png`, `rest.png`, `night.png`, `date.png` sind optional. Das Spiel wählt je nach Szene und Tageszeit den Slot und fällt bei fehlender Datei automatisch auf `sprite.png` zurück.
5. Bei Hintergründen `assets/backgrounds/gym.png`, `locker.png` oder `lounge.png` durch eigene Bilder mit **genau gleichem Namen** ersetzen.
6. Spiel neu laden (`Strg+F5`), falls ein Bild noch gecacht ist. Nicht direkt innerhalb des ZIP-Archivs öffnen.

## Grafikempfehlungen
- Charakter-PNGs mit transparentem Hintergrund (RGBA), möglichst 1000–2000 px hoch.
- Für Rina, Mio und Sakura gleiche Bildausrichtung über die Varianten beibehalten.
- Hintergründe: 16:9 oder breiter, idealerweise mindestens 1920×1080.
- PNG-Dateiendung muss stimmen. Eine JPG-Datei nur umzubenennen reicht nicht.

## Grenzen
- Browser können unter `file://` lokale Ordner nicht automatisch durchsuchen. Deshalb arbeitet das Spiel mit **festen Slot-Dateinamen**, nicht mit beliebig benannten Dateien. Unterordner und eigene Assets funktionieren ohne Server.
- Neue Figurenordner bereiten die Erweiterung nur vor; neue Dating-Routen entstehen nicht automatisch durch das Hinzufügen eines Bildes.
- Die Outfit-Stufen wechseln bereits als Status. Es gibt noch keine vollständigen eigenen Bilder für jede Kombination aus Outfit, Mood und Kapitel. Die Slots sind die vorbereitete Grundlage.
