# Student Score Prediction

This project is part of my **Data Science & Business Analytics Internship** with **The Sparks Foundation**.

## 📌 Objective

To predict the percentage of marks a student is expected to score based on the number of hours they studied. This is a simple linear regression task involving a single feature.

---

## 🔧 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📈 Dataset

- Source: [http://bit.ly/w-data](http://bit.ly/w-data)
- Features:
  - `Hours`: Number of study hours
  - `Scores`: Percentage score

---

## 📊 Steps Performed

1. **Data Importing and Preprocessing**
   - Loaded dataset using `pandas`.
   - Checked for basic statistics and missing values.

2. **Data Visualization**
   - Scatter plots and distribution plots using `matplotlib` and `seaborn`.

3. **Model Training**
   - Used Linear Regression model from `scikit-learn`.
   - Trained the model on 80% of the data.

4. **Model Evaluation**
   - Evaluated using R² scores on training and test sets.
   - Visualized the regression line.

5. **Prediction**
   - Predicted the score for a student studying 9.25 hours per day.

---

## ✅ Result

The predicted score for a student who studies **9.25 hours/day** is:

