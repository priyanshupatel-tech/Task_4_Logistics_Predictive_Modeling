# Week 4: Predictive Modeling and Optimization in Logistics Systems

## Project Overview
This project applies machine learning techniques to predict delivery time using logistics-related features. Linear Regression and Decision Tree Regression models are trained and evaluated using a simulated dataset.

## Dataset
The dataset contains 200 simulated shipment records with the following features:
- Distance in kilometers
- Shipment volume
- Traffic level
- Weather delay hours
- Transport cost

**Target variable:** Delivery Time (Hours)

## Models Used
1. Linear Regression
2. Decision Tree Regressor

## Model Evaluation

| Metric | Linear Regression | Decision Tree |
|---|---:|---:|
| MAE | 0.877 | 1.042 |
| RMSE | 1.059 | 1.272 |
| R² Score | 0.823 | 0.745 |
| 5-Fold CV Average MAE | 0.785 | 1.148 |

Linear Regression performed better than Decision Tree on the test set and in cross-validation for this dataset.

## Optimization Recommendations
- Consider distance and traffic when evaluating delivery routes.
- Allocate vehicles according to shipment volume.
- Plan buffer time for weather-related delays.
- Monitor transport cost and delivery-time performance together.

## Limitations
The dataset is simulated for educational purposes. The results should not be treated as evidence of performance in real logistics operations.

## Tools and Libraries
Python, Pandas, NumPy, Matplotlib, and Scikit-learn.

## Conclusion
Linear Regression was the better-performing model for this experiment. Further validation with real operational data is necessary before practical deployment.
