## 📈 Netflix Stock Price Prediction using Linear Regression

This project explores and models Netflix stock price data using linear regression. It focuses on predicting the **Open** and **Close** prices based on date-derived features such as year, month, day, and day of the week.

---


### 🔍 Exploratory Data Analysis

- Checked for null values and data types
- Extracted new features from the `Date` column
- Visualized Open vs. Close prices over time using Matplotlib

---

### 🧠 Model

- **Model Used**: Linear Regression (`sklearn.linear_model`)
- **Features**:
  - `year`, `month`, `day`, `day_of_week`
  - `High`, `Low`, `Volume`
- **Target**: `Open`, `Close` (multi-output regression)
- **Scaler**: MinMaxScaler for input feature normalization
- **Data Split**: 80% training, 20% testing

---

### 📊 Performance Metrics

Evaluated using:

- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **R² Score**

> Example output:
> ```
> MAE: ~3.47  
> MSE: ~20.73  
> R² Score: ~0.9983
> ```

---


### 🚀 Future Improvements

- Use more advanced models like LSTM or Random Forest
- Incorporate sentiment analysis from news sources
- Forecast future prices using time series methods (e.g., ARIMA)

---


