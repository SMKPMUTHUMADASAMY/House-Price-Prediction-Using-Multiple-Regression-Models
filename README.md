# House-Price-Prediction-Using-Multiple-Regression-Models

🏠 House Price Prediction Using Multiple Regression Models

This project demonstrates a comprehensive **machine learning pipeline** to predict **house prices** using various regression algorithms. It includes **data preprocessing, exploratory data analysis (EDA), model training, evaluation**, and **visualization**. The best-performing models are saved for reuse using **Pickle**.



 📁 Dataset

* Dataset used: `USA_Housing.csv`
* Key features:

  * Avg. Area Income
  * Avg. Area House Age
  * Avg. Area Number of Rooms
  * Avg. Area Number of Bedrooms
  * Area Population
  * Target: `Price`

---

## 🧠 Machine Learning Models Used

* Linear Regression
* Ridge Regression
* Lasso Regression
* ElasticNet
* Polynomial Regression (degree = 2)
* Random Forest Regressor
* Decision Tree Regressor
* Support Vector Regression (SVR)
* XGBoost Regressor
* K-Nearest Neighbors (KNN)

---

## 📊 Tools and Libraries

* **Python**
* `pandas`, `numpy`, `matplotlib`, `seaborn`, `hvplot`
* `scikit-learn`, `xgboost`
* `pickle` (model saving)

---

## 🧹 Data Preprocessing

* Converted float columns (`Avg. Area Number of Rooms`, `Avg. Area Number of Bedrooms`) to `int`
* Handled missing values and duplicates
* Dropped non-numeric/unnecessary columns like `Address`

---

## 📈 Exploratory Data Analysis (EDA)

* Distribution plots for `Price`
* Pair plots to study relationships between features
* Histograms using `hvplot`
* Scatter plots for actual vs predicted prices

---

## ✅ Model Evaluation Metrics

For each model:

* **MAE** (Mean Absolute Error)
* **MSE** (Mean Squared Error)
* **RMSE** (Root Mean Squared Error)
* **R² Score**

Results are saved to `model_evaluation_results.csv`.

---

## 📌 Visualizations

* Bar plots comparing RMSE and R² across models
* Scatter plots: Actual vs Predicted Price
* Histogram of target variable (Price)
* Polynomial regression curve

---

## 💾 Output

* Trained models saved as `.pkl` files for reuse
* Evaluation metrics saved to `model_evaluation_results.csv`
* Visual reports saved as `.png` images

---




## 🚀 Conclusion

This project illustrates how various regression models perform on housing data, helping in selecting the best fit based on evaluation metrics. It serves as a solid reference for anyone interested in **regression modeling, model comparison, and real estate analytics**.
