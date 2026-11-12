# Iris Flower Classification Using Machine Learning

## 1. Project Overview

This project implements a supervised machine learning approach to classify Iris flowers into three species: **Iris Setosa, Iris Versicolor, and Iris Virginica**.

Multiple classification algorithms are trained and evaluated to identify the best-performing model based on standard performance metrics.

## 2. Dataset Description

- **Dataset:** Iris Flower Dataset
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/53/iris)
- **Original Records:** 150
- **Records After Duplicate Removal:** 147
- **Input Features:** 4
- **Target Variable:** Species

### Features
1. Sepal Length
2. Sepal Width
3. Petal Length
4. Petal Width

### Target Classes
- Iris Setosa
- Iris Versicolor
- Iris Virginica

## 3. Methodology

The project follows these steps:

1. Dataset collection and loading.
2. Exploratory Data Analysis (EDA).
3. Data cleaning and duplicate removal.
4. Target label encoding.
5. Splitting the dataset into 70% training and 30% testing data.
6. Training and comparing multiple classification algorithms.
7. Hyperparameter tuning using GridSearchCV.
8. Five-fold cross-validation.
9. Model evaluation and final model selection.

## 4. Machine Learning Algorithms

The following algorithms were implemented:

- Logistic Regression
- Decision Tree Classifier
- K-Nearest Neighbors (KNN)
- Random Forest Classifier
- Gradient Boosting Classifier

## 5. Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC Curve and AUC Score

GridSearchCV and Stratified 5-Fold Cross-Validation were used to tune and evaluate the advanced models.

## 6. Results and Performance

The tuned Gradient Boosting model was selected as the final model.

| Evaluation Metric | Result |
|---|---:|
| Test Accuracy | 93.33% |
| Macro ROC-AUC | 0.9926 |

The model achieved strong classification performance on the test dataset.

## 7. Feature Importance

The Gradient Boosting model identified the following feature contributions:

- Petal Width: 65.25%
- Petal Length: 26.77%
- Sepal Width: 7.86%
- Sepal Length: 0.12%

Petal measurements were the most influential features in predicting Iris species.

## 8. Technologies Used

- **Programming Language:** Python
- **Development Environment:** Google Colab
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn

## 9. Project Files

- `iris_classification.ipynb` – python Notebook containing the complete implementation, analysis, model training, and evaluation.
- `Iris_Flower_Classification_Technical Report` – Technical report describing the project methodology and results.

## 10. Conclusion

This project demonstrates the application of supervised machine learning algorithms to a multiclass classification problem. Five classification models were compared, and Gradient Boosting achieved the highest test accuracy of 93.33%. The results also highlight the importance of petal measurements in Iris flower classification.

## Author

**M.Shashikiran**  
B.Tech – Computer Science Engineering  
