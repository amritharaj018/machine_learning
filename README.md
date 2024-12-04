# Ensemble Learning with Boosting, Bagging, and Stacking

In this tutorial, we will apply three popular ensemble learning techniques—**Boosting**, **Bagging**, and **Stacking**—to predict wine quality based on its physicochemical attributes using the Wine Quality dataset.

## Dataset:
- **Features**: 11 input features such as alcohol, pH, and residual sugar.
- **Target**: Wine quality ratings (integer values from 0 to 10).
- **Goal**: Predict wine quality using the given features.

## Requirements:
- **Libraries**: 
  - `sklearn` for machine learning models and evaluation metrics.
  - `pandas`, `numpy` for data manipulation.
  - `matplotlib` for visualization.

## Steps:
1. **Import Libraries**: We will import the necessary libraries for data processing, model building, and evaluation.
2. **Load the Wine Dataset**: We will load the Wine Quality dataset using `sklearn.datasets.load_wine`.
3. **Split the Data**: The dataset will be divided into training and testing sets (80% training, 20% testing).
4. **Build Ensemble Models**:
   - **Bagging**: Using **RandomForestClassifier**.
   - **Boosting**: Using **AdaBoostClassifier** and **GradientBoostingClassifier**.
   - **Stacking**: Combining base models like **RandomForestClassifier** and **GradientBoostingClassifier** with a **LogisticRegression** meta-model.
5. **Evaluate Models**: Accuracy and classification reports will be generated for each model.
6. **Visualization**: A bar chart will be created to compare the accuracy scores of each model.

By the end of this tutorial, you will have hands-on experience with ensemble learning techniques and understand how they improve model performance.