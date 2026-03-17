🌦️ Weather Prediction Expert System

A machine learning-based weather forecasting application that predicts the next 7 days of temperature and precipitation using historical data and provides intelligent weather advice through a rule-based system.

🚀 Features

📍 City-based weather forecasting

📊 Uses historical data from Meteostat

🤖 Machine Learning model (Random Forest)

📅 7-day future predictions

💡 Expert system for weather advice

📈 Graph visualization of forecast vs historical data

🖥️ GUI built with Tkinter

🛠️ Tech Stack

Python

Tkinter

Pandas

Scikit-learn

Matplotlib

Meteostat API

📂 How It Works

User enters a city name

Historical weather data is fetched (past 1 year)

Data is preprocessed and features are created

Random Forest models are trained for:

Temperature (tavg)

Precipitation (prcp)

Future 7-day predictions are generated

Rule-based logic provides weather advice

Results are displayed in GUI and plotted

🧠 Expert System Logic

The system provides advice based on rules like:

High precipitation → Carry an umbrella

High temperature → Heat warning

Low temperature → Cold weather precautions

Moderate temperature → Pleasant weather

📸 Output

Tabular 7-day forecast

Daily weather advice

Temperature trend graph

🔮 Future Improvements

Add more weather features (humidity, wind, pressure)

Use LSTM / time-series models

Expand to more cities using APIs

Deploy as a web app (Flask/Streamlit)

📌 Author

Nausheen Ansari
