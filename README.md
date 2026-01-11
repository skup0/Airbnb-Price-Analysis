# Airbnb NYC Pricing — Exploratory Data Analysis (EDA)

This project explores which listing features are most associated with nightly price for NYC Airbnb listings. The notebook focuses on practical exploratory data analysis with clear visualizations, including distributions, correlations, spatial patterns, and a targeted interaction-effect deep dive.

The analysis is intentionally lightweight and exploratory, emphasizing intuition, visual reasoning, and data validation rather than heavy modeling.

## What’s Inside
- Dataset loading and sanity checks
- Price distributions and core feature relationships
- Numeric correlation scan
- Spatial analysis using interactive Folium maps and a price heatmap
- Interaction-effect example: parking vs price overall and within neighborhoods
- Property-type comparisons for 1-bedroom vs 2-bedroom listings

## Tools & Technologies
- Python
- pandas
- NumPy
- matplotlib
- seaborn
- folium
- Jupyter Notebook

## Repository Contents
- `Airbnb-Analysis.ipynb` — main analysis notebook  
- `Airbnb-Analysis.html` — exported notebook for easy viewing  
- `requirements.txt`

## Dataset
The dataset used in this project is **not included** in the repository due to GitHub file size constraints.

Expected file:
- `airbnb_nyc.csv`

Place the dataset in the same directory as the notebook so it runs without modification.

If you obtained the dataset from a course portal, Kaggle, or an original source, re-download it and rename it accordingly.

## How to Run
1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
