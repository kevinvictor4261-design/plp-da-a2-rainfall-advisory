# PLP Data Analysis Assignment 2: Rainfall Advisory

## Project Summary
This project analyzes monthly rainfall readings across five target counties—Nairobi, Nakuru, Kisumu, Mombasa, and Machakos—to assist a farmer-support NGO in generating SMS planting advisories. The pipeline cleans messy station input data using exception handling, combines the records into a 5 × 12 NumPy array, calculates annual totals, monthly averages, wettest months, dry-month counts, and identifies optimal two-consecutive-month planting windows.

## How to Run the Notebook
1. Open Google Colab.
2. Clone or upload this repository (`plp-da-a2-rainfall-advisory`).
3. Run the cells in `rainfall_analysis.ipynb` sequentially from top to bottom (`Runtime -> Run all`).
4. The notebook will automatically process data, export `rainfall_summary.csv`, and output all required verification metrics and summaries.

## Planting Advisory & Data Quality Notes
Based on our multi-county rainfall distribution analysis, agricultural extension officers should advise farmers to align their planting schedules precisely with the identified two-consecutive-month peak windows to maximize crop germination. Regions experiencing higher counts of dry months below 50 mm will require targeted supplemental irrigation and water-harvesting infrastructure to mitigate mid-season drought risks. Furthermore, stakeholders must account for data-quality caveats, as missing station records in Machakos required imputation using rounded averages, which can smooth out extreme local weather anomalies. Incorporating these localized planting windows into NGO SMS advisories will directly improve seasonal agricultural yields and food security across all five target counties.
