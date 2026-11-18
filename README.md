# Auf Datensuche

**Wo finde ich geeignete Daten – und wie lade ich sie in R?**

Präsentationsfolien zu einer Workshop-Sitzung im R-Lab 2026. 

👉 **[Präsentation öffnen](https://jborcherding.github.io/RLab_Datenquellen/)**

## Voraussetzungen zum Mitmachen

```r
install.packages(c("tidyverse", "mariposa"))     # Grundausstattung
install.packages(c("WDI", "eurostat", "gerda", "httr2"))  # Datenzugang für diese Sitzung
```

Für die Übungen braucht ihr einen Ordner `daten/` in eurem RStudio-Projekt.

## Dateien

| Datei | Inhalt |
|-------|--------|
| `docs/index.html` | Fertige Präsentation (Quarto/reveal.js), alle Bilder eingebettet |
| `docs/daten/destatis_tabelle.csv` | GENESIS-Tabelle 14111-0003 für das Fehler-Museum |

## Quellen und Lizenzen der Daten

- **GENESIS-Tabelle 14111-0003:** © Statistisches Bundesamt (Destatis), Datenlizenz Deutschland – Namensnennung – Version 2.0
- **Ausschnitte aus Codebuch und Fragebogen des ALLBUS 2023:** GESIS – Leibniz-Institut für Sozialwissenschaften
- **Screenshots** der Datenportale: jeweilige Anbieter, Stand 09.11.2026 (OECD Data Explorer: Stand 18.11.2026)
- Alle übrigen Daten werden während der Sitzung direkt bei den Anbietern abgerufen (Our World in Data, Weltbank, Eurostat, GERDA, Afrobarometer, OECD) und liegen nicht in diesem Repository.
