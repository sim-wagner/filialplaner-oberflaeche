# Filialplaner — Oberfläche

Dieses Repo enthält **nur die Benutzeroberfläche** des Filialplaners: eine einzelne
HTML-Datei. Die Mac- und iPhone-App lädt sie beim Start von hier und benutzt sie ab
dem nächsten Öffnen. So kommen Änderungen an der Oberfläche auf die Geräte, ohne dass
die App neu installiert werden muss.

**Hier liegen keine Filial- oder Mitarbeiterdaten.** Die bleiben auf dem Gerät und in
iCloud und verlassen es nicht.

| Datei | Zweck |
|---|---|
| `filialplaner.html` | die Oberfläche selbst |
| `fassung.json` | Versionsstempel und SHA-256 der Datei — danach entscheidet die App, ob sie lädt |

Die Bibliotheken (ExcelJS, jsPDF) und die Schriften liegen weiterhin im App-Paket und
werden nicht nachgeladen.

Veröffentlicht wird aus dem Projekt `filialplaner-app` heraus mit `./veroeffentlichen.sh`.
