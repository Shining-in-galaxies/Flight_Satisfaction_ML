# ✈️ **Flight Price Prediction using Machine Learning**

## 📚 **Overview**

This project focuses on analyzing airline flight data to predict flight ticket prices using advanced machine learning techniques. By identifying key factors influencing flight prices, the project aims to provide actionable insights for both airlines and customers, enabling better decision-making and resource optimization.

---

## 📊 **Dataset**

- **Source:** [Kaggle - Flight Price Prediction](https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction)
- **Dataset Description:** The dataset includes flight details, customer demographics, service ratings, and key factors like flight duration, number of stops, and days left before departure.
- **Structure:** Tabular format with rows representing individual flights and columns capturing flight-specific features.

---

## 🛠️ **Methodology**

### 1️⃣ **Data Exploration & Preprocessing**

- Conducted an initial inspection with `head()`, `info()`, and `describe()` to understand the dataset.
- **Data Cleaning:**
  - Addressed missing values through imputation and removal of excessive null records.
  - Removed duplicate entries to maintain data integrity.
- **Data Transformation:**
  - Standardized categorical variables (e.g., airline names).
  - Converted data types for consistency and usability.

### 2️⃣ **Feature Engineering**

- Identified key features with the most significant influence on flight prices, such as:
  - Flight Duration
  - Number of Stops
  - Days Left Before Departure

### 3️⃣ **Model Selection & Training**

We selected three powerful regression models:

- **Random Forest:** Reduces overfitting and captures complex feature interactions effectively.
- **XGBoost:** Efficient and powerful, especially for datasets with missing values.
- **Gradient Boosting:** Builds strong predictive power by iteratively minimizing residual errors.

### 4️⃣ **Model Tuning**

- **Economy Class:** Used **Random Search** for hyperparameter optimization.
- **Business Class:** Applied **Grid Search** for fine-tuning model performance.

### 5️⃣ **Evaluation Metrics**

We evaluated model performance using the following metrics:

- **R² (Coefficient of Determination)**
- **MAE (Mean Absolute Error)**
- **MSE (Mean Squared Error)**
- **RMSE (Root Mean Squared Error)**

These metrics provided a comprehensive understanding of model accuracy and prediction errors.

---

## 🧠 **Key Findings**

After thorough analysis and optimization, the following insights emerged:

1. **Flight Duration** significantly impacts ticket pricing.
2. **Number of Stops** is directly correlated with price variations.
3. **Days Left Until Departure** play a critical role in determining ticket costs.

Among the three models, **Random Forest** consistently outperformed others, delivering the most accurate predictions.

---

## 🚀 **Results & Insights**

- The optimized **Random Forest model** displayed high predictive accuracy and reliability.
- The model can effectively assist airlines in setting dynamic pricing strategies.
- Customers can leverage these insights to optimize their travel booking times.

---

## 📎 **Project Resources**

- 📝 [Presentation Slides](https://drive.google.com/file/d/1S4mcjBMpmoYHrt_TZQvB2QF0gEfO5WMG/view?usp=drive_link)

---

## 📝 **Conclusion**

This project successfully demonstrated the power of machine learning in predicting flight prices. By leveraging data-driven insights, the model provides valuable support for optimizing airline operations and enhancing customer decision-making. Future enhancements could include real-time price prediction and integration with airline booking platforms.

✈️ _Thank you for exploring my project! Feel free to contribute, suggest improvements, or raise issues on our GitHub repository._ 🚀
