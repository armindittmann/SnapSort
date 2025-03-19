# SnapSort

![SnapSort Logo](logo.png)

SnapSort ist eine Browser-basierte Anwendung zum schnellen und effektiven Sortieren von Bildersammlungen. Die App ermöglicht es, Bilder intuitiv durch einfache Gesten zu organisieren, während alle aussortieren Bilder sicher in einem DELETE-Unterordner aufbewahrt werden.

## Features

- 🖱️ Mehrere Interaktionsmöglichkeiten: Tastatur, Mausklick oder Touch-Gesten
- 🌓 Dunkler und heller Modus für angenehmes Arbeiten
- 📂 Arbeitet direkt mit Ihrem lokalen Dateisystem (kein Upload nötig)
- 🔄 Rückgängig-Funktion für versehentliche Aktionen
- 📱 Responsives Design für alle Bildschirmgrößen
- 🔍 Zoom-Funktion für Bilddetails
- 📋 Liste aller verschobenen Bilder mit Wiederherstellungsoption
- 🔠 Alphabetische Sortierung für konsistente Bild-Navigation

## Verwendung

1. Öffnen Sie die Anwendung in einem modernen Browser (Chrome, Edge empfohlen)
2. Klicken Sie auf "Ordner auswählen" und wählen Sie den Ordner mit Ihren Bildern
3. Sortieren Sie Ihre Bilder mit:
   - **Rechter Pfeiltaste** oder **Nach-Links-Wischen**: Bild in DELETE-Ordner verschieben
   - **Linker Pfeiltaste** oder **Nach-Rechts-Wischen**: Bild behalten und zum nächsten gehen
   - **U-Taste**: Letzte Aktion rückgängig machen
   - **Z-Taste** oder **Doppelklick**: Bild vergrößern/verkleinern
   - **H-Taste**: Hilfe anzeigen/ausblenden

## Wie es funktioniert

SnapSort verwendet die moderne File System Access API von Chrome, um direkt mit Ihrem lokalen Dateisystem zu arbeiten. Bilder werden nicht hochgeladen, sondern direkt in Ihrem Browser verarbeitet. Aussortierte Bilder werden in einen Unterordner "DELETE" verschoben, nicht gelöscht.

## Datenschutz & Sicherheit

- Alle Daten bleiben lokal auf Ihrem Computer
- Keine Daten werden an externe Server gesendet
- Bilder werden nicht gelöscht, sondern nur in einen anderen Ordner verschoben

## Unterstützte Browser

- Google Chrome (Version 86+)
- Microsoft Edge (Version 86+)
- Opera (Version 72+)
- Andere Chromium-basierte Browser

**Hinweis:** Firefox und Safari unterstützen die File System Access API momentan nicht vollständig.

## Installation

SnapSort erfordert keine Installation. Öffnen Sie einfach die HTML-Datei in einem unterstützten Browser oder hosten Sie die Datei auf einem Webserver.

## Lizenz

Dieses Projekt ist unter der GNU General Public License v3.0 lizenziert - siehe die [LICENSE](LICENSE) Datei für Details.

## Mitwirken

Beiträge sind willkommen! Fühlen Sie sich frei, Issues zu erstellen oder Pull Requests einzureichen, um die Anwendung zu verbessern.

##Disclaimer

Der Code wurde durch conversational Prompting mit Hilfe von Grok 3 und Claude Sonnet erstellt. Das Bild wurde von Grok 3 generiert.
