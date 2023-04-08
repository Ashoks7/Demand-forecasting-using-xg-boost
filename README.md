# Demand-forecasting-using-xg-boost
demand Forecasting with Streamlit
This is a Python script for time series forecasting using Streamlit, a popular Python library for building interactive web applications. The script utilizes various time series forecasting techniques, such as Exponential Smoothing, ARIMA, SARIMA, and XGBoost, to predict the rolling sum of sales for different items.

Dependencies
Make sure you have the following libraries installed in your Python environment:

matplotlib
pandas
numpy
seaborn
statsmodels
sklearn
xgboost
streamlit
plotly
You can install these libraries using pip or conda, for example:

sh
Copy code
pip install matplotlib pandas numpy seaborn statsmodels sklearn xgboost streamlit plotly
How to Run
Clone the repository to your local machine.
Navigate to the directory where the script is located.
Open the terminal and run the following command:

The Streamlit web application will start running on your local machine.
Open a web browser and go to the URL http://localhost:8501 to access the Streamlit app.
Use the input fields in the app to specify the start date, item, and rolling window size for the time series forecasting.
Click the "Forecast" button to generate the forecasted rolling sum of sales.
The forecasted results will be displayed in a plot on the web app.
File Descriptions
train 2.csv: The dataset used for training the time series models, containing historical sales data for different items.
README.md: The documentation file that provides information about how to run the script and use the Streamlit app.
Contributing
If you would like to contribute to this project, please open an issue or submit a pull request. Any feedback, suggestions, or improvements are welcome!

License
This project is licensed under the MIT License. See the LICENSE file for more information.
