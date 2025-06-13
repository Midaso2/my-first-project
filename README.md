# Retail Sales Data Analysis

## Project Overview
This project analyses retail sales data to identify trends, insights, and the impact of promotional markdowns on sales. The goal is to provide actionable insights for retail managers and analysts using Python ETL and data visualisation tools.

---

## Project Steps

### 1. Ideation & Project Proposal
- **What:** Define the project idea, target audience, and main features.
- **Why:** To ensure the project addresses a real business need and has clear objectives.
- **How:** Brainstormed ideas and selected retail sales analysis as the focus.

### 2. Data Extraction (ETL - Extract)
- **What:** Load the raw data files (`stores_data.csv`, `features_data.csv`, `sales_data.csv`) into Python.
- **Why:** To make the data accessible for cleaning and analysis.
- **How:** Used `pandas.read_csv()` to import the datasets.

### 3. Data Cleaning & Transformation (ETL - Transform)
- **What:** Check for missing values, fix data types, and create new features if needed.
- **Why:** To ensure data quality and consistency for accurate analysis.
- **How:** Filled or dropped missing values, converted date columns, and added flags for holidays.

### 4. Data Loading (ETL - Load)
- **What:** Store the cleaned and transformed data in DataFrames (and optionally as new CSV files).
- **Why:** To have a reliable dataset ready for analysis and visualisation.
- **How:** Saved cleaned data using `to_csv()` and kept DataFrames in memory.

### 5. Exploratory Data Analysis & Basic Visualisations
- **What:** Generate descriptive statistics and basic plots (histograms, bar charts, line plots).
- **Why:** To understand the data structure and identify initial trends or anomalies.
- **How:** Used `matplotlib` and `seaborn` for visualisation.

### 6. Advanced Visualisations
- **What:** Create more complex and interactive visualisations (heatmaps, pair plots, interactive dashboards).
- **Why:** To uncover deeper insights and present findings in an engaging way.
- **How:** Used `seaborn` for advanced static plots and `plotly` for interactive charts.

### 7. Documentation & Presentation
- **What:** Document the ETL process, visualisation steps, and key findings.
- **Why:** To ensure the project is reproducible and insights are clearly communicated.
- **How:** Maintained this README, commented code, and prepared a summary presentation.

### 8. Version Control & Project Management
- **What:** Track progress and changes using GitHub and a Kanban board.
- **Why:** To manage tasks, document user stories, and ensure project transparency.
- **How:** Used GitHub for version control and GitHub Projects/Trello for task management.

---

## How to Reproduce

1. Clone this repository.
2. Install dependencies from `requirements.txt`.
3. Place the raw data files in the `data/` directory.
4. Run the Jupyter notebook step by step.

---

## Key Findings (to be completed after analysis)
- [Add your main insights here after completing the analysis.]

---

## References
- [Retail Sales Dataset on Kaggle](https://www.kaggle.com/datasets/manjeetsingh/retaildataset)

---

## Contact
For questions, contact [Your Name] at [your.email@example.com].
