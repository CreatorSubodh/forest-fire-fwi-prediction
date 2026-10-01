# Algerian Forest Fire FWI Prediction

A Machine Learning project that predicts the **Fire Weather Index (FWI)** using weather conditions and fire-weather indicators from the **Algerian Forest Fires dataset**.

The project covers the complete Machine Learning workflow, including data cleaning, exploratory data analysis, feature selection, model training, evaluation, and deployment using Streamlit.

---

## Project Overview

Forest fire conditions are influenced by environmental and weather factors such as temperature, humidity, wind speed, rainfall, and fire-weather indicators.

This project uses the **Algerian Forest Fires dataset** to build a regression model for predicting the **Fire Weather Index (FWI)**.

The trained model is deployed as an interactive **Streamlit web application**, where users can enter weather and fire-weather conditions and receive an estimated FWI value.

---

## Features

The final model uses the following input features:

- Temperature
- Relative Humidity (RH)
- Wind Speed (Ws)
- Rain
- FFMC (Fine Fuel Moisture Code)
- DMC (Duff Moisture Code)
- ISI (Initial Spread Index)
- Region

### Target Variable

- **FWI (Fire Weather Index)**

> The `Classes` column was not used as a model input because it is directly related to fire conditions and could introduce target leakage.

---

## Machine Learning Workflow

The project follows these steps:

Raw Dataset
     ↓
Data Cleaning
     ↓
Exploratory Data Analysis
     ↓
Feature Selection
     ↓
Train-Test Split
     ↓
Feature Scaling
     ↓
Model Training
     ↓
Model Comparison
     ↓
Model Evaluation
     ↓
Model Saving
     ↓
Streamlit Deployment