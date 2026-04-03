
# Regressionsanalys av försäkringskostnader  
Detta projekt genomför en statistisk analys av vilka faktorer som påverkar försäkringskostnader (charges) med hjälp av R. Projektet innehåller datastädning, beskrivande analys, regressionsmodellering och residualdiagnostik.

## Projektstruktur
Projektet består av följande filer:

- `insurance_analysis.R` eller `.Rmd` – huvudfil med all kod (datainläsning, datastädning, visualiseringar, modeller, diagnoser)
- `insurance_costs.csv` – datasetet som används i analysen
- `Regressionsanalys_rapport.docx` – skriftlig rapport med metod, resultat, tolkningar och slutsatser
- `README.md` – denna körinstruktion

## Hur du kör projektet

### 1. Öppna projektet
- Ladda ned repositoryn eller klona den från GitHub.
- Öppna projektet i **RStudio**.

### 2. Installera nödvändiga paket
Analysen använder följande R‑paket:

```r
install.packages(c(
  "tidyverse",
  "janitor",
  "ggplot2",
  "dplyr",
  "lmtest",
  "car"
))
