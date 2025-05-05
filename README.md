# AI-Powered-Air-Quality-Alert-System-
This project is an AI-based system that predicts Air Quality Index (AQI) levels using environmental data and triggers alerts when pollution levels become harmful. It leverages the Random Forest algorithm for accurate AQI prediction
🔍 Features
Predicts AQI using pollutants (PM2.5, PM10, NO₂, CO, SO₂) and weather data.

Triggers health alerts based on predicted air quality levels.

Built with Python using Pandas, Scikit-learn, and Matplotlib.

High model accuracy with R² Score: 0.9689.

🧠 ML Model
Algorithm: Random Forest Regressor

Performance:

R² Score: 0.9689

MAE and RMSE evaluated for regression performance

Why Random Forest?

High accuracy and robustness

Handles multivariate and nonlinear data

Provides feature importance insights

📊 Sample Dataset Columns
PM2.5, PM10, NO₂, SO₂, CO, O₃, Temperature, Humidity, Wind Speed, AQI

📁 Project Structure
bash
Copy
Edit
├── data/                # Air quality dataset
├── models/              # Trained model files
├── notebooks/           # Jupyter notebooks
├── src/                 # Source code
├── app/                 # Optional UI or alert module
├── README.md
└── requirements.txt
🚀 How to Run
Clone the repo

Install dependencies:

nginx
Copy
Edit
pip install -r requirements.txt
Run the notebook or Python script to train and test the model.

📬 Alerts
The system can be extended to send alerts via:

Email notifications

Mobile push messages

Dashboard integration
