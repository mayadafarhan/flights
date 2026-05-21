# Flights Exploratory Data Analysis (EDA)

This repository contains a comprehensive Exploratory Data Analysis (EDA) of the classic Seaborn `flights` dataset. The analysis explores air passenger traffic patterns from 1949 to 1960, focusing on trend identification, seasonality detection, and growth metrics.

## 🚀 Project Overview

The goal of this project is to perform an end-to-end data analysis workflow, including:
- **Data Cleaning:** Handling missing values and standardizing data types.
- **Feature Engineering:** Creating time-based indices, log transformations, and rolling statistics.
- **Statistical Analysis:** Descriptive statistics and distribution checks.
- **Time-Series Analysis:** Visualizing long-term trends and monthly seasonality.
- **Growth Analysis:** Calculating Month-over-Month (MoM) and Year-over-Year (YoY) growth percentages.

## 📊 Key Findings

- **Consistent Growth:** There is a clear upward structural trend in passenger numbers over the 12-year period.
- **Seasonality:** Strong seasonal patterns are evident, with peak travel occurring during the summer months (July and August).
- **Multiplicative Seasonality:** The variance in passenger numbers increases as the overall level increases, suggesting a multiplicative relationship.
- **Growth Stability:** Rolling averages (12-month) effectively smooth out seasonal noise to reveal the underlying growth trajectory.

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas:** Data manipulation and analysis.
- **NumPy:** Numerical operations.
- **Matplotlib & Seaborn:** Publication-quality data visualizations.
- **Jupyter Notebook:** Interactive development environment.

## 📈 Visualizations Included

1. **Passengers Over Time:** Raw time-series plot showing trend and seasonality.
2. **12-Month Rolling Mean:** Smoothing plot to highlight the structural trend.
3. **Monthly Distribution:** Boxplots/Violin plots showing seasonal variance across months.
4. **Yearly Growth:** Comparison of passenger volume across different years.
5. **Correlation Heatmaps:** Analyzing relationships between time-based features.

## 📂 Getting Started

### Prerequisites

Ensure you have the following libraries installed:
```bash
pip install pandas numpy matplotlib seaborn
```

### Running the Analysis

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/flight-eda.git
   ```
2. Navigate to the project directory:
   ```bash
   cd flight-eda
   ```
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook flight_eda.ipynb
   ```

## 📝 Author

**Senior Data Scientist**

---
*Note: This analysis uses the built-in Seaborn `flights` dataset.*
