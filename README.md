# Grocery Demand Prediction

## Project Overview
This project focuses on forecasting grocery product demand using historical sales data and external factors like promotions, holidays, and economic indicators. The integrated approach combines six datasets to build a robust predictive model. The SARIMA model is used for time-series forecasting, achieving over 92% accuracy, and identifying seasonal and non-seasonal trends.

## Features
- **Demand Forecasting**: Predict future demand for grocery products.
- **Dataset Integration**: Combines sales, store, item, transaction, holiday, and oil price data.
- **Seasonal Analysis**: Captures trends influenced by holidays and promotions.
- **Evaluation Metrics**: Uses RMSE, MAE, and residual analysis to validate predictions.

## Datasets
1. **Sales Data**: Historical sales records with promotions.
2. **Store Data**: Metadata about stores (location, type).
3. **Item Data**: Details of products (categories, perishability).
4. **Transactions Data**: Number of daily transactions.
5. **Oil Prices**: Economic context affecting demand.
6. **Holidays Data**: Influence of holidays on sales patterns.

## Methodology
1. **Data Cleaning and Integration**: Handle missing values, outliers, and merge datasets.
2. **Exploratory Data Analysis (EDA)**: Identify patterns, trends, and key drivers of sales.
3. **Modeling**: Implement SARIMA for time-series forecasting.
4. **Evaluation**: Validate predictions using metrics like MAE and RMSE.

## Results
- Achieved **92% accuracy** in demand prediction.
- Identified key trends, such as seasonal spikes during holidays and weekends.

## Future Work
- Expand modeling to include neural networks (e.g., LSTM) for handling complex relationships.
- Incorporate additional external factors like competing store sales and marketing campaigns.
- Scale predictions for all items and stores.

## How to Use
1. Clone the repository and install dependencies.
2. Place the required datasets in the `data/` folder.
3. Run the notebooks in the following order:
   - `DI.ipynb`: Dataset integration.
   - `EDA.ipynb`: Exploratory data analysis.
   - `DA.ipynb`: Demand prediction model training.
4. Review predictions and visualizations in `results/`.
