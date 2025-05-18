# Regression Model Comparison

This project compares the performance of three regression algorithms — **Linear Regression**, **Decision Tree Regressor**, and **Random Forest Regressor** — using the **California Housing** dataset from `sklearn.datasets`.

## Structure

- `Linearregressioncal.ipynb`: Implementation of Linear Regression
- `Decisiontreecalifornia.ipynb`: Implementation of Decision Tree
- `Randomforestcalifornia.ipynb`: Implementation of Random Forest
- `Linear-regression-results.png`, `Decision-tree-results.png`, `Random-forest-results.png`: Output graphs (RMSE, R², Accuracy)
- `Regression-project.pdf`: Contains a summary of methods used and results

## Metrics Used

- RMSE (Root Mean Square Error)
- R² Score
- Accuracy 
- Visual comparison using matplotlib

## Dataset

- California Housing dataset (from `sklearn.datasets.fetch_california_housing()`)

## Libraries Used

- `sklearn`
- `pandas`
- `matplotlib`
- `seaborn`
- `numpy`

## Observations

- Random Forest achieved the best performance based on both RMSE and R² score.
- Linear Regression performed the worst due to its simplicity and assumption of linearity.

## Notes

This was a 4th-semester academic project. The goal was to get hands-on experience with basic regression models and performance comparison.

