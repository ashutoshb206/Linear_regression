# 📈 Linear Regression Projects using Scikit-learn

This repository demonstrates two implementations of **Linear Regression** using Python and the Scikit-learn library, applied to real-world datasets.

---

## 🗂️ Project Files

| File Name                      | Description                                             |
|-------------------------------|---------------------------------------------------------|
| `linear_regression_diabetes.ipynb` | Linear regression on the Diabetes dataset (predicts disease progression) |
| `linear_regression_dataset.ipynb`  | Linear regression on the California Housing dataset (predicts median house value) |

---

## 📊 Datasets Used

### 1. **Diabetes Dataset** (from `sklearn.datasets`)
- Features: age, sex, bmi, blood pressure, and 6 serum measurements
- Target: disease progression after one year

### 2. **California Housing Dataset** (from `sklearn.datasets.fetch_california_housing`)
- Features: MedInc, HouseAge, AveRooms, AveOccup, etc.
- Target: Median house value in California districts

---

## 🔧 What the Notebooks Do

Both notebooks:
- Load and preprocess the dataset
- Split the data into training and test sets
- Train a **Linear Regression** model using Scikit-learn
- Predict and evaluate performance using:
  - Coefficients and intercept
  - Mean Squared Error (MSE)
  - Coefficient of Determination (R² score)
- Visualize predictions with Seaborn and Matplotlib

---

## 📌 Sample Output
Coefficients: [...]
Intercept: ...
Mean squared error (MSE): ...
Coefficient of determination (R²): ...

## ✅ Requirements

To run the notebooks, install the required libraries using:

scikit-learn
pandas
matplotlib
seaborn

## 🚀 Getting Started

To run this project locally:

### 1. Clone the repository:

```bash
git clone https://github.com/ashutoshb206/Linear_regression.git
cd Linear_regression

```
### 2. Open the notebook 
```bash
jupyter notebook linear_regression_diabetes.ipynb
# or
jupyter notebook linear_regression_dataset.ipynb
```
3. Run all cells
Run all cells to see model training, prediction, evaluation metrics, and plots

Feel free to star ⭐ the repo if u find it helpful.

