# Bradford Air Quality – Winter Analysis (PM2.5 & PM10)

## Overview
This repository contains a reproducible analysis of PM2.5 and PM10 air quality data
from multiple monitoring sites across Bradford during the winter period
(November 2024 – January 2025).

The analysis was completed as part of an interview task to support councillors
and officers in understanding air quality trends and potential public health implications.

## Data
The dataset is an extract from Bradford Council’s air quality monitoring systems
(via UK Air Quality), provided for interview purposes.
No personal or sensitive data is included.

## Approach
- Cleaned and standardised monitoring data across sites
- Aggregated hourly data to daily means for public health interpretation
- Explored trends, site-level differences, and pollution spikes
- Compared observed levels to relevant WHO and UK guideline thresholds
- Produced clear visualisations suitable for non-technical audiences

## Reproducibility
All analysis steps are fully reproducible.
Running the notebook or script will regenerate all tables and figures in the `outputs/` folder.

## How to Run
1. Create a virtual environment (optional)
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
