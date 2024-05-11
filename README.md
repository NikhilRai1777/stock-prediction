# Stock Price Forecasting Project

## Overview
This project aims to develop a predictive model for forecasting stock prices using Python and machine learning techniques. The model utilizes historical stock data sourced from the Quandl API, focusing on the Google (GOOGL) stock dataset. The primary objective is to predict future stock prices based on past performance, facilitating informed decision-making for investors and financial analysts.

## Features
- Data Retrieval: Fetch historical stock data using Quandl API, focusing on relevant features such as Adjusted Open, High, Low, Close prices, and trading volume.
- Data Preprocessing: Perform data cleaning tasks including handling missing values, feature selection, and normalization to prepare the dataset for analysis.
- Model Development: Utilize machine learning algorithms, specifically Linear Regression, to train the predictive model on the preprocessed dataset.
- Model Evaluation: Assess the accuracy of the model using cross-validation techniques to ensure its reliability and effectiveness in forecasting future stock prices.
- Visualization: Visualize the forecasted stock prices alongside historical data using Matplotlib, providing intuitive insights for stakeholders.

## Dependencies
- Python 3.x
- pandas
- numpy
- scikit-learn
- quandl
- matplotlib

## Usage
1. Clone the repository:
2. Install the required dependencies:
3. 3. Run the `forecast_stock_prices.py` script:
4. View the forecasted stock prices plotted against historical data in the generated graph.

## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests to enhance the functionality of this project.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
