# 🎓 Student Performance Prediction using Machine Learning

## 📝 Overview
This project focuses on predicting student academic performance based on a variety of socio-economic and educational factors. By leveraging **Educational Data Mining (EDM)** techniques, the model identifies key predictors of success, such as study time, previous grades, and family background.

As a **Mathematics Professor**, my approach to this project goes beyond simple code implementation; it emphasizes the **statistical and mathematical foundations** of predictive modeling.

---

## 🔬 Mathematical & Statistical Framework
Unlike standard implementations, this project provides a deep dive into the logic of the algorithms used:

1. **Correlation Analysis ($r$):**
   We use the **Pearson Correlation Coefficient** to measure the linear relationship between variables.
   $$r = \frac{\sum (x_i - \bar{x})(y_i - \bar{y})}{\sqrt{\sum (x_i - \bar{x})^2 \sum (y_i - \bar{y})^2}}$$
   *This ensures we select features with the highest impact on the final grade ($G3$).*

2. **Model Evaluation Metrics:**
   The model's accuracy is evaluated using:
   - **Mean Squared Error (MSE):** To measure the average squared difference between estimated and actual values.
   - **R-squared ($R^2$):** To determine the proportion of variance for the dependent variable that's explained by the independent variables.

3. **Algorithm Logic (Random Forest):**
   The project utilizes an ensemble of Decision Trees to reduce variance. The mathematical focus here is on **Information Gain** and **Gini Impurity**.

---

## 🛠 Tech Stack
- **Language:** Python 3.x
- **Libraries:** - `Pandas` & `NumPy` for data manipulation and matrix operations.
  - `Matplotlib` & `Seaborn` for statistical visualization.
  - `Scikit-learn` for implementing the Random Forest Regressor.

---

## 📂 Project Structure
* `data/`: Contains the Student Performance Dataset (CSV).
* `notebooks/`: Exploratory Data Analysis (EDA) and model training.
* `scripts/`: Production-ready Python scripts.
* `README.md`: Project documentation.

---

## 📊 Key Insights
- **Previous Grades ($G1, G2$):** Showed the strongest positive correlation with the final outcome.
- **Absences:** Found to be a significant negative predictor, requiring a non-linear approach for accuracy.
- **Study Time:** Demonstrated a logarithmic relationship with performance improvement.

---

## 📧 Contact
**Dr. Wael Alhajyounes** *University Professor & AI Researcher* [LinkedIn Profile] | [Email Address]
