# AVALito – Veröffentlichungen

Hier liegen ausschließlich die fertigen Installationsdateien von **AVALito** (Ausschreibung · Vergabe · Abrechnung –
lokale AVA-Software für Leistungsverzeichnisse im Bauwesen, Windows 10/11, 64 Bit). Der Quellcode wird an anderer
Stelle gepflegt und ist nicht Teil dieses Repositorys.

## Installieren

Unter **Releases** die neueste Version öffnen und `AVALito-<Version>-Setup.exe` herunterladen und ausführen.
Die Installation läuft für den angemeldeten Windows-Benutzer, Administratorrechte sind nicht nötig.
Windows meldet beim ersten Start evtl. „Der Computer wurde durch Windows geschützt“, weil das Programm nicht mit einem
gekauften Zertifikat signiert ist – dann „Weitere Informationen“ › „Trotzdem ausführen“.

`AVALito-<Version>-portable.exe` läuft ohne Installation (z. B. vom USB-Stick), aktualisiert sich aber nicht selbst.

## Aktualisieren

Die installierte Fassung prüft beim Start und über **Hilfe › Nach Updates suchen** dieses Repository, lädt eine neue
Version im Hintergrund und installiert sie beim Beenden – oder sofort nach Rückfrage. Projekte, Einstellungen,
Vorlagen und Benutzerkonten bleiben erhalten. Die Dateien `latest.yml` und `*.blockmap` gehören zum Update-Mechanismus
und müssen nicht heruntergeladen werden.

## Dateiformat

Projekte sind `.avalito`-Dateien. Ab Version 0.3.0 gilt das Dateiformat 3: Dateien, die mit 0.3.0 oder neuer
gespeichert wurden, öffnen ältere Versionen nicht mehr. Beim ersten Speichern einer älteren Datei bleibt automatisch
eine Kopie im bisherigen Format daneben liegen. Deshalb auf allen PCs, die dieselben Projekte bearbeiten, dieselbe
Version verwenden.
