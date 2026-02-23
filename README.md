# 📦 Smart Warehouse Inventory Management System

An AI-powered warehouse inventory monitoring and decision-support system that combines demand forecasting, reinforcement learning–based inventory policies, supplier analytics, and an interactive Streamlit dashboard.

This project demonstrates a complete end-to-end data science pipeline:
**data ingestion → preprocessing → feature engineering → forecasting → RL optimization → visualization**

---

## 🚀 Features

* 📊 Interactive Streamlit dashboard for warehouse monitoring
* 📈 7-day demand forecasting with confidence intervals
* ⚠️ Automated alert system for low stock and risks
* 🤖 Reinforcement Learning (DQN/PPO) inventory optimization
* 🏭 Supplier performance analytics
* 📉 Historical demand and stock trend visualization
* 📦 End-to-end reproducible ML pipeline

---

## 🧠 Tech Stack

**Programming:**
Python

**Data & ML:**
pandas, NumPy, scikit-learn

**Reinforcement Learning:**
Stable-Baselines3, Gymnasium, PyTorch

**Visualization & Dashboard:**
Plotly, Streamlit, Matplotlib

**External Data Sources:**
FRED Economic Data, Google Trends, Retail datasets

---

## 📂 Repository Structure

```
Smart-Warehouse-Inventory-Management/
│
├── smart_warehouse_inventory_management.ipynb   # Main project notebook
├── requirements.txt                              # Dependencies
├── README.md
│
├── images/                                       # Dashboard screenshots & plots
│
└── report                                       # Final project report PDF
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/Smart-Warehouse-Inventory-Management.git
cd Smart-Warehouse-Inventory-Management
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Project

### Option 1 — Run Notebook

Open and run:

```
smart_warehouse_inventory_management.ipynb
```

Run all cells from top to bottom.

The notebook will:

* generate datasets (if not present)
* train forecasting models
* run RL policy evaluation
* display dashboard visuals

---

### Option 2 — Run Dashboard with Streamlit

1. Export notebook as Python file

```
File → Download → .py
```

2. Run:

```bash
streamlit run smart_warehouse_inventory_management.py
```

---

## 📊 Example Outputs

The system provides:

* Inventory KPIs dashboard
* Forecast vs actual demand plots
* Supplier reliability charts
* Reinforcement learning cost-service comparison
* Stock risk alerts

Screenshots available in `/images`.

---

## 📄 Project Report

Full academic report available in:

```
/report
```

---

## 🎯 Key Contributions

* Integrated forecasting + RL decision system
* Multi-dataset warehouse simulation
* Lightweight architecture suitable for Colab or local machines
* End-to-end deployable analytics dashboard

---

## 🔮 Future Improvements

* Real warehouse ERP/WMS integration
* IoT sensor-based real-time inventory tracking
* Automated retraining pipeline
* Hierarchical time-series forecasting
* Role-based dashboard authentication

---

## 👨‍💻 Author

**Abhinav Vajinapalli**
AI/ML Student | Data Science | Reinforcement Learning | Full-Stack ML Systems

---

## ⭐ If you like this project

Consider starring the repository ⭐ to support the work.

