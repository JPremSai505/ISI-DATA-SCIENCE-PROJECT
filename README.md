# ISI-DATA-SCIENCE-PROJECT
# Time-Series Analysis of Global Temperature Data

This repo has my project notebook for the **IDEAS (Institute of Data Engineering, Analytics and Science Foundation) Summer Internship Program 2026**.

## Project Overview

This project has two parts:

**Part 1 - Temperature Data Analysis (Q1-Q10)**
Analyzed global monthly temperature anomaly data from two sources, GCAG and GISTEMP. I did data cleaning, converted dates, added Year/Month columns, calculated a 12-month moving average, filtered last 20 years of data, and used groupby + pivot tables to find trends.

**Part 2 - MNIST Digits Clustering (Q11-Q13)**
Used K-Means clustering on the sklearn digits dataset (1797 handwritten digit images) to group similar digits without using labels, then mapped the clusters to actual digit labels and checked accuracy using the macro F1 score.

---

>  **How to Run — Read Before Running**
>
> This notebook was developed and run in **Google Colab**. The first cell uses:
>
> ```python
> from google.colab import files
> uploaded = files.upload()
> ```
>
> This is used to upload `monthly_csv.csv` when running in Colab. If running locally (eg. Jupyter Notebook), **skip this cell** — just make sure `monthly_csv.csv` (included in this repo) is in the same folder as the notebook, and `pd.read_csv('monthly_csv.csv')` will work directly.

---

## Files

- `07-Time-Series_Analysis_of_Global_Temperature_Data_Summer_2026.ipynb` - notebook with all 13 questions and solutions
- `monthly_csv.csv` - dataset used for Part 1

## Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

