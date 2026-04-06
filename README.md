# superstore-data-cleaning
Data wrangling and cleaning project using Superstore dataset
# 🛒 Superstore Data Cleaning Project

## 📌 Project Overview
This project involves data wrangling and cleaning of the 
Superstore Sales dataset as part of a data analytics internship task.

## 📂 Dataset
- **Source**: Kaggle Superstore Dataset
- **Rows**: 9,994
- **Original Columns**: 21
- **Final Columns**: 32

## 🔍 Data Quality Issues Found
| Issue | Detail |
|---|---|
| Missing Values | None found |
| Duplicate Rows | None found |
| Date Format | Fixed DD-MM-YYYY to proper datetime |
| Outliers | Found and flagged in Sales, Profit, Discount, Quantity |

## 🛠️ Data Cleaning Steps
1. Loaded dataset with correct encoding (latin1)
2. Fixed date formats for Order Date and Ship Date
3. Flagged outliers in numeric columns
4. Performed feature engineering

## 🆕 New Columns Created
| Column | Description |
|---|---|
| Shipping Days | Days taken to ship the order |
| Order Month | Month of the order |
| Order Year | Year of the order |
| Order Quarter | Quarter of the order |
| Profit Margin % | Profit as % of Sales |
| Revenue Category | Low / Medium / High / Premium |
| Is Discounted | Whether discount was applied |

## 📁 Files
| File | Description |
|---|---|
| Superstore.csv | Original raw dataset |
| data_dictionary.csv | Data dictionary with column meanings |
| cleaned_superstore.csv | Final cleaned dataset |
| notebook.ipynb | Full cleaning script |

## 🛠️ Tools Used
- Python 3
- Pandas
- NumPy
- Jupyter Notebook
