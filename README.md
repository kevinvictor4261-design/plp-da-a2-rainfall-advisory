# PLP Data Analysis Assignment 2: Rainfall Advisory

## Project Summary
This project analyzes multi-county monthly rainfall data using NumPy and Python's built-in CSV module. It cleans raw rainfall data using exception handling, computes annual totals, monthly averages, identifies wettest months, counts dry months, and generates actionable agricultural planting windows across five counties.

## How to Run the Notebook
1. Open Google Colab.
2. Upload or clone this repository (`plp-da-a2-rainfall-advisory`).
3. Run the cells in `rainfall_analysis.ipynb` sequentially from top to bottom (`Runtime -> Run all`).
4. The notebook will automatically process data, print outputs, display the planting advisory, and export `rainfall_summary.csv`.

## Planting Advisory
* Farmers in agricultural counties should align planting schedules closely with the onset of bimodal long and short rainy seasons to optimize crop germination.
* Supplemental irrigation is crucial during extended dry months where monthly rainfall drops below the 50 mm threshold to prevent crop failure.
* County-specific planting windows identified in this analysis should guide regional seed distribution and agricultural extension planning.