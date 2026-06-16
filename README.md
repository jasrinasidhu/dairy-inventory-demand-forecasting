# Dairy Inventory Demand Forecasting

A unified AI framework for enhancing dairy retail operations through demand forecasting, low-stock prediction, and dynamic pricing — addressing the unique challenges of perishable, short shelf-life products.

Completed as a group assignment for Master of Business Analytics at Sunway University. I was responsible for data preprocessing, model development, and coding.

## Three Models Built

| Model | Purpose | Method |
|---|---|---|
| Demand Forecasting | Identify demand trends and support production planning | 7-Day Moving Average |
| Low-Stock Classification | Predict items at risk of shortage | Logistic Regression |
| Pricing Prediction | Estimate optimal price per unit | Linear Regression |

## Key Results
- Low-stock classifier achieved high recall with ROC-AUC close to 1 — minimal false negatives
- Pricing model predictions closely aligned with actual values (strong MAE, RMSE, R²)
- Deployed as an interactive **Gradio web app** for real-time stock risk, pricing, and demand predictions

## Tech Stack
Python, Scikit-learn, Pandas, Matplotlib, Seaborn, Gradio

## Files
| File | Description |
|---|---|
| `ai_and_decision_making_assignment.ipynb` | Full notebook (data prep, modelling, deployment) |
| `dairy_dataset.csv` | Dataset used |
