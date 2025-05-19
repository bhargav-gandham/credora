
This project involves analyzing and visualizing global population data provided by the World Bank. The original dataset contains population data by country from the year 1960 to 2023.

## 📁 Dataset Source
- Original File: `worldpopulation.csv`

## 🔄 Data Preparation

The original dataset was in wide format with years as columns. It was reshaped to long format using Python and Pandas for easier analysis and visualization.

### ✅ Steps Taken:
1. Skipped metadata rows in the CSV.
2. Removed empty columns.
3. Used `pd.melt()` to convert year columns into a single `Year` column.
4. Dropped rows with missing population data.
5. Saved the reshaped dataset as `worldpopulation_reshaped.csv`.

## 📊 Visualizations

### 1. Bar Chart
- Top 10 most populous countries in 2023
- X-axis: Country
- Y-axis: Population

## 🛠️ Technologies Used
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## 📂 Files Included
- `worldpopulation.csv` – Original dataset
- `worldpopulation_reshaped.csv` – Cleaned and reshaped dataset
- `population_analysis.ipynb` – Python code for data preparation and charts
- `README.md` – This documentation

## 📌 How to Run
1. Install dependencies: `pandas`, `matplotlib`
2. Open `population_analysis.ipynb` in Jupyter Notebook or VSCode
3. Run all cells to load data, reshape it, and generate visualizations

## 📬 Contact
For any questions or clarifications, contact:
- **Bhargav**
- Email: [gandhambhargav77@gmail.com]
