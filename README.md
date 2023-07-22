# Stock Price Prediction

Stock (also known as equity) is a security that represents the ownership of a fraction of a corporation. This entitles the owner of the stock to a proportion of the corporation's assets and profits equal to how much stock they own. Units of stock are called "shares." A stock is a general term used to describe the ownership certificates of any company. Stock prices change everyday by market forces. By this we mean that share prices change because of supply and demand. If more people want to buy a stock (demand) than sell it (supply), then the price moves up. Conversely, if more people wanted to sell a stock than buy it, there would be greater supply than demand, and the price would fall. Understanding supply and demand is easy. So, why do stock prices change? The best answer is that nobody really knows for sure. Some believe that it isn't possible to predict how stocks will change in price while others think that by drawing charts and looking at past price movements, you can determine when to buy and sell.


![stock_icon](https://github.com/saisanthoshbussa/StockPrice-Prediction/assets/118352633/ee4c7956-a231-4f33-873f-926a6d8e02e2)

Welcome to the Stock Price Prediction Model! This helps to develop an accurate and reliable model for forecasting stock prices. By employing historical data and extracting relevant features, the model can provide valuable insights to investors, aiding in making informed investment decisions in the dynamic and ever-changing stock market.

## Table of Contents

- [Implementation](#implementation)
- [Technologies Used](#technologies-used)
- [Analytical Web Application](#analytical-web-application)
- [Setup](#setup)
- [Performance Evaluation](#performance-evaluation)

## Implementation

1.Using Sckiit Learning( Machine Learning model)

2.Data Preprocessing using dataset

3.Visualization of Dataset

4.Feature Scaling

5.Preparing the Datasets for training

6.Reshaping the datasets

7.Model development

8.Implementation of sequential, dense, LSTM and dropout.

9.Preprocessing the Data

10.Predicting the Output

11.Result visualization

## Technologies Used

- sklearn MinMaxScaler: A preprocessing tool from the scikit-learn library that scales features to a specified range (e.g., between 0 and 1) to improve model performance.
- Keras: A high-level neural network API that simplifies the process of building and training deep learning models, utilizing the powerful capabilities of TensorFlow as the backend.
- NumPy: A fundamental library for numerical computing in Python, providing support for large, multi-dimensional arrays and a collection of mathematical functions to manipulate the data.
- Pandas: A data manipulation and analysis library that offers powerful data structures (e.g., DataFrame) and tools for cleaning, transforming, and exploring structured data.
- HTML: A standard markup language for creating web pages, used to structure the content and layout of the project's web-based user interfaces.
- dcc from Dash: The dash-core-components library from Plotly Dash, which provides interactive UI components for creating data visualization and analytical web applications.

## Analytical Web Application

An analytical web application is built using Plotly Dash to visualize the predicted stock price and analyze the closing and opening stock prices and total market volume of different companies. The web application includes features such as 1-month and 6-month range selectors and range sliders for interactive exploration of stock price data.

![newspp](https://github.com/saisanthoshbussa/StockPrice-Prediction/assets/118352633/6bd3f78b-a3fa-4e25-9bcc-19a9246af1a3)


![spp2](https://github.com/saisanthoshbussa/StockPrice-Prediction/assets/118352633/b4b29114-3a8a-4d53-b730-acc11f501676)


## Setup

1. Clone the repository:

```bash
    git clone https://github.com/saisanthoshbussa/StockPrice-Prediction
```

2. Install the required dependencies: NumPy, Pandas, Keras, sklearn and dash.

3. To run the web application:
   `python app.py` and open the web application in your web browser at specified address.

## Performance Evaluation

The performance of the prediction model is evaluated using the Mean Squared Error (MSE) evaluation metric. The lower the MSE value, the better the prediction accuracy. The MSE value is calculated by comparing the predicted closing stock prices with the actual closing stock prices from the test dataset.
