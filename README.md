# Feature-engineering
This project focuses on analyzing and forecasting web traffic trends using the Web Traffic Time Series Forecasting Dataset
 from Kaggle.
It applies time-series analysis, data preprocessing, and forecasting models to predict future page views of Wikipedia articles.

📊 Dataset Overview
Source: Kaggle – Web Traffic Time Series Forecasting
Description: Daily page view data for over 145,000 Wikipedia articles.
Goal: Predict the number of visits for each page based on historical data.

⚙️ Technologies Used
Python 3
Pandas, NumPy – for data preprocessing
Matplotlib, Seaborn – for visualization
Scikit-learn, Statsmodels, Prophet, LSTM (Keras/TensorFlow) – for forecasting
Jupyter Notebook / Google Colab – for experimentation

⚙️ Feature Engineering Steps

Data Loading and Exploration
Loaded the dataset using pandas
Checked for missing values, data types, and overall shape
Visualized sample time-series trends
Handling Missing Values
Missing page views were replaced using forward-fill and mean imputation to preserve temporal consistency.
Encoding Categorical Features
Converted text attributes like Project, Access, and Agent into numerical form using Label Encoding and One-Hot Encoding.
Feature Scaling
Applied StandardScaler to normalize numerical features (Views, etc.) for balanced learning behavior.
Feature Extraction / Dimensionality Reduction
Applied PCA (Principal Component Analysis) to reduce redundancy and improve interpretability of time-based features.
Feature Selection
Used correlation analysis and variance thresholding to retain only the most informative features for forecasting.

🧩 Project Workflow
Data Collection – Downloaded from Kaggle
Data Cleaning – Handling missing values and duplicates
Exploratory Data Analysis (EDA) – Visualizing trends and seasonality
Feature Engineering – Creating time-based features
Model Training – ARIMA / Prophet / LSTM
Forecasting – Predicting future page views
Evaluation – RMSE, MAE metrics for performance comparison

📈 Conclusion
The dataset reveals strong seasonal and weekly patterns in page views.
Forecasting models help predict future trends, enabling better content planning, server optimization, and traffic management for web platforms.

👤 Author
ASHIS KUMAR lENKA
📧202401110068@mitaoe.ac.in

