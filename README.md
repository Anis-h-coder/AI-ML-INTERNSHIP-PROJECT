# AI-ML-INTERNSHIP-PROJECT

Titanic Survival Prediction – Data Cleaning & Logistic Regression

This project demonstrates a complete machine learning pipeline on the Titanic dataset — from data cleaning and preprocessing to model training and evaluation using **Logistic Regression**.

---

Dataset

The Titanic dataset is a classic binary classification dataset. You can download it from:

* [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)

---

Project Goals

* Clean raw Titanic data
* Handle missing values and outliers
* Encode categorical features
* Normalize numerical features
* Train a logistic regression model
* Visualize data distributions and relationships
* Evaluate model performance

---

Tools & Libraries Used

* Python 3.x
* Pandas
* NumPy
* Seaborn
* Matplotlib
* Scikit-learn

---

Data Preprocessing Steps

1. Missing Value Handling

   * `Age`: Filled with median
   * `Embarked`: Filled with mode
   * `Cabin`: Dropped due to too many nulls

2. Categorical Encoding

   * `Sex`: Label encoding (male → 0, female → 1)
   * `Embarked`: One-hot encoding (`Embarked_Q`, `Embarked_S`)

3. Feature Scaling

   * Standardized `Age` and `Fare` using `StandardScaler`

4. Outlier Removal

   * Applied IQR method on `Age` and `Fare`

---

Visualizations Included

* Missing Values Heatmap
* Count of Survivors
* Correlation Heatmap
* Boxplots for Outliers
* (Optional) Pairplot for multi-feature relationships

---

Model Training

* Algorithm: Logistic Regression
* Evaluation:

  * Accuracy
  * Confusion Matrix
  * Classification Report (Precision, Recall, F1)

Results

The logistic regression model achieved good accuracy with well-preprocessed data, showing how basic data science techniques can significantly improve model performance.

 Future Work

* Try advanced models like Random Forest or XGBoost
* Add cross-validation
* Hyperparameter tuning
* Use more features like family size or title extraction from names

---
