# Patrick Kreutzer, LL.M. – Digitale Visitenkarte Wohnbau Derr

Version 6, 24.10.2026.

Öffentliche Seite: https://voxxxyn.github.io/visitenkarte-wbd/
Repository: https://github.com/Voxxxyn/visitenkarte-wbd

## Für Veranstaltungen

`assets/visitenkarte-wbd-qr-v6.png` öffnet die neue Seitenadresse. `assets/visitenkarte-wbd-qr-v6.svg` ist die skalierbare Druckdatei. Den weißen Rand nicht abschneiden. Vor einem Druck den QR mit dem Smartphone testen.

Frühere Veranstaltungs-QR-Codes aus den Versionen 1 bis 4 enthalten den alten Seitenpfad und müssen ersetzt werden. Diese Adresse wurde durch die Umbenennung geändert. Die LinkedIn-QR-Datei führt weiterhin direkt zum LinkedIn-Profil.

## Dateien und lokale Nutzung

ZIP vollständig entpacken und index.html öffnen. Die Seite, Foto und QR-Dateien liegen lokal im Paket; keine externen Schriftarten oder Skripte. LinkedIn und externe Websites benötigen Internet. „Kontakt speichern“ öffnet oder lädt die vCard; Import anschließend im Kontaktprogramm bestätigen.

- index.html: Visitenkarte mit Wohnbau-Derr-Blau, Mobil- und Büro-Nummer, E-Mail, LinkedIn und Teilen-Funktion.
- assets/profil.webp: offizielles Mitarbeiterfoto von Wohnbau Derr mit blauem Hintergrund, proportional für die Webseite verkleinert; kreisförmige Anzeige im Browser.
- patrick-kreutzer.vcf: Kontaktdaten mit Mobil- und Büronummer.
- assets/visitenkarte-wbd-qr-v6.png und .svg: neue Veranstaltungs-QR-Dateien.
- assets/linkedin-qr.png: direkter LinkedIn-Profillink.
- QUELLEN.md und PRUEFBERICHT.md: Herkunft und Prüfungen.
- .nojekyll: statische Auslieferung.

## Pflege und GitHub Pages

Repository → Settings → Pages: Deploy from a branch, main, /(root). Dateien direkt im Hauptverzeichnis ablegen; kein zusätzlicher Ordner und kein Build erforderlich. Kontaktdaten in index.html und patrick-kreutzer.vcf gemeinsam ändern. Solange die Seitenadresse gleich bleibt, bleibt der neue Veranstaltungs-QR gültig.

LinkedIn verwendet einen direkten HTTPS-Profillink. Ob die installierte LinkedIn-App öffnet, hängt von iOS und der gespeicherten Gerätepräferenz ab. Falls nötig den Profillink in Notizen lange drücken und, wenn angeboten, „In LinkedIn öffnen“ auswählen. Die Webseite kann dies nicht erzwingen.

Version 6: Die eingebundene Veranstaltungs-QR-Datei besitzt einen neuen Dateinamen, damit Browser sie frisch abrufen. Die Zieladresse ist unter dem QR sichtbar.
