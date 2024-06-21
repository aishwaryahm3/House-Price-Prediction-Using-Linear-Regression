# Linear-Regression-On-Dataset
This project demonstrates the application of both Simple Linear Regression and Multiple Linear Regression on the Boston Housing Dataset to predict housing prices. The dataset contains information collected by the U.S. Census Service concerning housing in the area of Boston, Massachusetts. The notebook walks through the process of loading the dataset, exploring the data, and applying linear regression models to predict the median value of owner-occupied homes (PRICE).

### Dataset
The dataset used in this project is the Boston Housing Dataset, which contains the following columns:
- `CRIM`: Per capita crime rate by town
- `ZN`: Proportion of residential land zoned for lots over 25,000 sq. ft.
- `INDUS`: Proportion of non-retail business acres per town
- `CHAS`: Charles River dummy variable (1 if tract bounds river; 0 otherwise)
- `NOX`: Nitric oxides concentration (parts per 10 million)
- `RM`: Average number of rooms per dwelling
- `AGE`: Proportion of owner-occupied units built prior to 1940
- `DIS`: Weighted distances to five Boston employment centers
- `RAD`: Index of accessibility to radial highways
- `TAX`: Full-value property tax rate per $10,000
- `PTRATIO`: Pupil-teacher ratio by town
- `B`: 1000(Bk - 0.63)^2 where Bk is the proportion of Black residents by town
- `LSTAT`: Percentage of lower status of the population
- `PRICE`: Median value of owner-occupied homes in $1000's

### Files
- `Boston_Housing_Dataset.csv`: The dataset file containing the housing data.
- `Linear Reg on Dataset.ipynb`: Jupyter notebook demonstrating the comparison between Simple Linear Regression and Multiple Linear Regression on the dataset.

### Requirements
- Python 3.x
- pandas
- numpy
- matplotlib
- scikit-learn


### Results
The notebook will guide you through visualizing the data, training the linear regression models, and evaluating their performance. The final models predict the median house prices based on the provided features, with a comparison of the results from Simple Linear Regression and Multiple Linear Regression.
