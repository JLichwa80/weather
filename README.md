# Weather Analysis: Seattle vs. Honolulu

Analyze and compare daily rainfall precipitation between Seattle and Honolulu using NOAA data.

---

## Project Overview

- **Objective:** Analyze and compare rainfall precipitation trends between Seattle and Honolulu.
- **Domain:** Meteorology/Climate
- **Key Techniques:** Time Series Analysis, Data Cleaning, Visualization

---

## Project Structure

```
├── data/                 # Raw and processed data (CSV)
├── code/                 # Jupyter notebooks and Python scripts
├── reports/              # Generated reports and visualizations 
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
```

Key files:
- `code/Weather_Data_Preparation.ipynb` (notebook with data cleaning)
- `data/seattle_honolulu_rain_clean.csv` (cleaned data using Jupyter notebook)

---

## Setup

1. Clone the repository: http://github.com/JLichwa80/weather
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter notebook in `code/Weather_Data_Preparation.ipynb` to explore the data cleaning and analysis process. Run the cells sequentially to produce results, visualizations, and the cleaned dataset 'data/seattle_honolulu_rain_clean.csv'.

## Data

- **Source:** [NOAA - Climate Data](https://www.ncei.noaa.gov/cdo-web/search?datasetid=GHCND)
- **Description:** Daily precipitation observations for Seattle and Honolulu.
- **Terms:** N/A.

Files included in `data/`:
- `seattle_rain.csv` – Seattle daily precipitation (raw)
- `hnl_rain.csv` – Honolulu daily precipitation (raw)

---

## Analysis

- `code/Weather_Data_Preparation.ipynb` data cleaning and exploratory analysis notebook.

---

## Results

Include a short discussion of the findings and what they imply.

---

## Authors

  Jack Lichwa – [@JLichwa80](https://github.com/JLichwa80)

---

## License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

**Libraries/Tools used:** numpy, pandas, matplotlib, seaborn, scikit-learn,Jupyter

---
