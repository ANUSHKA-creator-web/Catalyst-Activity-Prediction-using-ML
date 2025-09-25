🧪 Machine Learning Model for Predicting Catalytic Activity of CO₂-to-Methanol Conversion


📌 Project Overview
This project applies machine learning to predict the catalytic activity of experimental catalysts in the CO₂ hydrogenation to methanol reaction. By leveraging regression models, we aim to assist in accelerating catalyst design and optimizing experimental efforts in sustainable fuel production.

📊 Dataset
Type: Experimental catalytic activity dataset
Samples: N = 234
Features: Catalyst descriptors & experimental conditions
Target: Catalytic activity (measured experimentally)
⚙️ Methodology
Data Preprocessing

Cleaned and normalized experimental dataset
Handled missing values and outliers
Feature scaling and selection
Model Development

Implemented regression models:
Linear Regression
Random Forest
XGBoost
Hyperparameter tuning and cross-validation
Evaluation Metrics

Coefficient of Determination (R²)
Mean Absolute Error (MAE)
Root Mean Square Error (RMSE)
Diagnostics & Visualization

Actual vs Predicted plots with regression line
Residual distribution (histogram + KDE)
Residuals vs Actual to detect bias/outliers
📈 Results
Best Model Performance:
R² = 0.748
MAE = 58.59
RMSE = 93.34
Model successfully captured ~75% of variance in catalytic activity.
Errors increase at high catalytic activity values, suggesting need for more data in that region.
🔍 Key Visualization
Model Diagnostics
Figure: Actual vs Predicted, Residual Distribution, and Residuals vs Actual

🔍 Key Insights
Machine learning can reliably predict catalyst performance from experimental data.
Model underpredicts at high catalytic activity → more balanced dataset or nonlinear models needed.
Demonstrates the potential of AI-driven catalyst screening for sustainable fuel production.
🛠️ Tech Stack
Languages: Python
Libraries: scikit-learn, pandas, NumPy, matplotlib, seaborn, Jupyter
Tools: GitHub, Jupyter Notebook

📌 Future Work
Expand dataset with more high-activity samples
Explore deep learning and ensemble models
Apply SHAP/feature importance for catalyst interpretability
Deploy as a simple web app for catalyst activity prediction

👤 Authors
Aman Malik, IIT Madras
Anushka Singh, IIT Guwahati 🔗 Email | Email
