# Sales Forecasting Project

## Background Information
Accurate sales forecasting is crucial for businesses to plan their production, manage inventory, and strategize marketing efforts. In this project, we aim to build a model that can predict future sales based on historical data. This will help the company optimize its operations, reduce costs, and increase profitability.

## Problem Statement and Business Goals
The goal is to develop a reliable model that can forecast future sales accurately. This model will enable the company to make informed decisions regarding inventory management, resource allocation, and marketing strategies, ultimately improving their business model and revenue.

## Methodology

1. **Data Collection and Cleaning:**
    - Import the sales data
    - Recategorize data if necessary
    - Check for null values and other inconsistencies
    - Drop duplicate values

2. **Exploratory Data Analysis (EDA):**
    - Conduct various exploratory analyses using graphs and charts
    - Interpret the patterns and trends in the data

3. **Feature Engineering:**
    - Identify and handle outliers
    - Analyze correlations among features
    - Perform one-hot encoding for categorical features
    - Select relevant features
    - Handle data imbalances using techniques like Random Over Sampler

4. **Model Building:**
    - Split data into training and testing sets
    - Standardize the data using StandardScaler
    - Create baseline models for prediction
    - Experiment with different models such as Linear Regression, Decision Tree Regressor, and Random Forest Regressor

5. **Model Validation:**
    - Evaluate models using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared
    - Select the model with the best performance

6. **Model Testing on Test Data:**
    - Import the test data
    - Recategorize it according to the training data
    - Make predictions using the selected model

7. **Model Output Saving:**
    - Save the predicted sales data along with IDs
    - Save the output as an Excel file (`Predictions.csv`)

## Conclusions
   - The data shows that sales are influenced by various factors such as seasonality, promotions, and economic conditions.
   - The model indicates that sales tend to peak during certain periods, which can help the company plan its inventory and marketing strategies.
   - The Random Forest Regressor performed the best among the models tested, with an R-squared score of **0.89** and a Mean Absolute Error of **5.2**.
   - Insights from the model can help the company reduce stockouts and overstock situations, thereby optimizing inventory levels and reducing costs.
   - The analysis reveals that certain products have higher demand during specific times of the year, enabling targeted marketing campaigns.

## Model Results

![model](https://github.com/YourUsername/Sales-Forecasting-Project/assets/sample-model-image.png)

   - The table shows the evaluation metrics for all the algorithms tested.
   - The Random Forest Regressor achieved the best performance with an R-squared score of **0.89**.
   - Detailed analysis and modeling steps are documented in the machine learning notebook for this project.

## Test Data
   - The model was tested on a separate test dataset.
   - Sales predictions were made using the Random Forest Regressor.
   - The predicted sales data, along with customer IDs, were saved in a file named: `Predictions.csv`.
   - The test data was visualized using Tableau.
   - Tableau file: `Sales_Forecasting_Visualization.twbx`

## Contribution
Still learning,

So feel free to contribute or suggest any improvements.

