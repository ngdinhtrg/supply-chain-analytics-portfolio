# Demand Analysis & Forecasting 📈

## 🎯 Objective
Analyze historical sales data to uncover demand trends, identify seasonality, and build forecasting models that support production and supply planning.

---

## 📦 Dataset Overview
| Column | Description |
|--------|-------------|
| `date` | Sales date |
| `market` | Market or region (e.g. Vietnam, US) |
| `sku` | Product SKU |
| `category` | Product category |
| `units_sold` | Quantity sold |
| `revenue` | Sales revenue |

---

## 🧭 Project Workflow
1. **Data Cleaning & Preprocessing**
   - Handle missing values, outliers, incorrect date format.
   - Aggregate data by week/month and by product category.

2. **Exploratory Data Analysis (EDA)**
   - Visualize sales trends over time.
   - Identify top-selling categories & regions.
   - Examine seasonality and correlation (price, promotion, etc).

3. **Forecasting Models**
   - Baseline: Moving Average & Exponential Smoothing.
   - Advanced: ARIMA, SARIMA, Facebook Prophet.
   - Compare using MAPE, RMSE.

4. **Insight & Recommendation**
   - Interpret forecast result by category.
   - Suggest production/ordering plan.
   - Highlight business implications (capacity, inventory).

---

## 🧠 Key Insights
- Category A shows strong seasonality peaking in Q4.
- Sales in Market B are growing 12% YoY with lower volatility.
- Prophet model achieved the lowest MAPE of 6.8%.

---

## 🧰 Tools Used
Python · Pandas · Matplotlib · Seaborn · Prophet · Statsmodels

---

## 📊 Output Example
![Forecast Plot](./visuals/forecast_plot.png)

---

## 🚀 Next Steps
- Integrate external data (weather, marketing spend).
- Automate monthly forecast update pipeline.
