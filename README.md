# Hospitality Revenue Analysis

## Project Overview

This project performs Exploratory Data Analysis (EDA) on hotel booking and occupancy data. The analysis uses Python to explore booking patterns, occupancy rates, realized revenue, hotel performance, and customer ratings.

The objective is to turn the available booking data into useful business insights that can support hotel revenue and operational analysis.

## Project Objectives

- Explore hotel booking data and understand its structure.
- Clean and prepare booking and aggregated booking datasets.
- Calculate and analyze occupancy percentages.
- Compare occupancy across room categories, room classes, cities, and day types.
- Analyze realized revenue across cities, months, and hotel properties.
- Explore customer ratings and booking-platform performance.
- Summarize findings through business-oriented insights.

## Repository Structure

```text
Hospitality-Revenue-Analysis/
|
|-- datasets/
|   |-- dim_date.csv
|   |-- dim_hotels.csv
|   |-- dim_rooms.csv
|   |-- fact_aggregated_bookings.csv
|   |-- fact_bookings.csv
|   |-- new_data_august.csv
|
|-- notebooks/
|   |-- Project_EDA_Hospitality_Domain_Updated.ipynb
|
|-- README.md
|-- requirements.txt
|-- .gitignore
```

## Datasets

The project uses the following CSV files:

| File | Purpose |
|---|---|
| `dim_date.csv` | Date dimension and calendar-related information |
| `dim_hotels.csv` | Hotel/property details |
| `dim_rooms.csv` | Room category and room-class details |
| `fact_bookings.csv` | Hotel booking-level data |
| `fact_aggregated_bookings.csv` | Aggregated successful bookings and room capacity |
| `new_data_august.csv` | Additional August data used in the notebook's append/analysis section |

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Analysis Workflow

1. **Data Loading:** Import the CSV datasets into Pandas DataFrames.
2. **Data Exploration:** Review dataset dimensions, columns, data types, summary statistics, and categorical values.
3. **Data Cleaning:** Inspect and handle data-quality issues in the source tables.
4. **Data Transformation:** Prepare date and occupancy-related fields for analysis.
5. **Exploratory Data Analysis:** Use grouping, aggregation, joins, and visualizations to investigate business questions.
6. **Business Insights:** Summarize the patterns observed in occupancy, revenue, hotel performance, and customer ratings.

## Business Questions Explored

The notebook investigates questions including:

- What is the average occupancy rate for each room category?
- How does average occupancy vary by room class and city?
- Is occupancy different on weekdays and weekends?
- What is the city-wise occupancy during June 2022?
- How can additional August data be appended to the existing aggregated data?
- What is the realized revenue by city?
- How does realized revenue change month by month?
- Which hotel properties generate the highest realized revenue?
- What patterns can be observed in customer ratings and booking channels?

Refer to the notebook for the complete analysis, calculations, visualizations, and insights.

## How to Run the Project

### 1. Clone the repository

```bash
git clone <your-repository-url>
cd Hospitality-Revenue-Analysis
```

### 2. Install the required libraries

```bash
pip install -r requirements.txt
```

### 3. Open Jupyter Notebook

```bash
jupyter notebook
```

Open:

`notebooks/Project_EDA_Hospitality_Domain_Updated.ipynb`

### 4. Run the notebook

Run the cells from top to bottom. Keep the `datasets` folder at the repository root so the notebook can access the CSV files using the paths defined in the notebook.

## Key Takeaways

The analysis compares occupancy and revenue from multiple business perspectives, including city, room category, room class, day type, month, and hotel property. The notebook also explores customer ratings and booking-platform performance.

For the detailed findings and numerical results, see the **Business Insights** and **Conclusion** sections in the notebook.

## Author

**Amol Idhate**

---

*This repository is intended as a Python EDA portfolio project. Please retain the original dataset attribution and follow the dataset's usage or redistribution terms where applicable.*
