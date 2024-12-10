# Wallmart-Sales-prediction-using-ARIMA-Model

📋 Project Overview
This project analyzes and forecasts weekly sales for Walmart stores. The primary objective is to understand the key factors influencing sales, identify trends, and build predictive models to enhance business decision-making. The dataset includes features such as holiday indicators, temperature, fuel prices, CPI, and unemployment rates.

🗂️ Dataset Description
The dataset contains the following variables:

Store: Store ID.
Weekly_Sales: Weekly sales revenue for the store.
Holiday_Flag: Indicates whether the week includes a holiday (1 = Yes, 0 = No).
Temperature: Average temperature for the week.
Fuel_Price: Average fuel price for the week.
CPI (Consumer Price Index): Measure of inflation.
Unemployment: Unemployment rate for the region.

Key Insights from Dataset
Holidays marginally impact weekly sales.
Temperature and fuel prices show weak linear relationships with sales.
CPI and unemployment have minor negative effects on weekly sales.
Store-specific trends suggest the need for customized models.

🎯 Goals
Identify Influential Factors: Analyze relationships between features and weekly sales.
Predict Sales: Build models to forecast sales based on historical data.
Actionable Insights: Provide recommendations for business strategy optimization.

🛠️ Methods and Tools
Data Analysis
Exploratory Data Analysis (EDA):
Correlation analysis using a heatmap.
Scatter plots and box plots to visualize trends.

Modeling
Linear Regression:
Quantified the impact of variables like temperature, unemployment, and CPI.

ARIMA:
Forecasted future weekly sales using time series analysis.

Tools Used
Python Libraries: pandas, numpy, matplotlib, seaborn, sklearn, statsmodels.
Visualization: Correlation heatmaps, feature importance charts, and ACF/PACF plots.

📊 Results
Correlation Analysis:
Weak correlations between Weekly_Sales and most variables, indicating minimal linear relationships.
Moderate negative correlation between Store and Weekly_Sales, suggesting store-specific trends.
Modeling Insights:
Random Forest revealed Holiday_Flag and Temperature as moderately influential factors.
ARIMA produced accurate forecasts for weekly sales trends.

🚀 How to Run
Requirements
Python 3.7+
Install dependencies using:
bash
Copy code
pip install -r requirements.txt

Steps
Clone the repository:
bash
Copy code
git clone https://github.com/paridhomane/walmart-sales-analysis.git
cd walmart-sales-analysis
Run the Jupyter Notebook:
bash
Copy code
jupyter notebook
Explore visualizations and modeling outputs.

File Structure
plaintext
Copy code
├── data/
│   ├── walmart_sales.csv      # Raw dataset
│   ├── processed_data.csv     # Preprocessed data
├── notebooks/
│   ├── EDA.ipynb              # Exploratory data analysis
│   ├── modeling.ipynb         # Regression and forecasting
├── outputs/
│   ├── visuals/               # Saved charts and plots
│   ├── forecasts.csv          # Predicted sales
├── README.md                  # Project documentation
├── requirements.txt           # Python dependencies

📈 Future Scope
Integrate additional features (e.g., regional demographics, promotions) for better predictions.
Explore deep learning models like LSTMs for improved forecasting.
Analyze sales trends at a finer granularity (e.g., daily data).

🤝 Contributing
Contributions are welcome! Please fork the repository and submit a pull request with a detailed description of your changes.

📧 Contact
For questions or suggestions, feel free to reach out:

Email: prashansa.dhomaneofficial@gmail.com

LinkedIn: https://www.linkedin.com/in/prashansadhomane/

Portfolio:https://tinyurl.com/prash-portfolio

