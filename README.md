# Heart Problem Prediction

This notebook demonstrates a machine learning project to predict heart problems using a dataset. We go through the steps of data preprocessing, exploratory data analysis, feature engineering, model training, evaluation, and making predictions.

## Dataset
- **Name**: `heart.csv`
- **Description**: This dataset contains various features related to patients' health metrics to predict the likelihood of heart problems. The features include age, sex, chest pain type, resting blood pressure, cholesterol level, fasting blood sugar, resting electrocardiogram results, maximum heart rate achieved, exercise-induced angina, ST depression induced by exercise, slope of the peak exercise ST segment, number of major vessels, thalassemia, and the target variable indicating the likelihood of a heart attack.

## Project Steps
1. **Data Preprocessing**: Handle missing values, encode categorical variables, and normalize numerical features.
2. **Exploratory Data Analysis (EDA)**: Visualize the data and understand the relationships between features.
3. **Feature Engineering**: Select important features based on correlation with the target variable.
4. **Model Training**: Train machine learning models to predict heart problems.
   - **Algorithms Used**: Logistic Regression, Random Forest Classifier
5. **Model Evaluation**: Evaluate the models using various metrics.
   - **Evaluation Metrics**: Accuracy, Precision, Recall, F1-Score, ROC-AUC Score, Confusion Matrix

## Installation

To get started with this project, clone the repository and install the required dependencies:

```bash
git clone https://github.com/mohammad007kh/Heart-Problem-Prediction.git
cd Heart-Problem-Prediction
pip install -r requirements.txt
```

## Contributing

Contributions are welcome!

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.