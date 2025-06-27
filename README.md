# AI-ML-Engineering-Internship-Tasks-at-DevelopersHub-Corporation

### 🧠 **Summary of All Findings**

These three findings cover different real-world machine learning projects—**Iris classification**, **stock price prediction using LSTM**, and **house price regression**. Despite differing use cases, they follow a common data science workflow:

* **Importing Essential Libraries:** All projects begin by importing libraries like `pandas`, `numpy`, `matplotlib`, `seaborn`, and model-specific libraries such as `sklearn`, `tensorflow.keras`, or `xgboost`.

* **Dataset Loading & Inspection:** Each project loads a dataset (Iris, AAPL stock, house prices) from a CSV or API and uses `.head()`, `.info()`, and `.describe()` for initial inspection.

* **Data Preprocessing & Cleaning:** Common steps include handling missing values, dropping irrelevant columns (like 'Id'), and filling missing data with means. In stock price and house price prediction, scaling with `MinMaxScaler` or `StandardScaler` is also performed.

* **Visualization:** All findings use plots (histograms, box plots, scatter plots, pair plots, and heatmaps) to understand data distributions, feature relationships, and missing values. The stock prediction also uses time-series plots and candlestick charts.

* **Correlation Analysis:** Each case uses correlation matrices or heatmaps to identify strong relationships between features—important for feature selection.

* **Feature Engineering:** For categorical data (e.g., house prices), one-hot encoding is applied. LSTM models use sequence generation from time-series data.

* **Model Building:**

  * *Iris Dataset:* Focus on classification using visual separation between species.
  * *Stock Prices:* LSTM deep learning model with time-step sequences.
  * *House Prices:* Regression models (`LinearRegression`, `RandomForest`, `GradientBoosting`, and `XGBRegressor`).

* **Model Training & Evaluation:** All findings involve training/testing splits and use metrics like **R2 score**, **MAE**, **RMSE**, or **MSE** to assess performance. The LSTM model shows time-series forecasting results and training loss curves.

* **Final Output:** Each project visualizes the actual vs. predicted outputs and summarizes model performance to determine accuracy and reliability.
