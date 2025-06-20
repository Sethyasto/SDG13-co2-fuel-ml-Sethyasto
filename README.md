# SDG13-co2-fuel-ml-Sethyasto
# 🌍 Climate Action with Machine Learning – SDG 13

**Project Title**: Predicting CO₂ Emissions Per Capita from Fuel Use  
**Author**: [Your Name]  
**Repository**: SDG13-co2-fuel-ml-Sethyasto  
**Week 2 Assignment – AI for Sustainable Development**

---

##  Project Overview

This project supports **UN Sustainable Development Goal 13: Climate Action** by building a machine learning model that predicts **CO₂ emissions per capita** based on different types of fuel usage (gas, liquid, solid, cement, flaring).

###  Objective
To analyze fuel consumption trends and estimate their per-person environmental impact, enabling better policy and energy decisions worldwide.

---

##  Machine Learning Approach

- **Problem Type**: Regression
- **Algorithm Used**: Random Forest Regressor
- **ML Methodology**:
  - **Input features**:
    - Total CO₂ emissions
    - Gas Fuel
    - Liquid Fuel
    - Solid Fuel
    - Cement
    - Gas Flaring
  - **Target variable**:
    - CO₂ emissions per capita (tons per person)

---

##  Dataset

- Source: [Fossil CO2 emissions dataset (Global)](https://github.com/datasets/co2-fossil-global)
- Format: CSV
- Size: 260 records
- Features used:
  - `Total`, `Gas Fuel`, `Liquid Fuel`, `Solid Fuel`, `Cement`, `Gas Flaring`, `Per Capita`

---

## 🛠 Tools & Libraries

- Python
- Google Colab
- `pandas`, `numpy` for data processing
- `scikit-learn` for machine learning
- `matplotlib`, `seaborn` for visualization

---

##  Results

| Metric               | Value           |
|----------------------|------------------|
| Mean Absolute Error  | ~[Your MAE]      |
| R² Score             | ~[Your R² Score] |

> The model showed a strong correlation between predicted and actual CO₂ emissions per capita, demonstrating the predictive power of fuel consumption data.

---

##  Visualization

![Scatter Plot: Actual vs Predicted](images/actual-vs-predicted.png)

---

##  Ethical Reflection

- **Bias**: The dataset may lack representation of individual country-level factors and developing regions.
- **Fairness**: By focusing on fuel types rather than country names, the model avoids geopolitical bias.
- **Sustainability**: Helps target energy sectors with the highest per-person CO₂ impact, aiding in cleaner transitions.

---

## Folder Structure
SDG13-co2-fuel-ml-Sethyasto
├── climate_model.ipynb
├── README.md
├── summary_report.pdf
├── images/
│ └── actual-vs-predicted.png


---

## 🎤 Demo

🕒 5-minute demo will walk through:
1. Project goal and SDG relevance
2. Data and model pipeline
3. Results interpretation
4. Ethical considerations

---

##  How to Run

1. Open `climate_model.ipynb` in Google Colab.
2. All cells are executable — from data load to predictions.
3. Output graphs and evaluation appear inline.

---

##  License

MIT License – Feel free to reuse and improve!

---

##  Acknowledgements

- UN Sustainable Development Goals (https://sdgs.un.org/)
- Open CO₂ Emissions Dataset (https://datahub.io/core/co2-fossil-global)


