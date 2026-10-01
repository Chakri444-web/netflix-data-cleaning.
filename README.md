# Netflix Movies and TV Shows – Data Cleaning & Preprocessing

## Project Overview

This project focuses on cleaning and preprocessing the Netflix Movies and TV Shows dataset using Python and Pandas.

The objective was to transform raw data into a clean and structured dataset suitable for further analysis.

## Dataset

- **Source:** [Kaggle – Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **Original Records:** 8,807
- **Columns:** 12

## Technologies Used

- **Python** – Programming language used for data cleaning.
- **Pandas** – Data manipulation, missing value handling, and preprocessing.
- **NumPy** – Numerical operations and data handling.
- **Matplotlib** – Data visualization.
- **Google Colab** – Cloud-based notebook environment.
- **GitHub** – Version control and project hosting.

## Data Cleaning Operations

1. Identified missing values using `isnull()` and `sum()`.
2. Handled missing values using `fillna()`.
3. Detected and removed duplicate records using `drop_duplicates()`.
4. Standardized text values using Pandas string methods.
5. Converted `date_added` into datetime format.
6. Standardized column names using lowercase and underscores.
7. Validated column data types.
8. Exported the cleaned dataset into CSV format.

## Final Results

| Metric | Result |
|---|---:|
| Original Rows | 8,807 |
| Final Rows | 8,807 |
| Total Columns | 12 |
| Duplicate Rows | 0 |
| Missing Date Values Preserved | 10 |

## Project Structure

```text
netflix-data-cleaning/
│
├── dataset/
│   └── netflix_titles.csv
│
├── output/
│   ├── netflix_cleaned.csv
│   └── data_cleaning_report.txt
│
├── screenshots/
│
├── netflix_cleaning.ipynb
│
└── README.md
```

## Key Learning Outcomes

- Understanding real-world data quality issues.
- Handling missing and duplicate records.
- Working with Pandas DataFrames.
- Standardizing text and date formats.
- Validating data types.
- Exporting cleaned datasets.

## Conclusion

Successfully completed the data cleaning and preprocessing workflow on the Netflix dataset. The final dataset is structured and ready for further exploratory data analysis.
