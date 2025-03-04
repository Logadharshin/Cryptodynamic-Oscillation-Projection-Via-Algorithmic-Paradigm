# Cryptodynamic-Oscillation-Projection-Via-Algorithmic-Paradigm
The Project employs a Long Short-Term Memory (LSTM) neural network to predict bitcoin prices, utilizing data investigation and visualization tools to analyze pricing trends, correlations, and future estimates, thereby improving financial market decision-making by identifying past price trends and producing accurate short-term forecasts.
**Overview**

This project utilizes a Long Short-Term Memory (LSTM) neural network to predict cryptocurrency prices based on historical data. It incorporates data preprocessing, feature engineering, and deep learning techniques to analyze trends, visualize correlations, and forecast future prices.

**Features**

**Data Preprocessing:** Cleans and normalizes cryptocurrency price data.

**Exploratory Data Analysis (EDA):** Visualizes price trends, correlations, moving averages, and statistical distributions.

**LSTM Model Implementation:**Uses a deep learning-based recurrent neural network to capture price patterns.

**Model Training & Evaluation:** Trains the LSTM model and evaluates performance using metrics like MSE, MAE, and R-squared.

**Future Price Prediction:** Forecasts cryptocurrency prices for the next 30 days.
**
Advanced Visualizations: **Includes interactive plots, heatmaps, animated charts, and 3D surface plots for enhanced data interpretation.

**Dataset**

The project uses historical cryptocurrency price data, including:

Columns: Date, Open, High, Low, Close, Volume, Market Cap

**Interval:** 1-hour, 4-hour, or daily price data
**
Cryptocurrency:** Example: Bitcoin (BTC-USD), but adaptable for other coins
**
Technologies Used**

**Programming Language:** Python

**Libraries:**

**pandas, numpy** – Data manipulation and preprocessing

**scikit-learn** – Feature scaling and model evaluation

**tensorflow.keras** – Deep learning model (LSTM)

**seaborn, matplotlib** – Data visualization

**plotly** – Interactive and animated charts

**Installation**

**Clone the repository:**

git clone https://github.com/yourusername/crypto-price-prediction.git
cd crypto-price-prediction

**Install dependencies:**

pip install -r requirements.txt

**Run the script:**

python main.py

**Model Training**

The model is trained on past price data with a sequence length of 60 time steps.

Uses Adam optimizer and Mean Squared Error (MSE) loss function.

Trained over multiple epochs with a batch size of 1.

**Results**
**
Performance Metrics:**

Mean Squared Error (MSE)

Mean Absolute Error (MAE)

R-squared (R²)

**Prediction Visualization:
**
Actual vs. Predicted Prices

Future Price Predictions with Confidence Interval

3D Price Trends and Moving Averages

**Future Enhancements**

Implementing additional technical indicators (e.g., RSI, MACD)

Integrating real-time data streaming for live predictions

Deploying the model using Flask or FastAPI
**
Contributing**

Feel free to fork this repository, create feature branches, and submit pull requests. Any contributions are welcome!

**License**

This project is licensed under the MIT License. See LICENSE for details.

**Author**

Logadharshini

