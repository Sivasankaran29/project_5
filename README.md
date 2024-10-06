# Dominos - Predictive Purchase Order System

## Project Overview
This project aims to optimize the ingredient ordering process for Dominos by predicting future sales and generating efficient purchase orders. By leveraging historical sales data and ingredient information, this system ensures that Dominos maintains the right stock levels, minimizing waste and preventing stockouts.

## Skills Acquired
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Time series forecasting
- Predictive modeling
- Business decision-making
- Real-world application of data science

## Domain
Food Service Industry

## Problem Statement
Dominos wants to enhance its ingredient ordering process by accurately forecasting sales. This project leverages historical sales data to develop a predictive model that generates a purchase order system, ensuring optimal ingredient stock levels.

## Business Use Cases
- **Inventory Management:** Ensure optimal stock levels to meet future demand without overstocking.
- **Cost Reduction:** Minimize waste and reduce costs associated with expired or excess inventory.
- **Sales Forecasting:** Accurately predict sales trends to inform business strategies and promotions.
- **Supply Chain Optimization:** Streamline the ordering process to align with predicted sales and avoid disruptions.

## Approach

### 1. Data Preprocessing and Exploration
- **Data Cleaning:** Removed missing or inconsistent data entries, handled outliers, and formatted data appropriately.
- **Exploratory Data Analysis (EDA):** Analyzed sales trends, seasonality, and patterns in historical sales data.

### 2. Sales Prediction
- **Feature Engineering:** Created relevant features from sales data such as day of the week, month, promotional periods, and holiday effects.
- **Model Selection:** Chose appropriate time series forecasting models, including ARIMA, SARIMA, Prophet, LSTM, and Regression Model.
- **Model Training:** Trained predictive models on historical sales data.
- **Model Evaluation:** Used Mean Absolute Percentage Error (MAPE) to evaluate model performance.

### 3. Purchase Order Generation
- **Sales Forecasting:** Predicted pizza sales for the next week using the trained model.
- **Ingredient Calculation:** Calculated required ingredient quantities based on predicted sales and ingredient datasets.
- **Purchase Order Creation:** Generated a detailed purchase order listing the quantities of each ingredient needed.

## Results
- Accurate sales predictions.
- A comprehensive purchase order detailing the required ingredients for the forecasted sales period.

## Technical Tags
- Data Cleaning
- EDA
- Time Series Forecasting
- ARIMA/SARIMA/Prophet/LSTM/Regression Model
- Predictive Modeling
- Inventory Management
- Python
- Pandas
- Scikit-learn
- Matplotlib/Seaborn

## Datasets
- **Sales Dataset:** [Link to Sales Dataset](#)
- **Ingredients Dataset:** [Link to Ingredients Dataset](#)

### Dataset Explanation
- **Sales Data:** Contains historical sales records, including date, pizza type, quantity sold, price, category, and ingredients.
- **Ingredient Data:** Lists ingredient requirements for each pizza type, including pizza type, ingredient, and quantity needed.

## Conclusion
This project demonstrates the ability to accurately predict sales for Dominos, leading to efficient inventory management and cost reductions. By utilizing historical data and predictive modeling techniques, Dominos can optimize its supply chain operations and improve overall business performance.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

