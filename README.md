# AtliQ Motors India – EV Sales Analysis

## 📘 Project Overview
AtliQ Motors India is an electric vehicle (EV) manufacturer and distributor seeking to expand its footprint across Indian states. This project performs an **end-to-end analysis** of EV sales data through **Exploratory Data Analysis (EDA)** and an **interactive Power BI dashboard**. The objective is to uncover sales trends, regional performance, growth patterns, and insights for strategic decision-making.

The analysis integrates three datasets:
1. **dim_date.csv** – Contains fiscal dates and derived calendar features.
2. **electric_vehicle_sales_by_makers.csv** – Captures EV sales volume by manufacturer, model, and year.
3. **electric_vehicle_sales_by_state.csv** – Represents total vehicle sales (electric and non-electric) by state and year.

---

## 🎯 Key Objectives
- Understand EV adoption trends across India from 2022–2024.
- Identify top-performing manufacturers and states.
- Analyze the compound annual growth rate (CAGR) in EV sales.
- Compare EV penetration across states and years.
- Provide actionable insights for policy, production, and distribution planning.

---

## 🧩 Features and Functionality

### **1. Exploratory Data Analysis (EDA)**
The EDA was conducted in Python using pandas, numpy, matplotlib, and seaborn. Key steps included:
- **Data Cleaning:** Removal of duplicates, handling of nulls, datatype corrections.
- **Feature Engineering:** Derivation of fiscal years, quarters, and EV penetration metrics.
- **Trend Analysis:** Temporal evolution of EV sales across states and makers.
- **Correlation Study:** Relationship between total vehicles sold and EV share.
- **CAGR Computation:** State-wise and manufacturer-wise growth rate analysis.

### **2. Power BI Dashboard**
A multi-page Power BI report was built to visualize findings from the EDA. The dashboard includes:
- **KPI Page:** Total EVs sold, YoY growth, CAGR, and EV penetration ratio.
- **Geographical View:** State-wise EV adoption and market size heatmap.
- **Maker Comparison:** Top 10 manufacturers by cumulative EV sales.
- **Trend View:** Quarterly and yearly EV growth visualization.
- **State Insights Page:** Drill-down filters for each state showing detailed trend and growth patterns.

---

## 📊 Key Insights

### **From EDA**
- **Data Quality:** Minimal nulls, with consistent fiscal-year formatting.
- **EV Growth:** EV sales grew significantly post-2022, with several states showing >80% CAGR.
- **Top States:** Maharashtra, Karnataka, and Tamil Nadu lead in total EV sales volume.
- **Emerging Markets:** Northeastern and smaller states show strong growth momentum despite lower base.
- **Manufacturer Trends:** Tata Motors consistently leads in total EV sales, followed by MG Motors and Mahindra.
- **EV Penetration:** The ratio of EVs to total vehicles increased steadily, surpassing **4% national average** by 2024.

### **From Power BI Dashboard**
- **CAGR Leaders:** Gujarat, Kerala, and Delhi showed exceptional EV growth between 2022–2024.
- **Sales Concentration:** Top 5 states account for ~60% of total EV sales nationwide.
- **Yearly Seasonality:** Sales tend to peak in Q3 (festive and policy rollout periods).
- **Maker Diversity:** New entrants such as Hyundai and Kia exhibit sharp growth curves.
- **Geographical Patterns:** Southern and Western India remain dominant EV markets, while Eastern regions catch up.

---

## ⚙️ Installation & Setup Instructions

### **For EDA (Python Environment)**
```bash
# Clone this repository
git clone https://github.com/<your-username>/AtliQ-Motors-EV-Sales-Analysis.git
cd AtliQ-Motors-EV-Sales-Analysis

# Create virtual environment
python -m venv venv
venv\Scripts\activate     # (Windows)
# or
source venv/bin/activate    # (Mac/Linux)

# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook EDA.ipynb
```

### **For Power BI**
1. Open `AtliQ_EV_Sales.pbix` file in Power BI Desktop.
2. Ensure data source paths match local CSV/Excel dataset paths.
3. Refresh data and view the full dashboard.

---

## 🧠 Tech Stack & Dependencies
- **Languages:** Python (for EDA), DAX & M (for Power BI)
- **Libraries:** pandas, numpy, matplotlib, seaborn, plotly
- **Tools:** Power BI Desktop, Jupyter Notebook, Git
- **Data Sources:** CSV files – `dim_date`, `electric_vehicle_sales_by_makers`, `electric_vehicle_sales_by_state`

---

## 📁 File Structure
```
AtliQ-Motors-EV-Sales-Analysis/
│
├── data/
│   ├── dim_date.csv
│   ├── electric_vehicle_sales_by_makers.csv
│   ├── electric_vehicle_sales_by_state.csv
│
├── EDA.ipynb                     # Exploratory Data Analysis notebook
├── EV_Sales_Analysis.pbix           # Power BI dashboard file
├── README.md                     # Project documentation
├── requirements.txt              # Python dependencies
└── assets/                       # Screenshots of Power BI dashboards
```

---

## 👤 Author
**Harddik Singh**  
Data Analyst | Power BI Developer | Python & SQL Enthusiast  
📧 Email: harddik05@gmail.com 
---

## 🪪 License
This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute with proper attribution.
