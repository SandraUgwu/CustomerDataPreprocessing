# Customer Data Pre-processing Project

This project was completed as part of the "Introduction to Programming for Artificial Intelligence and Data Science" module. It involves customer data pre-processing, transformation, and visualization.

## Project Description

The project demonstrates:
- **Data Preprocessing**: Transforming flat CSV structures into nested JSON formats and correcting data inconsistencies.
- **Data Analysis**: Calculating metrics for ranking customers and identifying anomalies.
- **Data Visualization**: Using Pandas and Seaborn to gain insights from the dataset.

## Tasks
### Data Preprocessing
1. Read and process `acw_user_data.csv` to:
   - Convert flat CSV data into nested JSON structures.
   - Identify and handle missing values (e.g., empty "dependants" entries).
   - Generate JSON outputs for:
     - Processed data (`processed.json`).
     - Retired customers (`retired.json`).
     - Employed customers (`employed.json`).
   - Flag records with invalid credit card data (`remove_ccard.json`).
   - Calculate the "Salary-Commute" metric and generate `commute.json`.

### Data Visualization
1. Calculate:
   - Mean Salary.
   - Median Age.
2. Create visualizations using Seaborn for:
   - Age and dependants.
   - Salary vs commute distance.
   - Age vs Salary (conditioned by dependants).
3. Save plots for client presentation.

## Project Files
- `Assignment.ipynb`: Main Jupyter notebook with all code and visualizations.
- `acw_user_data.csv`: Input dataset for preprocessing.
- `Task Description.docx`: Detailed task description and requirements.

## Requirements
- Python 3.x
- Libraries: `csv`, `json`, `os`, `sys`, `time`, `pandas`, `seaborn`

## How to Run
1. Open `Assignment.ipynb` in Jupyter Notebook or Jupyter Lab.
2. Follow the cells to preprocess data, generate JSON files, and create visualizations.

## Acknowledgments
This project was part of the coursework for the AI and Data Science module.

