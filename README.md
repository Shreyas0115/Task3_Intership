## 📌 Task 3: Linear Regression

# 🏠 Linear Regression with Housing Dataset

This project implements and explores **Simple and Multiple Linear Regression** using the `Housing.csv` dataset. It includes data preprocessing, model training, evaluation, and visualization using Python and key machine learning libraries like Scikit-learn, Pandas, and Matplotlib.

---

## 📚 What I Learned

### 📊 1. Understanding Linear Regression
- **Simple Linear Regression** uses one independent variable to predict a dependent variable.
- **Multiple Linear Regression** uses multiple independent variables.
- Learned how to interpret the coefficients and their impact on the target variable (house price).

### 🧹 2. Data Preprocessing
- Handled categorical variables using label encoding and one-hot encoding.
- Checked for null values and performed data cleaning where needed.

### 🔀 3. Train-Test Splitting
- Used `train_test_split` to divide the dataset into training and testing sets to evaluate model performance.

### 🧠 4. Model Building with Scikit-learn
- Trained a **LinearRegression** model from `sklearn.linear_model`.
- Fit the model and made predictions on the test set.

### 📈 5. Model Evaluation Metrics
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **R² Score (Coefficient of Determination)**

These metrics helped assess the model's accuracy and effectiveness in predicting house prices.

### 🖼️ 6. Visualization
- Plotted regression lines to understand the model’s fit.
- Visualized the relationship between features (like area) and the target variable.

---

## 💬 Interview Insights

| Question | Key Learning |
|---------|---------------|
| **Assumptions of Linear Regression** | Linearity, Independence, Homoscedasticity, No Multicollinearity, Normality of Errors |
| **R² Score** | Measures how well the independent variables explain the variability of the dependent variable |
| **MAE vs MSE** | MAE is robust to outliers; MSE penalizes large errors more |
| **Multicollinearity Detection** | Checked using correlation matrix and VIF (Variance Inflation Factor) |
| **Simple vs Multiple Regression** | Single vs multiple predictors |
| **Use of Linear Regression for Classification** | Not suitable – prefer logistic regression |
| **Effect of Violating Assumptions** | Can lead to misleading or biased results |

---

## 🔧 Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib & Seaborn
- Scikit-learn

---

## 📁 Dataset
**Housing.csv** – Contains information about house attributes (area, number of bedrooms, bathrooms, etc.) and target variable (price).

---

## 🚀 Next Steps
- Try **Polynomial Regression** for non-linear relationships.
- Apply **Regularization** (Ridge, Lasso) to handle multicollinearity.
- Perform **feature selection** for better model performance.

---

## 📬 Contact
If you have any questions or feedback, feel free to reach out via [GitHub Issues](https://github.com/yourusername/repo-name/issues).

