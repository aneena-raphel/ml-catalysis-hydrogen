# Hydrogen Adsorption Energy Prediction with Machine Learning

![Python](https://img.shields.io/badge/python-3.9+-blue.svg)
![Jupyter](https://img.shields.io/badge/jupyter-notebook-orange.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

## 📌 Project Overview
This project applies **machine learning (Linear Regression, Random Forest, XGBoost)** to predict **hydrogen adsorption energies** (*E_ads*) on transition-metal catalysts using simple electronic descriptors.  

Hydrogen adsorption energy is a key descriptor in **catalyst screening for hydrogen evolution and hydrogenation reactions**. By combining basic atomic features (atomic number, electronegativity, d-electron count) with ML models, this project demonstrates how **data-driven approaches** can complement traditional **DFT calculations** in computational catalysis.

---


---

## 📊 Dataset
- **Size:** 48 samples  
- **Features:**
  - `atomic_number`  
  - `electronegativity`  
  - `d_electron_count`  
  - `facet` (surface orientation)  
- **Target:** `E_ads` (hydrogen adsorption energy, eV)

---

## ⚙️ Methods
- **Exploratory Data Analysis (EDA)** with Seaborn & Matplotlib  
- **Machine Learning Models:**
  - Linear Regression  
  - Random Forest Regressor  
  - XGBoost Regressor  
- **Performance Metrics:**
  - Mean Absolute Error (MAE)  
  - Coefficient of Determination (R²)  
- **Visualizations:**
  - Pair plots  
  - Parity plots (predicted vs. actual)  
  - Feature importance analysis  

---

## 🚀 Getting Started

### 1️⃣ Clone the repository
```bash

pip install -r requirements.txt  #Install dependencies

jupyter notebook notebook/hydrogen_adsorption_ML.ipynb  #Open Jupyter Notebook and run


git clone https://github.com/aneena-raphel/hydrogen-adsorption-ml.git
cd hydrogen-adsorption-ml
