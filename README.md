# Geld-Cockpit

Eine kleine Web-App für die Haushaltsplanung: Töpfe, Rechnungen, Verträge, Fristen und Ziele.

## Datenschutz

- Dieses Projekt enthält nur den Programmcode.
- Die Daten liegen in `data/cockpit.enc` und sind auf dem Gerät mit einem Passwort verschlüsselt (AES-256-GCM, Schlüssel aus PBKDF2 mit 600.000 Durchläufen).
- Ohne Passwort ist die Datei nicht lesbar.
- Kontoauszüge (CSV) werden nur im Browser gelesen und nie hochgeladen.
- Die Seite lädt nichts von fremden Servern und spricht nur mit der GitHub-Schnittstelle.
