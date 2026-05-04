
<h1 align="center">Stock Market Predictor Using LSTM (Deep Learning)</h1>

In this repository, I’ve documented a comprehensive time-series forecasting project using **Long Short-Term Memory (LSTM)** networks to predict stock market trends[cite: 6]. This project bridges the gap between deep learning research and practical application by providing an interactive dashboard to visualize market data and model performance, making it an excellent demonstration of skills for data science and financial analyst roles[cite: 6].

**<h3>Project Overview</h3>**

This project leverages historical stock data to train a recurrent neural network capable of identifying patterns in sequential data[cite: 6]. It provides users with a tool to fetch real-time data and generate forecasts for various stock tickers[cite: 6].

**<h3>Key Features:</h3>**

*   **Real-time Data Integration:** Uses the Yahoo Finance (`yfinance`) API to pull up-to-date historical market data[cite: 6].
*   **Technical Analysis Visualization:** Automatically calculates and plots **50-day**, **100-day**, and **200-day Moving Averages (MA)** to help identify trend crossovers[cite: 6].
*   **Deep Learning Forecasts:** Employs a trained LSTM model to predict closing prices based on a sliding window of the previous 100 days of data[cite: 6].
*   **Interactive Dashboard:** A responsive user interface built with Streamlit for seamless stock selection and analysis[cite: 6].

**<h3>Project Architecture</h3>**

**Workflow Breakdown:**

1.  **Data Extraction:** Programmatic retrieval of stock history using `yfinance`[cite: 6].
2.  **Preprocessing:** 
    *   Normalization of data using `MinMaxScaler` (0-1) to optimize neural network training[cite: 6].
    *   Creation of time-step windows (100 days) to capture temporal dependencies[cite: 6].
3.  **Model Training:** Development of a stacked LSTM architecture in TensorFlow/Keras to learn long-term price patterns[cite: 6].
4.  **Deployment:** Integration of the trained model into a Streamlit web application for real-time inference[cite: 6].

**Skills Demonstrated**

*   **Deep Learning:** Proficiency in designing and implementing Recurrent Neural Networks (RNNs) and LSTMs[cite: 6].
*   **Time-Series Analysis:** Handling sequential data, windowing, and trend analysis[cite: 6].
*   **Full-Stack Data Science:** Moving from a Jupyter Notebook research environment to a deployed web application[cite: 6].
*   **Data Visualization:** Creating clear, comparative charts using Matplotlib to evaluate "Original" vs. "Predicted" prices[cite: 6].

**<h3>How to Run This Project</h3>**

**Clone this repository:**

`git clone [https://github.com/yourusername/stock-market-predictor.git](https://github.com/yourusername/stock-market-predictor.git)`

**Install the required Python libraries:**

`pip install numpy pandas yfinance keras tensorflow streamlit matplotlib scikit-learn`[cite: 6]

**Run the application:**

`streamlit run app.py`[cite: 6]

**<h3>Files in the Repository</h3>**

*   **app.py:** The main Streamlit application script for the interactive dashboard[cite: 6].
*   **Stock_Market_Prediction_Model_Creation.ipynb:** Jupyter notebook detailing the EDA, data cleaning, and LSTM training process[cite: 6].
*   **Stock Predictions Model.keras:** The serialized pre-trained LSTM model used for generating forecasts[cite: 6].
*   **README.md:** Project documentation.

**<h3>Key Insights from the Analysis</h3>**

1.  **Model Convergence:** Successfully trained the model to follow general market volatility and trend direction using historical 10-year data[cite: 6].
2.  **Technical Indicator Synergy:** Demonstrated how deep learning predictions can be used alongside traditional Moving Averages to confirm momentum and potential reversals[cite: 6].
3.  **Window Analysis:** Identified that a 100-day historical window provides a significant enough context for the LSTM to minimize mean squared error in short-term forecasts[cite: 6].

**⚠️ Disclaimer**

This tool is for **educational and research purposes only**. Stock trading involves significant financial risk. The predictions provided by this LSTM model should not be interpreted as financial advice. Always consult with a certified financial advisor before making investment decisions[cite: 6].

**Let's Connect**

I'm always interested in discussing deep learning, quantitative finance, and data science. Feel free to reach out with questions or feedback!

**LinkedIn:**https://www.linkedin.com/in/raghunath-panda-78651a242/
