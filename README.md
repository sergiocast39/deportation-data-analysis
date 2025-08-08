# Deportation Data Analysis (2008–2025)

This project analyzes publicly available deportation data from [deportationdata.org](https://deportationdata.org/data/ice.html#sec-about).  
It explores patterns in U.S. Immigration and Customs Enforcement (ICE) removals by **age**, **gender**, **state of departure**, **country of birth**, and **presidential term**.

The analysis was built in Python using a single Jupyter notebook, supported by helper utilities for cleaning and processing messy CSV data.

---

## 🔍 Project Goals

- Clean and unify multiple CSV files with inconsistent schemas
- Calculate age at deportation using birth year and removal date
- Assign U.S. presidential term to each deportation record
- Explore trends by:
  - Age
  - Year
  - Gender
  - U.S. state of departure
  - Country of birth
- Visualize the findings using `matplotlib` and `plotly`

---

## 📁 Project Structure

deportation-data-analysis/
deportation_csvs/ # CSV files (not included in repo)
Deportation_Data_Analysis.ipynb # 💡 Main notebook
requirements.txt # Python dependencies
README.md # Project overview
.gitignore

## Tools & Libraries
Python 3.x
Pandas
Matplotlib
Plotly
Jupyter Notebook

## Data Source
All data used in this project is sourced from DeportationData.org, a project by the Transactional Records Access Clearinghouse (TRAC) at Syracuse University.

## About the Author
Created by Sergio Castaneda – data analyst passionate about public interest data, transparency, and reproducible research.
