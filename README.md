MOST IMPORTANT IS HOW TO USE: FOR THIS SEARCH FOR how_to_useNrun file amongts this many files and follow the instructions

STRUCTURE
├── data/                   # Input and processed CSVs
├── notebooks/              # Jupyter notebooks (EDA + Dashboard)
├── requirements            # Python package list:
                              pandas
                              numpy
                              matplotlib
                              seaborn
                              plotly
                              ipywidgets
                              scikit-learn
                              qgrid
└── README.md               # Project summary & instructions


# 📦 Wine Inventory Optimization Dashboard

A data science project built to **optimize wine & spirits inventory, pricing, and reorder decisions** for retail businesses using sales and purchase analytics.

---

## 📈 Project Objective

To build a **data-driven dashboard** and backend logic that helps:
- Predict product demand
- Identify low-stock or overstock items
- Recommend reorder quantities
- Analyze pricing sensitivity (elasticity)

---

## 💡 Problems Solved

✅ Combined sales, purchases, and inventory data  
✅ Calculated **Net Demand** per product  
✅ Flagged **Inventory Health** (Low, Balanced, Overstock)  
✅ Estimated **Price Elasticity of Demand (PED)**  
✅ Built an **interactive trend dashboard** using Jupyter widgets & Plotly

---

## 📊 Features

### 🔍 Data Analysis
- Total Sales, Purchases, Begin/End Inventory
- Net Demand = Sales - Purchases
- Inventory Health flags
- Price Elasticity Estimation using regression

### 📈 Dashboard (in Jupyter Notebook)
- Dynamic dropdown filters (Store, Brand, Inventory ID)
- Net Demand trend plots (synthetic 6-month time series)
- Product control grid (via `qgrid` or similar)

---


