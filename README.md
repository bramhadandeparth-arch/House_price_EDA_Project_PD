# House Price Exploratory Data Analysis (EDA)

## Project Overview

This project explores a house-price dataset to understand how property characteristics and neighbourhoods relate to sale prices. The analysis is presented through a four-chart EDA dashboard.

## Dashboard

The dashboard contains the following visualisations:

1. **Average Sale Price by Year Built** — shows how average sale prices vary by the year a property was built.
2. **Top 10 Neighbourhoods by Average Price** — compares the ten neighbourhoods with the highest average sale prices.
3. **Sale Price Distribution** — displays the distribution of sale prices, including reference lines for the mean and median.
4. **Living Area vs Sale Price** — explores the relationship between ground living area and sale price, with point colour representing overall quality.

## Key Observations

Based on the displayed dashboard:

- Average sale prices vary across construction years, with higher values visible among some of the more recently built homes.
- The neighbourhoods shown at the top of the ranking include NoRidge, NridgHt and StoneBr.
- Sale prices are right-skewed: most observations are concentrated in the lower-to-middle price ranges, with a smaller number of high-priced properties.
- Sale price generally increases with ground living area, although there is variation between properties.
- Higher overall-quality ratings appear among many of the higher-priced properties, but the chart also shows exceptions.

These are visual observations from the dashboard, not statistical or causal conclusions.

## Project Structure

A suggested project structure is:

```text
house-price-eda/
├── data/
│   └── house_prices.csv
├── eda_dashboard.png
├── notebook.ipynb
├── README.md
└── requirements.txt
```

## Dataset and Columns1

The dashboard indicates that the analysis uses fields corresponding to:

- `SalePrice` — property sale price
- `YearBuilt` — year the property was built
- `Neighborhood` — property neighbourhood
- `GrLivArea` — ground living area
- `OverallQual` — overall quality rating

The original dataset filename, source, units, preprocessing steps and exact column names should be documented here once confirmed from the dataset/notebook. If your dataset uses different column names, update the analysis or this section accordingly.

## Technologies Used

- Python
- pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Notes

- The dashboard image is a visual summary; the underlying dataset and notebook are required to reproduce the charts.
- The chart values and observations may change if the dataset or preprocessing changes.
- This project is for exploratory data analysis and does not, by itself, provide a trained house-price prediction model.

## Author

Add your name and project details here.
