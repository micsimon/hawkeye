# hawkeye
hawkeye

## Idee
* zentrales Tool zur Überwachung sämtliche Anwendungen
* es soll auf Basis von "green or red" zu erkennen sein, ob alles ok ist
* dient nicht der grundsätzlichen Fehleranalse, sondern nur der Visualisierung der Funktionstüchtigkeit
* bietet Konnektoren für verschiedene Systeme

## details
* reine stantalone Anwendung
* keine Datenbank
* Konfiguration wird im Code definiert

## connectors
* gitlab - Status pipeline
* http statuscode - erreichbar 200
* http plain text regex - Kontrollwort
* elk-stack
