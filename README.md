# 🌸 Iris_ML_Model

This is my first Machine Learning project using **Scikit-Learn**. I’ve trained a **RandomForestClassifier** on the famous **Iris Dataset** to classify different species of iris flowers based on their petal and sepal measurements.

---

## Files in This Repository

- `traing_on_iris_dataset.ipynb` — Jupyter Notebook with model training, prediction, and accuracy check.
- `iris-train.xlsx` — Excel file used for training the model.
- `iris-test.xlsx` — Excel file used for testing the model.

---

# What This Project Does

- Loads the Iris training dataset
- Trains a Random Forest Classifier
- Makes predictions on custom inputs and test dataset
- Calculates and prints the accuracy (~97%)

---

## Sample Prediction

```python
model.predict([[5.3, 3.7, 1.5, 0.2]])
# Output: ['Iris-setosa']
** Technologies Used
Python

Pandas

Scikit-learn

Jupyter Notebook
**How to Run
Clone the repo:

Copy
Edit
git clone https://github.com/minku999/Iris_ML_Model.git
cd Iris_ML_Model
Install dependencies:

Copy
Edit
pip install pandas scikit-learn openpyxl
Open the notebook:

Use Jupyter Notebook or VS Code with Jupyter extension

Run all cells in traing_on_iris_dataset.ipynb

📊 Accuracy
Tested on iris-test.xlsx

Achieved ~97% model accuracy

🙋‍♂️ Author
Mayank
GitHub: @minku999

📃 License
This project is licensed under the MIT License.
