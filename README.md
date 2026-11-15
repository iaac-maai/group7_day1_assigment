# group7_day1_assigment
Ugochinyere Megwa, Sneha Sachin Shenoy, Álvaro Miñé

Cleaning and exploratory analysis of 13,500 NYC Department of Buildings permits for apartment renovations: what drives renovation cost, and how it varies by borough, job type, zoning and time.

## Structure

```
data/
  apartment_data.csv          raw dataset
  apartment_data_clean.csv    cleaned dataset (written by the notebook)
figures/                      all charts (written by the notebook)
notebook/
  data_cleaning_and_EDA.ipynb cleaning, EDA and correlation analysis
requirements.txt
```

## How to run

```bash
pip install -r requirements.txt
cd notebook
jupyter notebook data_cleaning_and_EDA.ipynb
```

Run all cells from top to bottom. The notebook regenerates `data/apartment_data_clean.csv` and every image in `figures/`.
