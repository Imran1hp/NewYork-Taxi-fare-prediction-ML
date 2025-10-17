# 🚕 New York Taxi Fare Prediction
📖 Overview

This project predicts the fare amount of New York City taxi rides 🗽 using data such as pickup and dropoff locations, passenger count, and time of day.
It applies machine learning regression techniques to estimate prices accurately and understand key factors influencing taxi fares 💰.

⚙️ Project Workflow

🧹 Data Preprocessing — Handle missing data, clean coordinates, and remove outliers.

🌍 Feature Engineering — Extract distance, time features (hour, day, month), and use haversine formula for trip length.

🔍 EDA (Exploratory Data Analysis) — Visualize data patterns and fare distribution.

🧠 Model Training — Use algorithms like Linear Regression, Random Forest, and XGBoost.

📊 Evaluation — Compare model performance using RMSE, MAE, and R² metrics.

🚀 Prediction — Generate predictions for unseen test data.

🧰 Tech Stack
Category	Tools / Libraries
🧮 Data Handling	pandas, numpy
📊 Visualization	matplotlib, seaborn
🤖 Machine Learning	scikit-learn, XGBoost
🧾 Notebook	Jupyter Notebook
📍 Geospatial	haversine, geopy
📂 Project Structure
📁 NewYork-Taxi-fare-prediction-ML-main
│
├── 📓 NewYork_Taxi_Fare_Prediction.ipynb   → Main notebook  
├── 📘 README.md                             → Project documentation  
└── 📂 data/ (optional)                      → Dataset folder if included

🚀 How to Run

Clone this repository:

git clone https://github.com/your-username/NewYork-Taxi-fare-prediction-ML.git
cd NewYork-Taxi-fare-prediction-ML-main


Install dependencies:

pip install -r requirements.txt


Launch Jupyter Notebook:

jupyter notebook NewYork_Taxi_Fare_Prediction.ipynb


Run all cells to view preprocessing, analysis, and model results 🧠

📈 Results

✅ Built a robust regression model for fare prediction.
✅ Discovered that distance and trip duration are the most important factors.
✅ Achieved strong performance metrics with XGBoost and Random Forest.

🌟 Future Improvements

🌦️ Include weather and traffic data for better predictions.

🧠 Use deep learning models like LSTM or CNN for time-series data.

📊 Deploy as a web app using Flask or Streamlit for live fare prediction.

👨‍💻 Author

Ali Imran
📍 Netaji Subhash Engineering College
💬 Passionate about Data Science, Machine Learning, and Predictive Modeling
