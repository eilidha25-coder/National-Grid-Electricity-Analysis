# UK Electricity Demand and Renewable Energy Analysis using Python
This project explores UK electricity demand using National Grid data and Meteostat weather observations. The analysis investigates seasonal demand patterns, temperature relationships and embedded renewable generation using Python.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Data sources
- National Grid ESO Open Data Portal – Half-hourly GB electricity demand data (2025).
- Meteostat – Daily weather observations for Glasgow (2025).

## Key Findings
- Electricity demand follows seasonal patterns.
- Winter demand is generally higher than other seasons.
- Lower temperatures are associated with increased electricity demand.
- Embedded solar generation follows daily and seasonal trends while embedded wind generation is irregular.

## How to Run

1. Clone or download this repository.
2. Install the required Python packages:

```bash
pip install -r requirements.txt
```

3. Open the Jupyter Notebook and run all cells.

## Example Visualisations

### Electricity demand over time
![Yearly demand](figures/yearly_demand.png)

### Electricity demand vs temperature
![Demand vs temperature](figures/demand_versus_temperature.png)

### Embedded solar and wind generation over time
![Embedded renewables over time](figures/monthly_renewables.png)

### Ratio of national demand provided by embedded solar and wind generation
![National demand and renewables ratio](figures/renewables_demand_ratio.png)

## Future Improvements
- Include total renewable generation data.
- Analyse regional demand differences.

## Author
Eilidh Anderson | BSc Physics with Astrophysics | Univeristy of Glasgow
