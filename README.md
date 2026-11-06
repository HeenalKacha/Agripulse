# 🌾 AgriPulse AI – 14-Day Price Volatility Forecasting

An AI-powered agricultural market intelligence platform designed to forecast short-term price volatility in Tur Dal (Pigeon Pea) using market and weather-related indicators.

AgriPulse AI helps users understand potential price fluctuations, assess market risk and make more informed agricultural market decisions through data-driven forecasting.

## 🚀 Project Overview

Agricultural commodity prices are influenced by several factors, including mandi arrivals, rainfall patterns, seasonal variations and market demand.

AgriPulse AI combines historical market information and environmental indicators to generate a 14-day price volatility forecast and classify the expected market risk.

## ✨ Key Features

- **14-Day Forecasting:** Predicts expected price volatility over the next 14 days.
- **AI/ML Forecasting Engine:** Uses a trained CatBoost-based model for volatility prediction.
- **Risk Classification:** Categorizes market conditions into Low, Moderate, High and Very High risk.
- **Market Indicators:** Incorporates spot price, daily mandi arrivals, rainfall and monsoon deficit.
- **Interactive Dashboard:** Visualizes predicted volatility, market risk and forecast trends.
- **Custom Scenario Inputs:** Allows users to experiment with different market conditions.
- **Market Selection:** Supports the Mumbai APMC market context.
- **Multilingual Interface:** Includes language selection for a more accessible experience.

## 🧠 How It Works

1. **Data Input:** Market and weather-related indicators are provided to the forecasting engine.
2. **Data Processing:** Input values are processed for model prediction.
3. **Model Inference:** The trained machine learning model generates a volatility forecast.
4. **Risk Assessment:** Predicted volatility is mapped to a corresponding risk category.
5. **Visualization:** Results are presented through an interactive dashboard.

## 🛠️ Technology Stack

| Category | Technologies |
|---|---|
| Frontend | React, TypeScript |
| Build Tool | Vite |
| Backend | Python, Node.js |
| Machine Learning | CatBoost |
| Data Processing | Python |
| Data Format | CSV, JSON |
| Version Control | Git, GitHub |

## 📊 Forecasting Inputs

| Parameter | Description |
|---|---|
| Modal Spot Price | Current commodity price (₹/qt) |
| Daily Mandi Arrivals | Quantity arriving in the market |
| 7-Day Rainfall Sum | Recent rainfall measurement |
| Monsoon Deficit | Rainfall deviation from normal |

## 📁 Project Structure

```text
Agripulse/
│
├── backend/
│   └── ml_engine/
│       ├── predict.py
│       ├── generate_data.py
│       ├── train_pipeline.py
│       └── CatBoost model files
│
├── public/
├── src/
│   ├── components/
│   └── App.tsx
│
├── .env.example
├── .gitignore
├── index.html
├── package.json
├── server.ts
├── tsconfig.json
├── vercel.json
└── vite.config.ts
```

## ⚙️ Installation & Setup

### Prerequisites

- Node.js
- npm
- Python 3
- Git

### 1. Clone the repository

```bash
git clone https://github.com/HeenalKacha/Agripulse.git
```

### 2. Navigate to the project

```bash
cd Agripulse
```

### 3. Install dependencies

```bash
npm install
```

### 4. Configure environment variables

Create your local `.env` file using `.env.example` as a reference. Add the required configuration values.

### 5. Start the application

```bash
npm run dev
```

*Note: Configure the Python backend dependencies and start command according to the project's backend requirements.*

## 🎯 Project Objective

The primary objective of AgriPulse AI is to explore how machine learning can support agricultural market intelligence by identifying potential price volatility and providing understandable risk insights.

## 🔮 Future Enhancements

- Expand forecasting to multiple agricultural commodities.
- Integrate real-time mandi price and weather APIs.
- Support additional agricultural markets across India.
- Improve forecasting through continuous model evaluation.
- Introduce historical forecast accuracy analysis.
- Develop personalized market alerts.

## ⚠️ Disclaimer

AgriPulse AI is an academic and experimental forecasting project. Predictions are estimates based on available data and model assumptions. They should not be treated as guaranteed market outcomes or financial advice.

## 👩‍💻 Developer

**Heenal Kacha**

GitHub: [@HeenalKacha](https://github.com/HeenalKacha)

---

⭐ If you find this project interesting, consider giving the repository a star!
