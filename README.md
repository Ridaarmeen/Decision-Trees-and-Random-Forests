🫀 Heart Disease Prediction using Tree-Based Models
📌 Objective:
To predict the presence of heart disease using tree-based classification models: Decision Tree and Random Forest. The analysis focuses on training, evaluating, and interpreting model results using a cleaned heart disease dataset.

Target Variable: target (1 = Disease, 0 = No Disease)
Features: Includes clinical and demographic attributes such as age, cholesterol, resting blood pressure, chest pain type, etc.

🧰 Tools Used
-Python
-Scikit-learn – for model building and evaluation
-Matplotlib & Seaborn – for plotting and visualization
-Pandas – for data manipulation

🧪 Methodology:

1.Data Loading:
-Load the dataset from a CSV file using pandas.

2.Data Splitting:
-Split the data into training and test sets (80/20).

3.Model Training:
-Train a Decision Tree Classifier
-Train a Random Forest Classifier

4.Visualization:
-Visualize the structure of the decision tree
-Plot feature importances from the random forest

5.Evaluation:
-Evaluate both models using accuracy on the test set
-Apply 5-fold cross-validation on the Random Forest to assess generalization

📈 Results:
-Accuracy of Decision Tree and Random Forest are printed in the console.
-Feature importance plot highlights the most influential medical indicators.
-Cross-validation gives a robust estimate of Random Forest performance.
