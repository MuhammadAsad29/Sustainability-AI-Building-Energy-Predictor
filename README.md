🌱 Sustainability AI: Building Energy & CO₂ Predictor
📋 Project Overview

This project addresses a Complex Computing Problem (CCP) focused on predicting energy consumption and carbon emissions for university building rooms.
Using a Random Forest Regressor, the system models the interdependence between hardware assets (ACs, Computers, GPUs) and usage patterns to generate meaningful sustainability insights.

🚀 Key Features

Data Merging Strategy
Combined two distinct datasets (300 samples total) to improve model learning and analytical depth.

High Prediction Accuracy
Achieved an R² score of ~0.915 for both power consumption and CO₂ emission predictions.

Interactive GUI
Implemented a Gradio dashboard for real-time “What-If” sustainability simulations.

K-Fold Cross Validation
Evaluated using 5-Fold Cross-Validation to ensure robust generalization and reliability.

🛠️ Tech Stack

Programming Language: Python

Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

GUI Framework: Gradio

Environment: Google Colab / Jupyter Notebook

📊 Results Summary
Metric	Power (kWh)	CO₂ (kg)
RMSE	3.6860	2.2831
R² Score	0.9153	0.9156

📂 Dataset Source

The dataset represents building energy usage logs and is available in the /data folder of this repository.

🌍 Impact

This project demonstrates how AI-driven sustainability analytics can help institutions:

Reduce energy waste

Track carbon footprints

Make data-driven infrastructure decisions
