# Dataset Information

## Dataset Name
Sample Superstore Sales Dataset

## Description
This dataset contains retail sales transaction records used to analyze business performance, sales trends, profitability, product categories, regional performance, and discount patterns.

## Source
The dataset is available from:

https://github.com/Victory-Data/Superstore-Sales-Dataset

## Dataset Details
- **Number of Records:** 9,994
- **Number of Columns:** 21
- **File Format:** CSV
- **File Name:** Sample - Superstore.csv

## Key Columns
The dataset includes the following information:

- Order ID and Order Date
- Ship Date and Ship Mode
- Customer ID and Customer Name
- Segment, Country, City, State, and Region
- Product ID, Category, Sub-Category, and Product Name
- Sales, Quantity, Discount, and Profit

## Usage
This dataset is used in the Sales Performance Analysis project to perform:

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Sales and profit analysis
- Category and regional performance analysis
- Discount impact analysis
- Monthly sales trend analysis
- Business insights and recommendations

## Important Note
The dataset is included for educational and portfolio purposes. Please verify the original source's licence and redistribution permissions before sharing or reusing the dataset.

## Data Loading
The dataset can be loaded using Pandas:

```python
import pandas as pd

df = pd.read_csv(
    "data/Sample - Superstore.csv",
    encoding="cp1252"
)

print(df.head())
```
