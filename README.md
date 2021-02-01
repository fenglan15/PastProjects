# Superconductivity

## About 
I explored the Superconductivity datasets by utilizing different types of visualizations, including matplotlib and seaborn. With heatmap and pairplot, I successfully chose and extracted the representative features, which had little or no collinearity with each other, from each dataset, and combined them into a new dataset. In addition, I figured the ridge regression model fitted the new dataset the best after applying the linear regression, ridge regression, and lasso regression models to the new dataset. Lastly, I performed the random forest model on the dataset and found out this model has 99.8% accuracy when predicting superconductors’ critical temperature.


## Data
The data that I used in this project is called Superconductivity Data, which was drawn from UC Irvine Machine Learning Repository database. There are two datasets involved in this project. One is the train dataset, which contains information about 81 features of 21263 observations/superconductors along with the critical temperature in the last column. The second dataset is called the unique dataset, which includes information of  86 elements with their corresponding proportion in each material. There are 21263 observations/substances in total. The last two columns of this dataset are chemical formulas of materials and their corresponding critical temperature.
