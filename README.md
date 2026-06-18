# Decision Tree Models: Classification and Regression

This repository contains Jupyter Notebooks demonstrating the implementation, evaluation, and visualization of Decision Tree algorithms for both classification and regression tasks using Python and `scikit-learn`.

---

## 📂 Repository Contents

* **`Decision_tree_classifire.ipynb`**
  * **Task:** Classification
  * **Dataset:** Titanic Dataset (loaded via Seaborn)
  * **Description:** Builds a Decision Tree Classifier to predict passenger survival ("Died" vs "Survived") based on passenger demographics and ticket features. The notebook includes data loading, model training, accuracy scoring (achieving ~82.4% accuracy), and a visual plot of the resulting tree.

* **`Decision_tree_Regressor.ipynb`**
  * **Task:** Regression
  * **Dataset:** Diabetes Dataset (loaded via Scikit-Learn)
  * **Description:** Builds a Decision Tree Regressor to predict diabetes disease progression based on physiological baseline variables. Demonstrates model fitting for continuous target variables and features a full visualization of the regression tree.

---

## 📊 Datasets

* **Titanic Dataset:** A famous dataset containing demographic and travel information for Titanic passengers (e.g., age, sex, passenger class, fare) used to predict survival odds.
* **Diabetes Dataset:** Contains 10 baseline variables (e.g., age, sex, BMI, average blood pressure) for 442 diabetes patients, used to predict a quantitative measure of disease progression one year after baseline.

---

## 🛠️ Technologies & Libraries

To run these notebooks, the following libraries are utilized:
* **Python 3.x**
* **scikit-learn**: For model building (`DecisionTreeClassifier`, `DecisionTreeRegressor`), data splitting (`train_test_split`), dataset loading, and visualization (`plot_tree`).
* **pandas**: For data manipulation and DataFrame structuring.
* **seaborn**: For loading the Titanic dataset.
* **matplotlib**: For rendering the decision tree visualizations.
