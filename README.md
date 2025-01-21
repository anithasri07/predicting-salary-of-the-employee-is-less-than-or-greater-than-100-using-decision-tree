# Employee Salary Prediction

This project predicts whether an employee's salary is less than or greater than $100 using a Decision Tree classifier. The project involves Exploratory Data Analysis (EDA), data preprocessing, model training, and evaluation. The goal is to build a model to classify employee salaries.

## Steps:

### 1. **Exploratory Data Analysis (EDA)**
- Analyzed the dataset to understand the distribution of salaries and relationships with other features.
- Visualized missing data, trends, and observed correlations.

### 2. **Data Preprocessing**
- Handled missing values and encoded categorical data.
- Scaled and transformed the data as required.
- Split the dataset into training and testing sets.

### 3. **Model Training**
- Trained a Decision Tree classifier to predict whether an employee's salary is greater or less than $100.

### 4. **Model Evaluation**
- Evaluated the model's performance using accuracy and confusion matrix.

### 5. **Salary Prediction**
- Predicted whether the salary of employees is greater or less than $100 based on the trained model.

## Requirements
- Python 3.x
- pandas
- scikit-learn
- matplotlib
- seaborn

## Usage

1. Clone the repository.
2. Place the `employee_salary.csv` dataset in the project directory.
3. Run `employee_salary_prediction.py` to preprocess the data, train the model, and predict salary categories.
4. View the results in the output.

## Results
The model's performance is evaluated using a confusion matrix, showing true positives, true negatives, false positives, and false negatives.

## License
This project is licensed under the MIT License.
