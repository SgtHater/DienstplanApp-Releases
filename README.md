# Dienstplanung Releases

Portable Windows-Fassungen der **Dienstplanung**. Der Quellcode ist privat, dieses Repository enthält nur die Releases.

## Dateien je Release

- `Dienstplanung.exe`: die Anwendung als einzelne Datei, keine Installation und keine .NET-Laufzeit nötig.
- `Dienstplanung-<version>-win-x64.zip`: EXE, `version.txt`, `CHANGELOG.md` und Setup-Skript für den Update-Ordner der zentralen Ablage.
- `SHA256SUMS.txt`: Prüfsummen.

## Aktualisieren

Den Inhalt der ZIP-Datei in den Ordner `Update` der zentralen Ablage entpacken. Arbeitsplätze mit älterer Version zeigen danach ein Hinweisband. Die Anwendung lädt selbst nichts herunter.

## Beta

Versionen wie `1.2.0-beta.1` sind als *Pre-release* markiert und können Fehler enthalten.
