# 🚖 Taxi Fare Prediction — Capstone Project

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Regression-brightgreen.svg)
![Status](https://img.shields.io/badge/Status-Completed-success.svg)

---

## 🧭 Overview  
This capstone project focuses on building a **predictive machine learning model** to estimate taxi fares based on trip features such as pickup/drop-off coordinates, distance, and time-based factors.  
The model identifies key pricing patterns that enable **passengers**, **drivers**, and **taxi platforms** to make smarter, data-driven decisions.

---

## 🎯 Objectives  

- Predict taxi fares accurately using historical data.  
- Understand how trip attributes (distance, time, and location) influence pricing.  
- Develop a scalable, reproducible ML pipeline for future deployment.  

---

## 🧪 Methodology — *CRISP-DM Framework*

| Phase | Description |
|-------|--------------|
| **1. Business Understanding** | Define problem: estimating fare amount for transparency and optimization. |
| **2. Data Understanding** | Explore raw trip data, analyze variable distributions, detect anomalies. |
| **3. Data Preparation** | Handle missing data, remove outliers, engineer distance/time-based features. |
| **4. Modeling** | Build and evaluate regression models (Linear, Ridge, Lasso, Random Forest, XGBoost). |
| **5. Evaluation** | Compare RMSE and R² metrics to identify best performance. |
| **6. Deployment Readiness** | Prepare for integration into dashboards or real-time applications. |

---

## ⚙️ Tools & Technologies  

| Category | Stack |
|-----------|--------|
| **Language** | Python |
| **Libraries** | pandas, numpy, scikit-learn, xgboost, matplotlib, seaborn |
| **IDE / Environment** | Jupyter Notebook / Anaconda |
| **Methodology** | CRISP-DM (Cross-Industry Standard Process for Data Mining) |

---

## 🔑 Key Features Considered

- Trip Distance - Distance covered in the Trip
- Passenger Count - Number of passengers travelled.
- Is Rush Hour - Time of the trip falls under rush hour or not?
- Is Night  - Trip happened in Day/Night?
- Is Weekend - Trip on Weekday/Weekend?

---

## 📖 Notebooks
Explore the Jupyter notebook below with in-depth analysis and insights:

- [**Model and insights**](https://github.com/NiranjanaAnand/MLAI_Mod_24_CapstoneProject/blob/main/Capstone_Project_Taxi_Fare_Prediction.ipynb) – Data analysis, feature engineering, and model building.

---
## 📊 Model Development  

- **Baseline Models:** Linear, Ridge & Lasso Regression — established benchmark.  
- **Advanced Models:** Random Forest & XGBoost — captured complex non-linear relationships.  
- **Best Performing Model:** `XGBoost Regressor`  

### 🧩 Performance Metrics  
| Metric | Score (Test Set) |
|--------|------------------|
| RMSE | ~3.327455 |
| R² | ~0.91 |

**Key Takeaway:**  
XGBoost effectively modeled non-linear fare behavior and delivered the lowest prediction error among all approaches.

---

## 📈 Results & Insights  

## 💡 Business Insights  

- **Trip distance** remains the primary determinant of fare.  
- **Peak hours** and **weekends** drive price surges due to demand spikes. 
- **Data preprocessing** (scaling, encoding, and outlier handling) improved model stability and accuracy.

---

## 🧠 Business Recommendations  

- Embed fare prediction logic into **mobile booking apps** for customer transparency.  
- Use model outputs to support **driver allocation** and **dynamic surge pricing**.  
- Implement **predictive dashboards** to monitor demand and optimize dispatch operations.  
- Extend pricing strategies to **ride-sharing** and **EV-based** taxi services.

---

## 🔮 Future Enhancements  

- Integrate **real-time weather and traffic APIs** to enhance context awareness.  
- Deploy as a *Web application** for user interaction.  
- Explore using **deep learning models** to understand and predict how fares change over time. 
- Apply **K-Means clustering** to group nearby pickup and drop-off locations and find pricing patterns in different areas.

---

## 🧾 Author  

**Niranjana Badrinarayanan**   
📅 *Capstone Submission – 2025*  
🔗 [linkedin.com/in/niranjana-badrinarayanan](https://www.linkedin.com/in/niranjana-badrinarayanan-3068b512/) • [Email](niranjana.badri@gmail.com) 

---



