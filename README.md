# Linear Regression on Income Dataset

This project implements a simple linear regression model to predict happiness based on income using a dataset. The goal of the model is to explore the relationship between income and happiness and evaluate the model's performance using various regression metrics.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Steps to Run the Code](#steps-to-run-the-code)
- [Model Evaluation](#model-evaluation)
- [Results](#results)
- [Conclusion](#conclusion)
- [License](#license)

## Project Overview

In this project, we use a dataset containing `income` and `happiness` values. The task is to train a linear regression model to predict happiness based on income. The project also includes data visualization, model evaluation, and improvement techniques like normalization.

## Dataset

The dataset contains the following columns:
- **Unnamed: 0**: Index column.
- **income**: The income value of an individual.
- **happiness**: The happiness score associated with the income.

## Technologies Used

- **Python**: Programming language used.
- **Libraries**:
  - `Pandas`: For data manipulation and analysis.
  - `NumPy`: For numerical operations.
  - `Matplotlib` and `Seaborn`: For data visualization.
  - `Scikit-learn`: For machine learning, specifically linear regression and evaluation metrics.
  - `Pickle`: For saving the trained model.

## Steps to Run the Code

1. Clone the repository:
   ```bash
   git clone https://github.com/Himel-Sarder/Linear-Regression-on-Income-Dataset-Kaggle.git
   cd Linear-Regression-on-Income-Dataset-Kaggle
   ```

2. Run the Jupyter notebook:
   ```bash
   jupyter notebook
   ```

4. Open the notebook and execute the cells to see the results.

## Model Evaluation

The model was evaluated using the following metrics:

- **Mean Absolute Error (MAE)**: 0.5516
- **Mean Squared Error (MSE)**: 0.4616
- **R-squared (R²)**: 0.7656
- **Root Mean Squared Error (RMSE)**: 0.6794
- **Adjusted R²**: 0.7608

These metrics indicate that the model performs well, with an R² of 0.7656, meaning that 76.56% of the variance in happiness can be explained by income.

## Results

After training the linear regression model, the following results were obtained:
- The model achieved a high R² score of 0.7656.
- The RMSE value of 0.6794 suggests a reasonable fit to the data.

## Conclusion

The linear regression model successfully predicts happiness based on income. The model could be improved further by exploring more features, using polynomial regression, or experimenting with other machine learning models. However, the current model performs well with the given data.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
