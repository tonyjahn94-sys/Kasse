# Kasse – Weihnachtsmarkt

Kassen-App fürs iPad: Glühwein, Crêpes, Pommes. Läuft ohne Internet, alle Verkäufe bleiben auf dem iPad gespeichert.

## Auf das iPad bringen

1. Am iPad mit WLAN Safari öffnen und die Adresse dieser App aufrufen.
2. Rechts neben der Adressleiste auf **Teilen** tippen → **Zum Home-Bildschirm**.
   „Als Web-App öffnen“ eingeschaltet lassen → **Hinzufügen**.
3. Die Kasse einmal über das neue Symbol öffnen, solange noch WLAN da ist.
4. Test: Flugmodus an, Kasse schließen und wieder öffnen – sie muss starten.

## Wichtig

- Die Kasse immer über das Symbol auf dem Home-Bildschirm öffnen, nicht über Safari. Das Symbol hat seinen eigenen Speicher.
- Das Symbol nicht löschen – sonst sind die gespeicherten Verkäufe weg.
- Jeden Abend sichern: Auswertung → Export & Sicherung → Komplette Sicherung → „In Dateien sichern“.
- Vor dem ersten Markttag die Probeverkäufe löschen: Auswertung → Export & Sicherung → Alle Verkäufe löschen.

## Für spätere Änderungen

Nach einer Änderung an `index.html` in `sw.js` die Zahl in `kasse-v1` erhöhen, damit das iPad die neue Version lädt (einmal mit WLAN öffnen).
