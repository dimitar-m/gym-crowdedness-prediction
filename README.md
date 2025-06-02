# Campus Gym Crowdedness Prediction

This project aims to forecast how crowded a university gym gets based on historical records. Using linear regression with stochastic gradient descent (SGDRegressor), the model predicts the number of visitors based on features such as time, temperature, and academic calendar events.

## How to Run  
- Open the latest version of the project in **NBViewer**:  
  [View in NBViewer](https://nbviewer.org/github/dimitar-m/gym-crowdedness-prediction/blob/master/gym-crowdedness-prediction.ipynb)
  
## Objectives

- Predict the number of gym visitors.
- Analyze which factors influence gym traffic.
- Compare models trained on raw vs log-transformed targets.
- Visualize predictions for interpretability.

## Methods Used

- Time-aware train/test split
- Feature scaling (StandardScaler)
- Correlation analysis with the target
- SGDRegressor from Scikit-learn
- Model evaluation: RMSE, MAE, R²
- Visual comparison of predictions vs actual values

## Key Findings

- The model trained on **raw target values** outperformed the log-transformed one.
- Features like hour of the day and timestamp had the strongest correlation with visitor counts.
- A well-scaled, time-respecting model yielded an R² of ~0.51.

## Feedback

I'm always looking for ways to improve. Feedback and suggestions are welcome!
