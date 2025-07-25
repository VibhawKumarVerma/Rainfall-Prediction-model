# Rainfall-Prediction-model
# 🌧️ Rainfall Prediction using LSTM and Weather Data API

This project predicts rainfall using an LSTM (Long Short-Term Memory) neural network trained on weather data obtained via a weather API. The goal is to use past weather conditions to forecast rainfall accurately over future time periods.

## 📌 Overview

- **Model Type**: LSTM (Deep Learning - Time Series)
- **Data Source**: Weather API (e.g., OpenWeatherMap)
- **Target**: Rainfall (mm or binary prediction: rain/no rain)

## 🧰 Features Used

- Temperature
- Humidity
- Wind Speed
- Atmospheric Pressure
- Rainfall (historical)
- Date & Time

---

## 📦 Installation

### 1. Clone the Repository
git clone https://github.com/yourusername/rainfall-prediction-lstm.git
cd rainfall-prediction-lstm

### 2. Install Dependencies
pip install -r requirements.txt

### 3. Setup Environment Variables
WEATHER_API_KEY=your_api_key_here

## 🚀 Usage
### Train the LSTM Model and Make Predictions.

## 📊 Example Outputs
- Predicted vs Actual Rainfall Graphs
- Training Loss Curves
- Accuracy / RMSE / MAE Metrics

## 📈 Evaluation Metrics
- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² Score (Optional)

## 🔮 Future Improvements
- Deploy model with Flask or Streamlit
- Use ConvLSTM for spatial data
- Extend to drought or flood forecasting
- Integrate satellite or radar data

```bash
