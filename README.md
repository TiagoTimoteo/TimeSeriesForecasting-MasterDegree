#  Time Series Forecasting in the Dairy Sector

This project was developed as part of the **Time Series Analysis and Forecasting** course in the Master’s in Data Science. It aims to analyze and forecast milk prices for consumers and producers using classical statistical models, deep learning, and hybrid approaches.

---

##  Objective

To model and forecast two real-world time series related to the dairy market:

- Average milk price for **consumers**
- Milk manufacturing price for **producers**

We explore patterns such as trend, seasonality, and noise, applying a range of techniques from ARIMA and Exponential Smoothing to Deep Neural Networks and hybrid modeling.

---

##  Datasets

The following time series were used:

- `data_avg_milk_price_consumer.csv`
- `data_milk_manufacturing_price_producer.csv`

Each series reflects different dynamics of the dairy market in Portugal.

---

##  Project Structure

```bash
Time-Series-Forecasting-Dairy-Prices/
│
├── Relatorio_Final.pdf               # Full project report (in Portuguese)
├── data/                             # Source time series
│   ├── data_avg_milk_price_consumer.csv
│   └── data_milk_manufacturing_price_producer.csv
│
├── EDA_Objetivo1/                    # Exploratory Data Analysis
│   ├── EDA_avg_milk_price_consumer.ipynb
│   └── EDA_milk_manufacturing_price_producer.ipynb
│
├── Modelos Classicos_Objetivo2/      # Classical forecasting models
│   ├── *_ARIMA.ipynb
│   └── *_ES.ipynb
│
├── Modelo DNN_Objetivo2/             # Deep learning models
│   ├── *_DDN.ipynb
│
├── Modelo Hibrido_Objetivo3/         # Hybrid and advanced modeling
│   ├── *_ModeloHibrido.ipynb

