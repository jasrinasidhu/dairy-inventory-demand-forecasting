# Dairy Inventory Demand Forecasting

AI models for dairy retail: demand forecasting, low-stock prediction and pricing, deployed as a Gradio web app. Group assignment, Sunway University. I led data preprocessing, modelling and coding.

## Results

| Model | Method | Result |
|---|---|---|
| Demand Forecasting | 7-Day Moving Average | MAE 510.2 (training average baseline: 508.1) |
| Low-Stock Classification | Logistic Regression | Accuracy 76.9%, Recall 0.80, AUC 0.85 |
| Pricing Prediction | Linear Regression | R² -0.01 (features did not explain price) |

**Note:** The notebook was revised after submission, so results differ from the report. Demand is now measured as quantity sold, the forecast is compared against simple baselines, and the low-stock model only uses information available before sales. In the original version, stock and sales columns were model inputs, and stock was calculated directly from them, which explained the near-perfect scores.

**Tech:** Python, Scikit-learn, Pandas, Matplotlib, Seaborn, Gradio
