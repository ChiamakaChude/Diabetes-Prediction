# Diabetes-Prediction

This project implements classification models to predict diabetes status using health indicators. The models used include Support Vector Machine (SVM), Decision Tree, and Multi-Layer Perceptron (MLP). The dataset used is the Diabetes Health Indicators dataset from Kaggle.

# Project Overview
The goal of this project is to develop and evaluate machine learning models for classifying diabetes status based on various health indicators. The project includes data preprocessing, exploratory data analysis, model training, and evaluation.

# Dataset
The dataset used in this project is from Kaggle and includes the following columns:

Diabetes_binary: Diabetes status (0 = non-diabetic, 1 = diabetic)
HighBP: High blood pressure (0 = no, 1 = yes)
HighChol: High cholesterol (0 = no, 1 = yes)
CholCheck: Cholesterol check in the past 5 years (0 = no, 1 = yes)
BMI: Body Mass Index
Smoker: Smoking status (0 = no, 1 = yes)
Stroke: Ever had a stroke (0 = no, 1 = yes)
HeartDiseaseorAttack: Coronary heart disease or myocardial infarction (0 = no, 1 = yes)
PhysActivity: Physical activity in the past 30 days (0 = no, 1 = yes)
Fruits: Consumed fruits 1 or more times per day (0 = no, 1 = yes)
Veggies: Consumed vegetables 1 or more times per day (0 = no, 1 = yes)
HvyAlcoholConsump: Heavy alcohol consumption (0 = no, 1 = yes)
AnyHealthcare: Health care coverage (0 = no, 1 = yes)
NoDocbcCost: Could not see a doctor due to cost (0 = no, 1 = yes)
GenHlth: General health (1 = excellent, 2 = very good, 3 = good, 4 = fair, 5 = poor)
MentHlth: Mental health in the past 30 days (1-30 days)
PhysHlth: Physical health in the past 30 days (1-30 days)
DiffWalk: Difficulty walking or climbing stairs (0 = no, 1 = yes)
Sex: Gender (0 = female, 1 = male)
Age: Age category (1 = 18-24, 9 = 60-64, 13 = 80 or older)
Education: Education level (1-6)
Income: Income level (1-8)


# Models Implemented
The project employs the following machine learning models:

Support Vector Machine (SVM): A supervised learning model that finds the hyperplane that best separates different classes.
Decision Tree: A tree-based model that splits data into subsets based on feature values to predict the target variable.
Multi-Layer Perceptron (MLP): A type of neural network with multiple layers of nodes that can model complex relationships between features and the target variable.

# Results
Model Performance: Various metrics, such as accuracy, precision, recall, and F1 score, are used to evaluate and compare the performance of the different models.
