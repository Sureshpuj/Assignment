# 📊 Amazon Sales Data Analysis with Matplotlib and Seaborn

This project performs descriptive and predictive analysis on Amazon sales data using Python libraries like `pandas`, `matplotlib`, and `seaborn`. The goal is to extract business insights and represent them using clear and visually appealing static dashboards.

---

## 🔍 Objective

- Perform **Descriptive Analysis** to understand historical performance
- Use **Predictive-like visualizations** to spot future trends
- Visualize key sales metrics using **Matplotlib and Seaborn**
- Build clear dashboards with interrelated plots

---

## 📁 Dataset

The dataset contains order-level details including:
- `Order ID`, `Order Date`, `Ship Date`
- `EmailID`, `Geography`, `Category`, `Product Name`
- `Sales`, `Quantity`, `Profit`

📌 Format: `.xlsx`

---

## 📊 Visualizations Created

### 1. **Monthly Sales Trend**
- **Type**: Line Chart
- **Tool**: Seaborn
- **Insights**: Highlights sales performance month-over-month.

### 2. **Profit by Geography**
- **Type**: Horizontal Bar Chart
- **Tool**: Seaborn
- **Insights**: Shows top 10 regions contributing to profit.

### 3. **Profit Heatmap (Category vs Geography)**
- **Type**: Heatmap
- **Tool**: Seaborn
- **Insights**: Visual cross-analysis of which categories perform best in which geographies.

---

## 🛠️ Tools Used

| Tool        | Purpose                    |
|-------------|-----------------------------|
| `pandas`    | Data manipulation & analysis |
| `matplotlib`| Plot rendering               |
| `seaborn`   | High-level statistical visuals|
| `Jupyter`   | Interactive coding environment|

---

## 🧮 Key Python Concepts Used

- `groupby()` and aggregation (`sum`)
- `pivot_table()` for heatmaps
- Date formatting using `dt.to_period('M')`
- Custom styling in plots (colors, labels, grids)

---

## 🧠 Insights

- Sales trends reveal peak and low months for planning.
- Certain geographies dominate in profits — ideal for targeting.
- Category-Geography combinations offer strategic positioning opportunities.

---

## 🚀 How to Run

1. Clone the repo or download the project files.
2. Ensure you have Python installed.
3. Install required libraries:
   ```bash
   pip install pandas matplotlib seaborn 


