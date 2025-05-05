
🛒 Supermarket Sales Analysis

This project provides a comprehensive analysis of supermarket sales data using Python, focusing on KPIs, customer behavior, and visual insights. The analysis is performed using Jupyter Notebook with libraries like `pandas`, `matplotlib`, and `seaborn`.

## 📂 Dataset

The dataset `supermarket_sales - Sheet1 (1).csv` includes sales data from a supermarket over a period of time and contains the following key columns:

- `Invoice ID`
- `Branch`
- `City`
- `Customer type`
- `Gender`
- `Product line`
- `Unit price`
- `Quantity`
- `Tax 5%`
- `Total`
- `Date`
- `Time`
- `Payment`
- `cogs`
- `gross margin percentage`
- `gross income`
- `Rating`

## 📊 Key Insights

- **Total Gross Income**
- **Average Customer Rating**
- **Sales Distribution by Product Line**
- **Sales Trends by Hour and Day**
- **Customer Preferences (Gender, Payment, Product Line)**

## 🔍 Exploratory Data Analysis (EDA)

- Cleaning and formatting dates and times
- Creating new time-based features (`Hour`, `Day`, `Month`)
- Visualizing total sales by product line, city, and time
- Heatmap of correlations between financial features

## 📈 Visualizations

The notebook provides detailed and attractive charts such as:
- Bar plots of product line and city income
- Line plots for sales by hour
- Count plots for payment methods
- Heatmaps of feature correlations

## 🛠️ Tech Stack

- Python 3
- Jupyter Notebook
- pandas
- matplotlib
- seaborn

## 📌 How to Run

1. Install dependencies:
   ```bash
   pip install pandas matplotlib seaborn
