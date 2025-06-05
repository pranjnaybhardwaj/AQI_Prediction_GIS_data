# AQI_Prediction_GIS_data
Machine learning-based AQI prediction across Dublin using geospatial data collected via DPD vans. Combines GIS feature engineering, SARIMA, LSTM modeling, and interactive AQI heatmaps.
# 📍 Dublin AQI Prediction Using Geospatial Data

Predicting AQI across Dublin using geospatial data collected by DPD delivery vans equipped with environmental sensors. This project applies machine learning and GIS techniques to forecast pollution levels and visualize spatial trends interactively.

---

## 🧠 Project Summary

This project builds a spatially-aware ML pipeline to:
- Predict real-time AQI levels across Dublin
- Engineer temporal + geospatial features (from GPS and timestamps)
- Visualize AQI patterns across the city using interactive maps

---

## 📦 Tech Stack

- **Languages**: Python
- **ML Libraries**: SARIMA, LSTM, XGBoost, Scikit-learn, SHAP
- **Geospatial Tools**: GeoPandas, Folium, Pandas
- **Notebook**: Jupyter (.ipynb)
- **Version Control**: Git, GitHub

---

## 📊 ML Models

| Model           | MAE (Mean Absolute Error) |
|----------------|----------------------------|
| SARIMA         | ~4.3                       |
| Random Forest  | ~5.0                       |
| Linear Reg     | ~6.4                       |

- Best performance from SARIMA + engineered spatial-temporal features
- Feature importance analyzed using SHAP

---

## 🌍 GIS Features

- Raw data from DPD vans: GPS-tagged pollutant readings across Dublin
- Engineered spatial features from lat/long and Dublin zone shapes
- Mapped AQI values by zone + time to reveal pollution hotspots
- Created interactive **Folium heatmaps** to explore predictions

---

## 📁 Repository Structure

├── notebook/
│ └── AQ_Prediction_stripped.ipynb 

