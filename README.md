# Digital Advertising A/B Testing Analysis

## Project Overview

This project explores the performance of two digital advertising variants, Ad A and Ad B, using Python. The goal is to analyze user engagement and compare click-through rates (CTR) across advertising platforms, device types, and days of the week.

## Objectives

- Compare the click-through rates of Ad A and Ad B.
- Analyze ad performance across social media platforms.
- Explore engagement differences across device types.
- Compare advertising activity on weekdays and weekends.
- Practice data manipulation, aggregation, and visualization using Python.

## Tools and Technologies

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Dataset

The project uses three CSV files:

- `users.csv` — User information, timestamps, and click activity.
- `advertisements.csv` — Advertisement information, including ad version.
- `devices.csv` — Device information associated with users.

*Note: Update these descriptions to match the actual contents of your datasets.*

## Analysis Performed

1. **Data preparation:** Loaded and merged datasets using common identifiers.
2. **Data exploration:** Counted unique users and examined repeated ad views.
3. **CTR analysis:** Calculated click-through rates for different ad variants.
4. **Platform analysis:** Compared CTR across social media sources.
5. **Device analysis:** Explored CTR by device type and ad version.
6. **Time-based analysis:** Compared weekday and weekend activity.
7. **Visualization:** Created charts using Matplotlib to make comparisons easier to interpret.

## Key Metrics

**Click-Through Rate (CTR)**

CTR measures the percentage of ad views that result in clicks.

CTR = (Number of clicks / Number of ad views) × 100

## How to Run This Project

1. Download or clone this repository.

2. Install the required libraries:

   ```bash
   pip install pandas matplotlib jupyter
   ```

3. Open the Jupyter Notebook.

4. Ensure the CSV files are in the expected locations.

5. Run the notebook cells in order.

## Repository Contents

- `ab_testing_analysis.ipynb` — Main analysis notebook.
- `users.csv` — User dataset.
- `advertisements.csv` — Advertisement dataset.
- `devices.csv` — Device dataset.

## Conclusion

This project demonstrates the use of Python and pandas to explore digital advertising performance, compare click-through rates, and visualize engagement patterns across advertising variants, platforms, devices, and days of the week.

The analysis can be extended with statistical significance testing to determine whether observed differences between ad variants are likely to reflect a genuine performance difference.

---

**Done By:** Parth Goyal
