# ClimateChangeModeling
🌍 Climate Change Temperature Anomaly Modeling (India)
This project analyzes historical climate data and predicts future temperature anomalies for India using machine learning models. The goal is to better understand climate trends and project potential impacts under changing conditions.

🔍 Project Overview
Dataset: GlobalLandTemperaturesByCountry.csv

Focus Region: India

Time Span: 1743–2013 (cleaned and processed)

Target Variable: Yearly average temperature anomaly

Models Used:

Linear Regression

Random Forest Regressor

Gradient Boosting Regressor

Tech Stack: Python, Pandas, Matplotlib, Scikit-learn, Seaborn

📈 Key Features
Data preprocessing and lag feature engineering

Visualization of temperature trends across years

Training and evaluation of multiple regression models

Performance metrics: MAE, MSE, R² Score

Future temperature anomaly projection using trained model

Scenario analysis with hypothetical CO₂ increase

📁 Files Included
climate_modeling.ipynb — Jupyter notebook for running the entire pipeline

GlobalLandTemperaturesByCountry.csv — Dataset (you must download it from Kaggle)

README.md — Project description and usage instructions

📦 Installation & Usage
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/climate-change-modeling.git
cd climate-change-modeling
Install dependencies:

bash
Copy
Edit
pip install pandas matplotlib seaborn scikit-learn
Run the Jupyter notebook:

bash
Copy
Edit
jupyter notebook climate_modeling.ipynb
📊 Sample Output
Line chart of temperature anomalies over time

Actual vs Predicted plots for each model

Projected temperature anomaly for the next year

Scenario-based projections for increasing trends

📚 Data Source
Kaggle - Climate Change: Earth Surface Temperature Data

📌 Future Enhancements
Add CO₂ concentration as a feature

Support multi-country comparisons

Integrate with Streamlit for web deployment

🧑‍💻 Author
Name: [Rohit sen]

Contact: [rsen95759@gmail.com]

