#Team Members:

- [Jash Parikh](https://github.com/Jash7447)
- [Saahil Doshi](https://github.com/Legit-Ox)
- [Paridhi Jain](https://github.com/paridhijain19)
- [Nevil Jobanputra](https://github.com/Nevil844)
# Athlete Performance in Collegiate Basketball: Predicting Match Line-up

This project aims to enhance athlete performance in collegiate basketball through predictive analytics and visualization techniques. By leveraging a comprehensive dataset encompassing sleep patterns, training details, emotional states, game scores, and physiological indicators, we developed machine learning models to forecast match line-ups and support decision-making processes.

## Project Overview

The primary goal of this project is to predict individual athletes' Relative Strength Index (RSI) values and leverage this information to forecast the next match lineup. Additionally, we employ eXplainable AI (XAI) techniques to interpret model predictions and provide insights into the underlying factors influencing player performance.

## Dataset

The project utilizes a diverse dataset obtained from the performance of Division 1 Basketball players over two seasons. The dataset includes:

- Sleep patterns
- Training details
- Cardiac rhythm patterns
- Emotional-mental state information
- Game scores
- Weekly readiness scores
- Jump-data (RSImod)

## Methodology

1. **Data Preparation**: Merged datasets from two seasons, conducted correlation matrix analysis, imputed missing data using the Iterative Imputer with a Random Forest Regressor, and standardized the data.

2. **Feature Engineering**: Analyzed feature importance using the RandomForestRegressor to identify key predictors of the RSImod variable.

3. **Handling Imbalance**: Employed SMOTE-ENN and SMOTE-Tomek techniques to address class imbalance in the dataset.

4. **Model Development**: Trained an XGBClassifier to classify players based on their RSI quartiles, predict RSI values for the upcoming week, and forecast the next match lineup.

5. **eXplainable AI (XAI)**: Utilized SHAP (Shapley Additive exPlanations) analysis to interpret model predictions and understand the influence of different features.

6. **Visualization**: Developed a Streamlit dashboard for real-time visualization and comparison of individual performance metrics against team averages.

## Results

- Predicted individual athletes' RSI values with an accuracy of 97.47% and an F1-score of 0.98.
- Predicted RSI values for the upcoming week with an accuracy of 88.23% and an F1-score of 0.88.
- Forecasted the next match lineup using the trained model.
- Provided interpretable explanations for model predictions using SHAP analysis.
- Created an interactive Streamlit dashboard for visualizing and exploring player performance data.



Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## Acknowledgments

We would like to express our gratitude to the instructors and teaching assistants of the CSE 523 Machine Learning course for their guidance and support throughout this project.
