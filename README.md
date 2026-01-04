Sustainability AI: Building Energy & CO2 Predictor

📋 Project Overview
This project addresses the Complex Computing Problem (CCP) of predicting energy consumption and carbon footprints for university building rooms. By utilizing a Random Forest Regressor, the model analyzes the interdependence between hardware assets (ACs, Computers, GPUs) and usage patterns to draw meaningful sustainability insights.

🚀 Key Features
•	Data Merging Strategy: Combined two distinct datasets (300 samples total) to enhance model training and depth of analysis.
•	High Accuracy: Achieved an R² score of 0.915 for both power and emission predictions.
•	Interactive GUI: Features a Gradio dashboard for real-time "What-If" sustainability simulations.
•	K-Fold Validation: Evaluated using 5-Fold Cross-Validation to ensure robust generalization.

🛠️ Tech Stack
•	Language: Python
•	Libraries: Pandas, Scikit-learn, NumPy, Matplotlib, Seaborn
•	GUI: Gradio
•	Environment: Google Colab / Jupyter Notebook

📊 Results Summary
Metric	Power (kWh)	CO2 (kg)
RMSE	3.6860	2.2831
R² Score	0.9153	0.9156

📂 Dataset Source
The data used in this project represents building energy logs and is available in the /data folder of this repository.
