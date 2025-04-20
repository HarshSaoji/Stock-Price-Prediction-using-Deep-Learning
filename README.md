## 📈 Stock Price Prediction using Deep Learning

### 🔍 Project Overview
This project leverages deep learning techniques to predict stock prices based on historical data. We implemented and compared the performance of three different deep learning models: **LSTM**, **GRU**, and **1D CNN** using the historical closing prices of **Apple Inc. (AAPL)**.

---

### 🚀 Models Used
- 🔷 **LSTM (Long Short-Term Memory)**: Captures long-term dependencies in time series data.
- 🔷 **GRU (Gated Recurrent Unit)**: A simplified version of LSTM with fewer parameters.
- 🔷 **1D CNN (Convolutional Neural Network)**: Detects patterns in time series through convolutional filters.

---

### 🧠 Objectives
- Predict future stock prices based on past performance.
- Compare performance of LSTM, GRU, and 1D CNN models.
- Visualize prediction accuracy using real stock data.

---

### 📊 Dataset
- **Source:** [Yahoo Finance](https://finance.yahoo.com/)
- **Stock Symbol:** `AAPL` (Apple Inc.)
- **Date Range:** 2015 - 2023
- Data is fetched directly using the [`yfinance`](https://pypi.org/project/yfinance/) API.

---

### 🛠️ Tech Stack
- Python 3
- TensorFlow / Keras
- yfinance
- NumPy, Pandas, Matplotlib
- Scikit-learn

---

### 📂 Project Structure
```
📁 stock-price-prediction/
├── README.md
├── stock_prediction.ipynb        
└── requirements.txt             
```

---

### 📈 Evaluation Metrics
Each model is evaluated using:
- ✅ Root Mean Squared Error (RMSE)
- ✅ Mean Absolute Error (MAE)
- ✅ R² Score (Coefficient of Determination)
- ✅ Line plots of actual vs. predicted prices

---

### 📷 Visual Output Example 
![lstm](https://github.com/user-attachments/assets/2330bf88-bc0e-4af0-afa3-bdcf02fd5a44)
![gru](https://github.com/user-attachments/assets/dd0502dc-247f-443d-986b-4257c52bc3ce)
![cnn](https://github.com/user-attachments/assets/0adb11e3-2fde-4902-8c1d-c1b72b85076d)


---

### 💡 How to Run
1. Open the `stock_prediction.ipynb` notebook in [Google Colab](https://colab.research.google.com)
2. Run all cells (GPU recommended for faster training)
3. View evaluation metrics and output graphs for each model

---

### ✅ Results Summary

| Model   | RMSE    | MAE     | R² Score |
|---------|---------|---------|----------|
| LSTM    | 8.4697  | 7.1140  | 0.5406   |
| GRU     | 4.7740  | 3.8853  | 0.8540   |
| 1D CNN  | 6.8366  | 5.6529  | 0.7006   |




---

### 📝 License
This project is open source under the MIT License. See the `LICENSE` file for details.

---
