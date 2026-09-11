# Military, Education & Healthcare Spending Analysis

A Python-based analysis comparing military, education, and healthcare spending across the world's top 10 military-spending countries from 2016–2021.

The project integrates data from the Stockholm International Peace Research Institute (SIPRI) and the World Bank to examine how national spending priorities differ when measured in total dollars, as a percentage of GDP, per person, and through spending growth over time.

## Technologies Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Data Sources

The analysis combines five datasets:

- SIPRI Military Expenditure Database
- World Bank Population Data
- World Bank GDP Data
- World Bank Education Expenditure Data
- World Bank Healthcare Expenditure Data

The analysis focuses on 2016–2021 because later years did not contain sufficient data across all datasets for consistent comparison.

## Analysis

The project:

- Identified the top 10 countries by military expenditure in 2021
- Compared military spending from 2016–2021
- Compared military, education, and healthcare spending as a percentage of GDP
- Converted GDP-percentage measures into estimated spending amounts
- Compared military, education, and healthcare spending in absolute terms
- Calculated spending per person using population data
- Compared per-capita spending with GDP per person
- Calculated absolute and percentage growth in education and healthcare spending
- Created reusable Python functions for data cleaning, filtering, calculations, and visualization

## Key Findings

- The United States had the highest total spending across military, education, and healthcare among the countries analyzed.
- Countries with higher GDP per person generally also spent more per person on education and healthcare.
- Spending as a percentage of GDP revealed different national priorities than comparisons based only on total spending.
- Saudi Arabia had the highest military-spending share of GDP in 2021 at approximately 7.2%.
- Healthcare represented the largest share of GDP for most countries, with the United States spending approximately 17.4% of GDP on healthcare in 2021.
- The United States had the largest absolute increase in education spending from 2016–2021, while South Korea had the largest percentage increase at approximately 53%.
- The United States had the largest absolute increase in healthcare spending, while Russia had the largest percentage increase at approximately 100%.
- Healthcare spending as a percentage of GDP increased noticeably in 2020 for several countries, coinciding with the COVID-19 pandemic.

## Selected Visualizations

The project includes visualizations comparing spending across countries and measurement approaches, including:

- Military, education, and healthcare spending as a percentage of GDP
- Total spending by category
- Education spending per person
- Healthcare spending per person
- Military spending per person
- Education and healthcare spending growth from 2016–2021

## Repository Contents

- `NickRini_spending_analysis.ipynb` — complete Python analysis
- `SIPRI-Milex-data-1948-2023.xlsx` — SIPRI military expenditure data
- World Bank GDP dataset
- World Bank population dataset
- World Bank education expenditure dataset
- World Bank healthcare expenditure dataset

## Running the Analysis

1. Clone or download this repository.
2. Keep the source datasets in the same directory as the Jupyter notebook.
3. Install the required Python libraries:
`pip install pandas matplotlib openpyxl xlrd`
5. Open `NickRini_spending_analysis.ipynb` in Jupyter Notebook or JupyterLab.
6. Run the notebook cells in order.

## Notes

Some countries contained missing values in the World Bank datasets. In particular, Saudi Arabia did not have education-spending data for the selected period, and Russia did not have education-spending data for 2021. These limitations are accounted for in the relevant comparisons.
