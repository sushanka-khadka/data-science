# House Price Prediction
This project predicts a home price in Boston Massachusetts in the 1970s form the boston.csv dataset.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#technology-used)
- [License](#license)

## Introduction

House prices can be influenced by a multitude of factors. This project utilizes a dataset to build predictive models that can estimate house prices based on the provided features. The goal is to create a model that generalizes well to unseen data.

## Dataset

The dataset used in this project is [boston.csv]. It contains the following attributes:
:Attribute Information (in order):
        1. CRIM     per capita crime rate by town
        2. ZN       proportion of residential land zoned for lots over 25,000 sq.ft.
        3. INDUS    proportion of non-retail business acres per town
        4. CHAS     Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
        5. NOX      nitric oxides concentration (parts per 10 million)
        6. RM       average number of rooms per dwelling
        7. AGE      proportion of owner-occupied units built prior to 1940
        8. DIS      weighted distances to five Boston employment centres
        9. RAD      index of accessibility to radial highways
        10. TAX      full-value property-tax rate per $10,000
        11. PTRATIO  pupil-teacher ratio by town
        12. B        1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
        13. LSTAT    % lower status of the population
        14. PRICE     Median value of owner-occupied homes in $1000's

### Data Preprocessing

Data preprocessing steps include:

- Handling missing values
- Encoding categorical variables
- Normalizing numerical features

## Installation

To run this project, you need to have Python installed along with the following libraries:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn ploty
```
Alternate way: download the resources and open the project file `multivariable_regr_model.ipynb` in `Jupiter Notebook'`.


## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn /Plotly (for data visualization)
- Jupyter Notebook (for development and testing)

## License

This project is free. Feel free to reach out if you have any questions or need further assistance!
