# Real Estate Price Prediction

## Overview

This project aims to predict real estate prices based on various input features such as location, property type, and physical attributes. The prediction model is trained using machine learning, specifically a gradient boosting model.

## Files

- `il_avg_label.txt`: Average price labels for cities.
- `il_id_label.json`: City IDs and corresponding labels.
- `ilce_avg_label.txt`: Average price labels for districts.
- `ilce_id_label.json`: District IDs and corresponding labels.
- `mahalle_avg_label.txt`: Average price labels for neighborhoods.
- `mahalle_id_label.json`: Neighborhood IDs and corresponding labels.
- `konut_tipi_id_label.json`: Property type IDs and corresponding labels.
- `bulundugu_kat_id_label.json`: Floor IDs and corresponding labels.
- `konut_kat_kombinasyon_id_label.json`: Combination of property type and floor IDs with corresponding labels.
- `gradient_boosting_model_2.pkl`: Trained gradient boosting model.

## Prerequisites

Before running the prediction script, make sure you have the following installed:

- Python
- Required Python packages (NumPy, pandas, scikit-learn, joblib)

Install the necessary packages using the following command:

```bash
pip install numpy pandas scikit-learn joblib
