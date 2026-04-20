# Situationsanalyse-GEM
# Statistik-Template für Karg Situationsanalyse

Dieses Repository enthält das HTML-Template zur Generierung einer standardisierten Situationsanalyse für Schulentwicklungsprozesse.

## Verwendung mit Gemini Gems
1. Kopiere den vollständigen Inhalt von `index.html`.
2. Gib dem Gem als Instruktion: "Nutze den folgenden HTML-Code als Template. Ersetze die Daten in den `datasets` der Chart.js-Charts sowie die Texte in den `<p>`-Containern entsprechend der Analyse."
3. Das Gem generiert dir dann eine fertig befüllte Datei.

## Aufbau des Templates
- **Design:** Tailwind CSS für ein modernes, responsives Layout.
- **Charts:** Chart.js für die Visualisierung der Umfragedaten.
- **Druck-Optimierung:** Über den `@media print` Block ist das Dokument direkt als PDF exportierbar.

## Technische Details
- **Fonts:** Inter
- **Frameworks:** Tailwind (via CDN), Chart.js (via CDN)
