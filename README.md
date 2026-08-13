# Data Cleaning and Preprocessing

## Project Overview

This project focuses on inspecting, cleaning, and preprocessing the Sample Superstore dataset using Python and Pandas.

The objective was to assess the quality of the dataset, identify potential data-quality issues, and prepare a validated dataset for further analysis.

## Dataset

The Sample Superstore dataset contains **9,994 rows and 13 columns**.

The main columns include:

- Ship Mode
- Segment
- Country
- City
- State
- Postal Code
- Region
- Category
- Sub-Category
- Sales
- Quantity
- Discount
- Profit

## Data Quality Checks

The following checks were performed using Pandas:

- Dataset dimensions
- Column names
- Data types
- Missing values
- Duplicate records

### Missing Values

No missing values were found in any of the 13 columns.

### Data Types

The dataset contains:

- 8 object/text columns
- 2 integer columns
- 3 floating-point numeric columns

### Duplicate Records

No duplicate rows were found in the dataset.

## Preprocessing

The dataset was loaded and inspected using Python and Pandas.

The validated dataset was saved as:

`superstore_cleaned.csv`

The complete analysis is available in the Jupyter Notebook.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Google Colab
- GitHub
- Jupyter Notebook

## Repository Contents

| File | Description |
|---|---|
| `Data_Cleaning_Preprocessing.ipynb` | Complete data inspection and preprocessing notebook |
| `superstore_cleaned.csv` | Validated/cleaned dataset |
| `data_quality_report.md` | Data quality findings and preprocessing documentation |
| `requirements.txt` | Python dependencies |
| `README.md` | Project documentation |

## Conclusion

The Sample Superstore dataset was successfully inspected and validated. The dataset contains 9,994 records and 13 columns, with no missing values identified during the quality assessment.

The cleaned dataset and analysis notebook are provided in this repository for reproducibility and further analysis.
