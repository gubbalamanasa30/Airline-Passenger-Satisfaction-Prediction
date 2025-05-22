# Airline Passenger Satisfaction Prediction

## Introduction

This repository presents a detailed analysis and predictive modeling of airline passenger satisfaction using various machine learning techniques. The analysis provides insights into key factors influencing passenger satisfaction and aids airlines in strategic decision-making for enhanced customer experiences.

## Objective

The aim of this project is to build and compare machine learning models to accurately predict airline passenger satisfaction based on diverse passenger data.

## Dataset

The dataset used in this analysis is sourced from Kaggle and contains 103,904 entries with 23 features detailing passenger demographics, flight details, and satisfaction levels.

**Preprocessing Steps:**
- Handling missing values
- Removing irrelevant features (`Unnamed: 0`, `id`)
- Encoding categorical variables
- Feature normalization

## Machine Learning Models

The following models were implemented and evaluated:
- **Logistic Regression**
- **Decision Tree Classifier**
- **Random Forest Classifier**
- **Neural Network (MLP Classifier)**

### Evaluation Metrics

Models were evaluated using:
- Accuracy
- Precision
- Recall
- F1 Score
- Precision-Recall Curve
- Confusion Matrix
- Permutation Feature Importance
- Cross-validation

## Results

| Model                  | Accuracy | Precision | Recall | F1-score |
|------------------------|----------|-----------|--------|----------|
| Logistic Regression    | 81.83%   | 78.13%    | 81.37% | 79.72%   |
| Decision Tree          | 94.66%   | 93.72%    | 94.15% | 93.93%   |
| Random Forest          | 96.34%   | 97.40%    | 94.18% | 95.76%   |
| Neural Network         | 91.35%   | 87.03%    | 94.34% | 90.54%   |

**Random Forest** achieved the highest accuracy and F1 score, demonstrating its superior capability in accurately predicting passenger satisfaction.

## Key Insights
- **Top influential factors**: Type of travel, Inflight Wi-Fi service, Customer type, and Ease of online booking.
- **Random Forest** provided robust results with high predictive accuracy and low false prediction rates.

## Tools and Libraries
- Python (NumPy, Pandas)
- Scikit-learn
- Matplotlib

## Future Work
- Implement Explainable AI (XAI) techniques for model interpretability.
- Address class imbalance using advanced methods like SMOTE.
- Explore hyperparameter tuning with Grid Search or Bayesian Optimization.
- Experiment with ensemble methods like stacking and blending.

## Repository Structure
```
Airline-Passenger-Satisfaction/
├── data/
│   ├── train.csv
│   └── test.csv
├── notebooks/
│   └── Airline_passenger_satisfaction.ipynb
├── reports/
│   └── Airline_passengers_satisfaction_report.docx
└── README.md
```

## Contributors
- Shagamreddy Sairam Reddy
- Dispa Krishna Priya Gude
- Boddapati Thilak Chowdary
- Manasa Gubbala
- Suhas Bitragunta
- Sanjay Kumar Vadla

## License

This project is licensed under the MIT License - see the LICENSE file for details.
