### 🏡 House Price Prediction with XGBoost

This project uses historical real estate data to train a machine learning model that predicts the **median sale price of homes** based on features such as inventory, property type, location, and market conditions.

---

## 📦 Features

* Trained using `XGBoostRegressor`
* Input features include:

  * Property type
  * Parent metro region
  * Inventory
  * Months of supply
  * Period (month)
* Evaluated using:

  * MAE, RMSE, and R²
  * Residual and scatter plots
* Clean preprocessing pipeline with `ColumnTransformer`
* Interactive predictions via `ipywidgets`

---

## 📁 Dataset

* Based on cleaned Redfin/real estate time series data
* Includes features such as:

  * `median_sale_price`, `inventory`, `months_of_supply`, `property_type`, `parent_metro_region`, etc.
* Target variable: `median_sale_price`

---

## ⚙️ Model Performance

| Metric | Score    |
| ------ | -------- |
| MAE    | $42,164.56 |
| RMSE   | $42,164.56 |
| R²     | 0.233    |

✅ Good correlation with actual prices
⚠️ Some underestimation for higher-priced homes
📉 Most errors fall within ±\$100,000

---

## 🧪 How to Run

1. Clone this repo:

2. Install dependencies:

3. Run training script:
 
4. (Optional) Launch Jupyter notebook for interactive prediction:

```bash
jupyter notebook
```

---

## 📊 Visualizations

* 📈 Actual vs. Predicted Price
* 📉 Residuals Distribution
* 🔧 Interactive input widget (via `ipywidgets`)

---

## 🧠 Future Improvements

* Try log-transforming the target variable
* Add more granular location data (city, zip code)
* Use LightGBM or CatBoost
* Deploy with Streamlit or Gradio

---

## 🤝 Credits

Developed by \[Adesiyan Heritage]


