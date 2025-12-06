# 📊 Sales Data Visualization & Business Insights

This project contains a complete **data analytics and visualization workflow** built using Python, Pandas, Matplotlib, Seaborn, and Folium.  
The aim is to analyse sales, orders, delivery performance, product demand, customer locations, and payment insights using multiple CSV datasets.

---

## 🚀 Project Features

### ✔️ **1. Data Loading & Cleaning**
- Loaded multiple CSV files including:
  - `Suppliers.csv`
  - `Products.csv`
  - `Customers.csv`
  - `OrderDetails.csv`
  - `Orders.csv`
  - `Shippers.csv`
  - `Payments.csv`
- Handled missing values, incorrect datatypes, and cleaned datetime columns.

---

## 📦 **2. Merging Datasets**
Performed dataset merging to generate unified views such as:
- Orders × Shippers → delivery analytics  
- Products × OrderDetails → sales insights  
- Orders × Payments → payment method trends  

---

## 🚚 **3. Delivery Performance Analysis**
- Calculated correct delivery time using:
- Visualized **fastest shipping companies** using bar charts.
- Identified companies with the most efficient delivery times.

---

## 🛒 **4. Product-Level Analytics**
### 🔹 Most Selling Products  
Grouped data by product and calculated:
- Total quantity sold  
- Top 10 best-selling items using bar plots  

### 🔹 Profit Analysis  
Computed:

DeliveryDate - ShipDate

- Visualized **fastest shipping companies** using bar charts.
- Identified companies with the most efficient delivery times.

---

## 🛒 **4. Product-Level Analytics**
### 🔹 Most Selling Products  
Grouped data by product and calculated:
- Total quantity sold  
- Top 10 best-selling items using bar plots  

### 🔹 Profit Analysis  
Computed:

Profit = (Market Price - Sale Price) × Quantity

Visualized:
- Top profitable products  
- Profit contribution per item  

---

## 🌍 **5. Geographic Insights (Customers in India)**
- Filtered customers belonging to **India**
- Retrieved city & state-level statistics
- Used **Geopy** + **Folium** to generate:
  - City-wise map with markers
  - State-wise customer distribution map

---

## 💳 **6. Payment Insights**
Merged orders with payment data to visualize:
- Most used payment methods
- Order volume per payment type using pie charts  

---

## 📈 Visualization Tools Used
- **Matplotlib** — bar charts, line charts
- **Seaborn** — advanced statistical plots
- **Folium** — Interactive maps
- **Pandas** — grouping, merging, transformation

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Folium
- Geopy

---

## 📁 Folder Structure
│── Analysis.ipynb # Main analysis notebook
│── Suppliers.csv
│── Products.csv
│── Orders.csv
│── Customers.csv
│── OrderDetails.csv
│── Shippers.csv
│── Payments.csv
│── README.md


---

## 📌 How to Run
```bash
pip install pandas matplotlib seaborn folium geopy

Open the notebook:
jupyter notebook Analysis.ipynb


✨ Outcome

This project provides:

Actionable business insights

End-to-end data cleaning + visualization workflow

Ready-to-use analytics examples

Interactive geographic mapping



🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you’d like to modify.


🧑‍💻 Author

Sahib Chouhan
Data Analysis • Machine Learning • Visualization






