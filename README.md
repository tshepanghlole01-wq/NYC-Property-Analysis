# NYC Property Sales Analysis

## 📋 Project Overview

This project analyzes NYC property sales data from September 2016 to September 2017. The goal was to clean, explore, and understand the factors that influence property prices in New York City.

**Key Question:** What factors most strongly predict property sale prices in NYC?

---

## 📊 Key Findings

| Finding | Insight |
| :--- | :--- |
| **Average Sale Price** | $1.47 Million |
| **Median Sale Price** | $620,000 |
| **Most Expensive Borough** | Manhattan (Borough 1) |
| **Least Expensive Borough** | Staten Island (Borough 5) |
| **Strongest Price Predictor** | Gross Square Feet (correlation: 0.50) |
| **Weakest Price Predictor** | Year Built (correlation: 0.003) |

---

## 🛠️ Technologies Used

- **Python** – Data analysis and manipulation
- **Pandas** – Data cleaning and processing
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualizations
- **Jupyter Notebook** – Interactive analysis environment

---

## 📂 Dataset

- **Source:** NYC Rolling Sales Dataset (Kaggle)
- **Original Rows:** 84,548
- **Final Rows (After Cleaning):** 55,449
- **Columns:** 22

---

## 🧹 Data Cleaning Steps

| Step | Action | Rows Removed |
| :--- | :--- | :--- |
| 1 | Removed properties with $0 sale price | 10,228 |
| 2 | Removed properties with YEAR BUILT = 0 | 4,310 |
| 3 | Converted SALE PRICE to numeric | - |
| 4 | Converted SALE DATE to datetime | - |

**Final Dataset:** 55,449 rows × 22 columns

---

## 📈 Visualizations

The analysis included:

1. **Histograms** – Distribution of sale prices (regular and log scale)
2. **Bar Chart** – Average sale price by borough
3. **Scatter Plot** – Sale price vs. property size
4. **Line Plot** – Sale prices over time
5. **Heatmap** – Correlation between numeric features

---

## 🔍 Key Insights

### 1. Size Drives Price
Gross Square Feet has the strongest correlation with sale price (0.50), confirming that larger properties tend to sell for more.

### 2. Location Matters Most
Manhattan dominates in average sale price, significantly outperforming other boroughs.

### 3. Year Built is Irrelevant
The near-zero correlation (0.003) suggests property age has no meaningful relationship with price in NYC.

### 4. Commercial Properties Are Outliers
The maximum sale price of $2.21B represents a commercial office building, far exceeding typical residential prices.

---

## 📁 Repository Structure

nyc-property-analysis/
├── README.md
└── ML(AI) FINAL PROJECT.ipynb
└── nyc-rolling-sales.csv

## 🚀 Future Work

- **Feature Engineering:** Create "price per square foot" feature
- **Modeling:** Build predictive models (Linear Regression, Random Forest)
- **Log Transformation:** Apply log transform to handle price skew
- **Separate Analysis:** Analyze residential vs. commercial properties separately
- **Expand Timeframe:** Include more years to identify market trends

---

## 👤 Author

[Tshepang Hlole]
[www.linkedin.com/in/tshepang-hlole-ab33722b9]

---

## 📄 License

This project is for educational purposes.
