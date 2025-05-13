# COVID-19 Global Data Tracker

## Project Overview
The **COVID-19 Global Data Tracker** is a data analysis project that explores global COVID-19 trends using the Our World in Data dataset. The goal is to analyze cases, deaths, and vaccinations across countries, visualize trends with charts, and summarize findings in a Jupyter Notebook. This project is ideal for beginners learning data analysis with Python, focusing on real-world data cleaning, exploratory data analysis (EDA), and visualization.

By the end, the project will produce a well-documented notebook with:
- Cleaned and analyzed COVID-19 data.
- Visualizations like line charts and (optionally) maps.
- Key insights about global pandemic trends.

## Objectives
- Import and clean the COVID-19 dataset.
- Analyze trends in cases, deaths, and vaccinations over time.
- Compare metrics across countries (e.g., Kenya, United States, India).
- Create visualizations to highlight patterns.
- Summarize findings in a narrative report.

## Current Progress
As of now, the project is in **Step 3: Data Loading and Exploration**. The following tasks have been completed:
- Loaded the `owid-covid-data.csv` dataset using pandas.
- Explored the dataset structure (columns, sample rows, and missing values).

The Jupyter Notebook (`covid.ipynb`) contains code to:
- Read the CSV file.
- Display column names, preview data, and check for missing values.

### Next Steps
- **Data Cleaning**: Filter specific countries, handle missing values, and convert dates.
- **Exploratory Data Analysis**: Plot trends like total cases and deaths over time.
- **Vaccination Analysis**: Visualize vaccination progress.
- **Visualizations**: Create line charts, bar charts, and possibly a choropleth map.
- **Reporting**: Write insights and explanations in the notebook.

## Dataset
The project uses the **Our World in Data COVID-19 dataset** (`owid-covid-data.csv`), which includes data on:
- Dates, countries, and ISO codes.
- Total cases, new cases, total deaths, and new deaths.
- Vaccination metrics (e.g., total vaccinations).
- Other metrics like population and death rates.



## Requirements
To run this project, you need:
- **Python 3.x** (download from [python.org](https://www.python.org)).
- **Jupyter Notebook** (for running `.ipynb` files).
- **Python Libraries**:
  - `pandas`: For data manipulation.
  - `matplotlib`: For plotting.
  - `seaborn`: For enhanced visualizations.

Install the libraries using:
```bash
pip install pandas matplotlib seaborn
```

Optional (for future choropleth maps):
```bash
pip install plotly
```



## How to Run
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/victorke485/plp_python_final_project.git
   cd plp_python_final_project
   ```
  

2. **Download the Dataset**:
   - Get `owid-covid-data.csv` from the [link above](https://github.com/owid/covid-19-data/raw/master/public/data/owid-covid-data.csv).
   - Save it in the `COVID19-Tracker` folder.

3. **Set Up Environment**:
   - Ensure Python and the required libraries are installed (see Requirements).
   - Install Jupyter Notebook if not already installed:
     ```bash
     pip install notebook
     ```

4. **Run the Notebook**:
   - Start Jupyter Notebook:
     ```bash
     jupyter notebook
     ```
   - Open `COVID19_Tracker.ipynb` in the browser.
   - Run all cells to see the data loading and exploration results.

