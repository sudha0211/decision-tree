# Student Placement Prediction using Decision Tree Classifier

This project aims to predict whether a student will be placed or not based on their academic and personal background using a Decision Tree Classification Model

This Jupyter Notebook contains the end-to-end workflow for the student placement classification task. It involves data preprocessing, model training, evaluation, and saving the model using pickle.


Workflow Summary
1. Importing Required Libraries
Standard Python libraries like pandas, numpy, matplotlib, seaborn, and sklearn are used for data manipulation, visualization, and model building.
2. Data Preprocessing
Loaded the CSV dataset into a DataFrame.
Categorical variables are encoded using LabelEncoder.
Dropped unnecessary columns like student names or serial numbers (if present).
Checked and handled null/missing values.
3. Feature Engineering
Defined input features (X) and target (y).
Performed train_test_split to divide data into training and test sets.
4. Model Building
Trained a DecisionTreeClassifier using the training data.
Visualized the tree structure using plot_tree for interpretability.
5. Model Evaluation
Evaluated the classifier using:
Accuracy score
Confusion matrix
Classification report (Precision, Recall, F1-Score)
6. Model Serialization
The trained model is saved using the pickle module to a .pkl file for later use in deployment.

placementdata.csv

Confusion Matrix:
 [[892 300]
 [257 551]]
Accuracy Score: 0.7215
Accuracy in Percentage: 72 %


