# Week 4 – Predictive Modeling and Optimization in Logistics Systems

This week focuses on applying predictive analytics and machine learning techniques to logistics operations. The objective is to predict shipment delivery time and identify important factors that influence delivery performance.

The project uses Python, Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn to perform data preparation, feature engineering, model development, and evaluation. The same 600-row synthetic logistics dataset used in the previous weeks is used for this analysis.

The target variable, delivery time in hours, is derived from the dispatch and delivery timestamps. The analysis considers features such as planned distance, shipment weight, carrier, service type, region, warehouse, and order date information.

Three machine learning approaches are evaluated: Linear Regression, Random Forest Regression, and a tuned Random Forest model. Model performance is compared using Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared (R²).

The Linear Regression model achieved the best test performance, with an MAE of approximately 1.24 hours, RMSE of 1.67 hours, and R² of 0.451. Feature importance analysis identified planned distance as the most influential model feature.

The project concludes with recommendations for improving delivery-time estimation and logistics planning. Since the dataset is synthetic, the results are intended for learning and demonstration rather than direct real-world operational deployment.
