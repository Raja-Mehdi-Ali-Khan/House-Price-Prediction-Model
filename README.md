# House Price Prediction using Linear Regression

## Overview
This project predicts house prices based on selected housing features using the California Housing dataset provided by `sklearn`. The model uses **Multiple Linear Regression** and evaluates performance using standard regression metrics. It also includes residual analysis and visualizations to understand the model's behavior.

---

## Files Included

- `house_price_prediction.ipynb`: Jupyter Notebook with full implementation
- `students_data.csv`: CSV dataset (if any custom dataset is used)
- `house_price_model.joblib`: (Optional) Saved trained model
- `summary.pdf`: One-page project summary
- `README.md`: Project documentation

---

## Dataset

**Source:** [California Housing Dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_california_housing.html)  
**Target Variable:** `Price` (in 100,000s USD)  
**Features Used (3):**
- `MedInc`: Median Income
- `AveRooms`: Average number of rooms per household
- `HouseAge`: Median age of the houses

---

## Project Workflow

1. Load dataset and explore basic statistics
2. Select 3 input features and define the target
3. Train-test split using `train_test_split()`
4. Train model using `LinearRegression()`
5. Evaluate using:
   - Mean Squared Error (MSE)
   - R² Score
6. Perform residual analysis with:
   - Histogram of residuals
   - Residuals vs Predicted plot
7. Visualize feature relationships
8. Predict house price from user input
9. (Optional) Save model using `joblib`

---

## How to Run

1. Open `house_price_prediction.ipynb` in Jupyter or Google Colab
2. Run all cells step by step
3. For prediction:
   - Enter values for `MedInc`, `AveRooms`, and `HouseAge` when prompted

---

## Example Metrics

- **Mean Squared Error:** ~0.52
- **R² Score:** ~0.62

_(Values vary slightly on different runs)_

---


## Future Improvements

- Try more features (like `AveOccup`, `Latitude`)
- Use regularization (Ridge/Lasso)
- Try Decision Trees or XGBoost for non-linear models
- Deploy using Flask or Streamlit

---

## Author

**Raja Mehdi Ali Khan**  
B.Tech | National Institute of Technology, Andhra Pradesh

Email: rajghaznavi7@gmail.com

---

