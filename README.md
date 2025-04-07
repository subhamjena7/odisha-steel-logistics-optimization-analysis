# Odisha Steel Logistics Optimization Analysis 🚚📊

A data-driven project to optimize inbound logistics for Odisha’s steel industry using predictive modeling, supply chain analytics, and dashboard visualization.

## 📌 Overview

This project analyzes and optimizes the raw material supply chain logistics for a hypothetical steel manufacturing unit in Odisha, India — inspired by real-world players like **Tata Steel** and **Jindal Steel**. Using historical and simulated datasets, it uncovers inefficiencies, builds a predictive model for shipment delays, and recommends actionable strategies for cost and delay reduction.

### 📁 Project File: `OSCEOSI.zip`
All notebooks, datasets, and deliverables are packaged inside the project archive. Refer to the PDF report for a structured summary.

---

## 🔍 Problem Statement

Odisha, a steel manufacturing hub, faces major challenges in 2025 like rising fuel costs, transportation delays, and inventory mismanagement. These inefficiencies inflate operational costs and threaten competitiveness.

This project seeks to:
- Identify delay hotspots.
- Analyze transport-mode trade-offs.
- Forecast shipment delays.
- Recommend optimized scheduling and inventory strategies.

---

## 🎯 Objectives

- 📈 **Quantify inefficiencies** in transportation time, cost, and delays.
- 🤖 **Predict delays** using machine learning (Random Forest).
- 📊 **Visualize supply chain metrics** via interactive dashboards.
- 🛠️ **Recommend improvements** for transport and inventory.

---

## 🗂️ Project Structure

| Phase | Description |
|-------|-------------|
| `1. Exploratory Data Analysis.ipynb` | Data cleaning, transformation, and statistical summaries |
| `2. Feature Engineering.ipynb` | Feature extraction (transit time, time-of-day, etc.) |
| `3. Model Development.ipynb` | Predictive modeling of shipment delays |
| `Odisha_Steel_SupplyChain_2025_Cleaned.csv` | Cleaned logistics dataset |
| `Odisha_Steel_SupplyChain_2025_Features.csv` | Final modeling-ready feature set |
| `Odisha Steel Logistics Optimization Report_Subham Jena.pdf` | Final report with findings, strategy, and impact |

---

## 📊 Key Insights

- **Truck vs Rail**: Trucks are faster but significantly more expensive. Rail is viable when planned off-peak.
- **Peak Congestion**: Shipments between **8:00–10:00 AM** have the highest average delays.
- **Inventory Risk**: Delays often result in inventory drops — leading to potential production halts.
- **Predictive Model**: A Random Forest model achieved an **R² of 0.78** in forecasting shipment delays.

---

## ✅ Recommendations

- Shift routes like **Sundargarh ➝ Kalinganagar** to **Rail** to reduce costs and maintain reliability.
- Avoid departures during **morning congestion** to minimize delays.
- Maintain a **minimum buffer of 550 tons** in inventory to ensure continuity.
- Integrate the delay prediction model into scheduling tools or ERP systems.

---

## 📈 Tools & Technologies

- **Python** (Pandas, Seaborn, Scikit-learn, Matplotlib)
- **Jupyter Notebook**
- **Power BI** (for interactive dashboards)
- **Machine Learning** (Random Forest Regressor)

---

## 📂 Dataset

- Title: [Supply Chain Data for a Steel Manufacturing Unit – Kalinganagar, Odisha (2025)](https://www.kaggle.com/datasets/worksubhamm/supply-chain-data-for-a-steel-manufacturing-unit)
- Simulated real-world logistics data from Jan–July 2025.

---

## 📜 Report

📄 The complete analysis, insights, and recommendations are available in:
**`Odisha Steel Logistics Optimization Report_Subham Jena.pdf`**

---

## 🙋‍♂️ Author

**Subham Jena**  
Data Science | Supply Chain Optimization | Predictive Analytics  
📎 [LinkedIn Profile](https://www.linkedin.com/in/subhamjena201/)

---

## 🚀 Future Enhancements

- Integration with **live GPS shipment feeds** for real-time monitoring.
- Advanced ML models (e.g., XGBoost, LSTM for time-series delays).
- Incorporate weather or road conditions as external features.
- Expand to **outbound logistics** and customer delivery chains.

---

## 📌 License

This project is for academic and demonstration purposes only. Data is simulated and does not reflect proprietary information from any organization.

---

_Optimizing supply chain efficiency one shipment at a time!_
