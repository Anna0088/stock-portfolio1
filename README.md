# stock-portfolio1
Gold Price Prediction Using Machine Learning
This project demonstrates how to predict gold prices using a machine learning model called Random Forest Regressor. The goal is to build a model that can accurately forecast future gold prices based on historical data and various economic indicators.

Data
The project utilizes a dataset containing historical gold prices and other relevant features such as:

SPX: Standard & Poor's 500 stock market index
SLV: iShares Silver Trust ETF prices
USO: United States Oil Fund ETF prices
EUR/USD: Euro to US Dollar exchange rate
Methodology
Data Preprocessing: The dataset is loaded, cleaned, and explored to understand its characteristics. Missing values are checked, and statistical measures are calculated.

Correlation Analysis: The correlation between different features and the gold price (GLD) is analyzed to identify potential predictors. A heatmap visualizes the correlation matrix.

Feature and Target Split: The dataset is split into features (X) and the target variable (gold price - Y).

Train-Test Split: The data is further divided into training and testing sets to evaluate the model's performance on unseen data.

Model Training: A Random Forest Regressor model is trained on the training data to learn the relationship between features and gold prices.

Model Evaluation: The trained model is used to predict gold prices on the test data. The R-squared error is calculated to measure the model's accuracy.

Visualization: A plot compares the actual gold prices with the predicted prices to visualize the model's performance.

Conclusion
This project provides a basic framework for gold price prediction using machine learning. The Random Forest Regressor model demonstrates promising results, and further improvements can be achieved through feature engineering, hyperparameter tuning, and exploring other advanced machine learning techniques.
