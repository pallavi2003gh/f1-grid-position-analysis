# Formula 1 Grid Position Analysis (2019–2024)

## Research Question

How much does starting position determine where a driver finishes, and does pit-stop strategy change that?

## Data

Race result and pit-stop data were collected using the FastF1 library (Ergast/Jolpica API) for the 2019–2024 Formula 1 seasons.

## Method

- Used Spearman rank correlation to compare starting and finishing positions for every race.
- Calculated seasonal and circuit-level averages.
- Compared drivers making fewer, typical, and more pit stops than the majority of the field.
- Created visualisations using Matplotlib.

## Key Findings

- Starting position was a strong predictor of finishing position across all seasons.
- Average seasonal correlations ranged from 0.71 to 0.81.
- Monaco showed the strongest grid dependence (0.92).
- Pit-stop count showed little evidence that alternative strategies consistently improved finishing position.

## Tools Used

- Python
- Pandas
- FastF1
- Matplotlib

## Project Outputs

- Circuit-level grid dependence analysis
- Seasonal comparison of grid-to-finish correlation
- Pit-stop strategy analysis
- Data visualisations

## Author

**Pallavi Ram**
