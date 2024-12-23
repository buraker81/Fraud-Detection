
# Fraud Detection Project

## Project Overview
This project is centered on building and evaluating fraud detection systems using both real-world and simulated data. The aim is to identify fraudulent activities effectively by advanced data science and machine learning techniques. The work spans data simulation, feature engineering, and model development, ensuring a robust and scalable solution.

## Motivation
The project that I developed was the part of my Microsoft Turkey FY 24 Summer Internship program. The aim of the project was to apply and develop machine learning techniques in real-life data.


### Models Implemented
The following models were explored and implemented to detect fraud:
1. Logistic Regression
2. SVM
3. Decision Trees
4. Random Forests
5. XGBoost ✅

## Dataset
### Real-World Data
The project includes analysis and modeling on a real-world dataset processed in the `fd_system3.ipynb` notebook. The dataset was preprocessed to handle missing values, normalize features, and address imbalances.

### Simulated Data
To complement the real-world data, simulated datasets were created and processed:
- `data_simulation.ipynb`: Contains the generation of synthetic transaction data, incorporating features and distributions that mimic real-world fraud scenarios.
- `feature_transformation.ipynb`: Details the feature engineering and transformations applied to the simulated dataset to enhance model performance.

## Results
- **Model Accuracy**: The implemented models achieved high accuracy rates, with the best-performing model attaining an average accuracy of 0.90.
- **Precision and Recall**: Precision and recall scores were prioritized to ensure the system effectively identifies fraudulent transactions while minimizing false positives.
- **Comparison**: The simulated data provided valuable insights and enabled a controlled environment for testing the models.

## Requirements
- pandas
- numpy
- scikit-learn
- xgboost
- lightgbm
- matplotlib
- seaborn

## Conclusion
This project demonstrates the capability to detect fraudulent activities using a combination of real and simulated data. By leveraging advanced machine learning models, the system achieved a balance between accuracy, precision, and recall, ensuring reliable fraud detection.

