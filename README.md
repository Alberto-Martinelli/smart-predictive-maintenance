# 🚀 Smart Predictive Maintenance for Industrial Equipment

## 📌 Overview  
This project aims to develop a **predictive maintenance system** for industrial machinery using **Advanced Machine Learning techniques**. We leverage the **CMAPSS dataset** to model the **Remaining Useful Life (RUL)** of machinery components, implement **various machine learning models**, and optimize maintenance scheduling through **reinforcement learning**.

## 📂 Project Structure  
- **📊 Data Processing**:  
  - Dataset selection and exploration  
  - Exploratory Data Analysis (EDA)  
  - Feature engineering and preprocessing  
- **📈 Model Training**:  
  - Ensemble Learning (Random Forest, Gradient Boosting, XGBoost)  
  - Handling Imbalanced Data (Oversampling, Undersampling, SMOTEENN, Cost-Sensitive Learning)  
- **🤖 Model Selection**:  
  - AutoML with **TPOT**  
  - Model evaluation and comparison  
- **🔧 Maintenance Optimization**:  
  - Reinforcement Learning for maintenance scheduling  
  - Q-learning algorithm for policy optimization  

## 📊 Dataset  
We use the **CMAPSS (Commercial Modular Aero-Propulsion System Simulation) dataset**, a widely recognized dataset for predictive maintenance provided by **NASA’s Prognostics Center of Excellence**. It includes:  
✔ **Engine sensor readings**  
✔ **Operational settings**  
✔ **Remaining Useful Life (RUL) labels**  

📌 **Dataset source**: [CMAPSS Dataset](https://c3.ndc.nasa.gov/dashlink/resources/139/?utm_source=chatgpt.com)  

## 🔍 Key Findings  
✅ **Random Forest, Gradient Boosting, and XGBoost models** performed well, with **XGBoost** being the most robust.  
✅ **SMOTEENN** provided the best balance in handling **imbalanced data**.  
✅ **AutoML (TPOT) found the best model**, improving the **F1-score**.  
✅ **Reinforcement Learning** successfully optimized maintenance schedules, reducing unexpected failures.  

## 📌 Best Model Summary  
- **Best model**: **AutoML (TPOT)**  
- **F1-Score**: **0.873**  
- **Feature Importance**: **Sensor 9, Sensor 11, Sensor 2, Sensor 13, Sensor 12**  
- **Maintenance Policy**: **Q-learning optimized maintenance schedules efficiently**  

## 📜 Authors  
| Name                  | Role                  |
|-----------------------|----------------------|
| **Alessia Sarritzu**  | Project Contributor  |
| **Alberto Martinelli** | Project Contributor  |
| **Marco Riva**        | Project Contributor  |
| **Michele Pulvirenti** | Project Contributor  |

📅 **Project Date**: January 18, 2025  
