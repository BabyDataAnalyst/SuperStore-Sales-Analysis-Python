# SuperStore-Sales-Analysis-Python 📊
This practice project analyzes sales data to uncover insights into revenue, and regional performance.  
It was done as part of my Data Analyst learning journey using Python.

## 📂 Files in this Repository
- `train.csv` → Dataset used
- `SuperStore_Retail_EDA.ipynb` → Jupyter Notebook with full analysis
- `Requirement.txt` → Required Python libraries

## 🛠 Tools & Libraries
- Python
- Pandas
- Seaborn
- Matplotlib

## 🚀 How to Run
1. Clone/download this repo
2. Install dependencies:

## 📈 Sample Output
![Total Sales By Category](https://github.com/user-attachments/assets/10a9dbf1-0dd7-4538-b11e-d613108c63da)
![Correlation Heatmap](https://github.com/user-attachments/assets/d52b2685-b59c-4312-a708-6176dacc41ae)

## 📃 Insights from the Charts

1️⃣ Sales by Region
- The West and East regions are leading in sales, contributing the most revenue.
- In contrast, Central and South regions are lagging behind, indicating potential areas for sales improvement or strategic focus.

2️⃣ Monthly Sales Trend
- Sales show seasonal fluctuations with several peaks and dips, but the overall trend is positive and growing steadily from 2015 to 2018.
- A significant spike in late 2018 suggests strong year-end performance, possibly due to holiday sales or seasonal promotions.

3️⃣ Sales by Category
- Technology dominates as the top-selling category, outperforming Furniture and Office Supplies.
- However, Furniture and Office Supplies are not far behind, showing consistent contribution to overall revenue.
- This indicates a balanced sales mix, but Technology is the key revenue driver.

4️⃣ Weekly Sales Trend (2015–2018)
- Overall, sales show a steady upward trend across the years.
- However, the trend is highly volatile, with sharp peaks and drops, suggesting sales could be influenced by seasonal events, discounts, or bulk purchases.

5️⃣ Outlier Analysis in Sales
- The sales distribution shows a large number of outliers (very high sales orders compared to the majority).
- These outliers may represent bulk corporate purchases or special deals, which significantly impact total revenue.

6️⃣ Correlation Between Numerical Features
- Numerical features like Row ID, Postal Code, and Sales show very weak or negligible correlation with each other.
- This means these identifiers don’t influence sales directly and are mainly structural data.
