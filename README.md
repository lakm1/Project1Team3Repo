# Project1Team3Repo
# Country GDP 2020–2025

A data analysis project exploring GDP trends across countries from 2020 to 2025 using Python, reproducible notebooks/scripts, and an interactive Gradio dashboard.

## Description

This project collects, cleans, analyzes, and visualizes country-level GDP data for the years 2020 through 2025. It aims to provide insights into economic growth, highlight cross-country differences, and spot patterns or anomalies.  
**Dataset Source:** Kaggle – GDP per Country 2020–2025 (codebynadiia)  
**Demo Link:** Gradio App

## Repository Structure

```
Project1Team3Repo/
├─ data/
│  ├─ 2020-2025.csv       # Original raw dataset
│  ├─ data_clean.csv      # Cleaned dataset
│  └─ data_csv.csv        # Extra dataset copy/variant
│
├─ notebooks/
│  ├─ Project1_Team3.ipynb        # Main analysis notebook
│  └─ ProjectOne-Team3.ipynb      # Alternate/early notebook
│
├─ .gitignore              # Git ignore file
├─ README.md               # Project documentation
├─ requirements.txt        # Dependencies

```

## Installation

Clone the repository:
```bash
git clone https://github.com/Mudhawish/country-gdp-2020-2025.git
cd country-gdp-2020-2025
```

(Optional) Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
```

Install dependencies:
```bash
pip install -r requirements.txt
```

If downloading via Kaggle API, ensure you’ve configured `~/.kaggle/kaggle.json` and downloaded the dataset into `data/`.

## Requirements

This project requires the following Python libraries:
- **gradio** – interactive dashboard
- **pandas** – data manipulation and analysis
- **matplotlib** – data visualization (static plots)
- **plotly** – interactive charts
- **seaborn** – statistical visualizations
- **numpy** – numerical computations
- **google.colab** – optional, for running in Google Colab notebooks

All dependencies are listed in `requirements.txt` for easy installation.

## What’s Included

- **EDA Outputs:** row/column counts, data types, missing values, summary statistics
- **Cleaning & Standardization:** renamed columns, handled missing data, converted types
- **Processed Data:** saved as `data/data_clean.csv`
- **EDA & Visuals:** bar plots, line charts, and comparisons across countries
- **Dashboard:** Gradio app with filters, stats, interactive visualizations, and table preview

## Data Notes

- GDP units may differ across countries; check Kaggle page for definitions
- Later years include estimates/projections
- For cross-country comparisons, you may need to normalize GDP values

## Contributing

Contributions are welcome!
- Open an issue for suggestions or bugs

## License

The dataset license/terms are governed by the Kaggle page—please review and comply.

## Citation

If you use this repo or the dataset, please cite:

- codebynadiia. GDP per Country 2020–2025. Kaggle.
- This repository: Country GDP 2020–2025 (GitHub).
