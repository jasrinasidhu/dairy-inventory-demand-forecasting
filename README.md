# Dairy Inventory Demand Forecasting

AI models for dairy retail: demand forecasting, low-stock prediction and pricing, deployed as a Gradio web app. Group assignment, Sunway University. I led data preprocessing, modelling and coding.

## Results

| Model | Method | Result |
|---|---|---|
| Demand Forecasting | 7-Day Moving Average | MAE 843.7 |
| Low-Stock Classification | Logistic Regression | Accuracy 96.5%, Recall 1.00 |
| Pricing Prediction | Linear Regression | R² -0.01 (features did not explain price) |

**Note:** The low-stock label was based on stock and threshold columns that were also model inputs, which explains the near-perfect scores. Next step is to predict future shortages using only current information.

**Tech:** Python, Scikit-learn, Pandas, Matplotlib, Seaborn, Gradio
