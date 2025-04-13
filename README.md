# EDA & Clustering of Crime Data in Indian Districts

This project performs exploratory data analysis (EDA) and clustering on crime data from Indian districts using K-Means clustering.

## Dataset

**Source:** `Districtwise_Crime_of_India_2001_to_2014.csv` `written as q.csv in the notbook` from `https://www.data.gov.in/catalog/district-wise-crimes-under-various-sections-indian-penal-code-ipc-crimes`  
The dataset contains crime statistics from 2001 to 2014 across Indian districts.

## Methods Used

- Data Cleaning & Grouping
- Feature Selection: 
  - Rape
  - Murder
  - Riots
  - Kidnapping & Abduction
  - Attempt to Murder
- Standardization using `StandardScaler`
- Clustering with `KMeans`

## Visualizations

- Cluster counts using bar charts
- Sample district plotting (e.g., Rape vs Murder)
- Scatter plots for selected districts across clusters

## Tech Stack

- Python
- Pandas
- Matplotlib
- scikit-learn
- Jupyter Notebook

## How to Run

1. Clone the repo or download the notebook.
2. Ensure the dataset CSV is in the same directory.
3. Run `EDA_Patrol_DataMiners.ipynb` using Jupyter or any notebook IDE.
