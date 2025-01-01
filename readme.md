# Student Math Score Prediction
## END to END Machine Learning Projects

This repository contains an end-to-end machine learning project designed to predict students' math scores based on input data. The project encompasses data analysis, model development, evaluation, and deployment using a structured and scalable approach with best pratices.

## Features
- Comprehensive Exploratory Data Analysis (EDA) to uncover key patterns and insights.
- Implementation of multiple machine learning algorithms:
  - KNeighborsRegressor
  - DecisionTreeRegressor
  - RandomForestRegressor
  - AdaBoostRegressor
  - Support Vector Regressor (SVR)
  - LinearRegression
  - Ridge
  - Lasso
  - XGBRegressor
- Model evaluation using statistical metrics like Mean Squared Error (MSE) and R² score.
- Hyperparameter tuning with RandomizedSearchCV for optimal model performance.
- Robust logging and exception handling mechanisms.
- Deployment-ready prediction pipeline.
- Deployment on AWS Elastic Beanstalk for real-world usability.


## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/swapilverma/mlprojects.git
   cd mlprojects
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```


## Results
- The final model (Ridge Regression) achieves high accuracy with a R² score of `0.88`.
- The prediction pipeline provides reliable and scalable predictions for new input data.

## Future Enhancements
- Incorporating additional features to improve prediction accuracy.
- Extending the deployment to support containerization with Docker.
- Implementing CI/CD for streamlined updates.

## Contributions
Feel free to fork this repository and submit pull requests for improvements. Feedback is always welcome!
