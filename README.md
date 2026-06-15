## Project_Linear_regression
#Sales Revenue Prediction
Project Summary:Project: Sales Revenue Prediction

Dataset: dataspy_inconsistent_sales_data.csv (sales records: Invoice_Date, Product, Region, Quantity, Stock, Revenue, etc.)

Goal: Predict Revenue from Product, Quantity, and Stock.

Approach: Train/test split (80/20). Pipeline with ColumnTransformer: StandardScaler for numeric (Quantity, Stock) and OneHotEncoder for Product; LinearRegression regressor. Visualized actual vs predicted and performed a single-row prediction.

Results: MSE ≈ 1.0e-4, MAE ≈ 0.0088, R² ≈ 0.9999999999 (near-perfect fit).

Notes/Next steps: Verify data leakage or target scaling, add cross-validation, engineer features (region, dates), and test robust models/regularization.
