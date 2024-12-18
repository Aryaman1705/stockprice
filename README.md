# **Stock Price Predictor**

This repository provides a machine learning solution for **stock price prediction** using historical financial data. The goal is to forecast future stock prices based on historical trends using time series models such as ARIMA and statistical analysis.

---

##  **Overview**  
The financial market is highly dynamic and impacted by various economic and external factors. Early and accurate stock price predictions can help investors make better financial decisions. This project leverages **machine learning algorithms** and **time series models** to analyze historical data and predict stock price movements with high accuracy. It demonstrates a complete pipeline for preprocessing, training, testing, and evaluating time series models.

---

##  **Features**  

- **Dataset**:  
   Historical stock price data collected from **Yahoo Finance**.

- **Algorithms Implemented**:  
   - ARIMA (Auto-Regressive Integrated Moving Average)  
   - ARMA (Auto-Regressive Moving Average)  
   - Linear and Quadratic Trend Models  

- **Data Preprocessing**:  
   - Handles non-constant variance using logarithmic transformations.  
   - Splits datasets into training and testing sets.  

- **Visualization**:  
   - **Heatmaps** to analyze correlations.  
   - **Time Series Plots** for predicted vs actual stock prices.  
   - **ACF** and **PACF** plots for temporal dependency analysis.

---

##  **Installation**  

### Prerequisites  
Make sure you have **Python 3.7+** installed along with the following libraries:  

- pandas  
- numpy  
- matplotlib  
- statsmodels  
- scikit-learn  

You can install the dependencies using the following command:  
```bash
pip install -r requirements.txt
```

---


## Clone the Repository  
Clone this repository to your local machine:  

```bash
git clone https://github.com/yourusername/Stock-Price-Predictor.git
cd Stock-Price-Predictor
```

---



##  **Results**  
Model evaluation metrics such as **Mean Squared Error (MSE)** and information criteria (**AIC/BIC**) are displayed in the console.  
Visualizations of time series predictions, autocorrelation graphs, and model performance plots are saved or displayed.  

---

##  **Project Structure**  
```plaintext
Stock-Price-Predictor/
├── stock-data.csv           # Dataset
├── stock_prediction.ipynb   # Jupyter Notebook / Google Colab file
├── requirements.txt         # Required dependencies
├── README.md                # Documentation
└── LICENSE                  # Project License
```

---


##  **License**  
This project is licensed under the **GNU General Public License v3.0**. See the [LICENSE](https://github.com/Aryaman1705/Stock-Price-Predictor?tab=GPL-3.0-1-ov-file) file for details.  

---

##  **Acknowledgments**  
- **Yahoo Finance** for providing stock price datasets.  
- **Statsmodels** and **Scikit-learn** libraries for model implementation and evaluation.  



