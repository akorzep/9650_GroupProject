Electricity consumption

The data is read into a dataframe. 
There are 5 energy resources : coal, other gasses, natural gas, geothermal and petroleum.
We are trying to find the electricity consumed by each of these resources.
In addition to this, we also try to predict the electricity consumed for the upcoming years.
For this, we will use Linear Regression. 
Linear Regression is a Machine Learning algorithm/statistical method that helps extrapolate values for the given data.
A sample dataset for Linear Regression model would contain two columns where one value in one column maps to the corresponding value in the second column. 
This data can be used to train the model. Few values in the first columns would not have a corresponding value in the second column.
These are the values that need to be predicted. For this purpose, the data (which has both the column of values) is trained using scikit-learn. The “linear_model” class is imported from scikit-learn to implement Linear Regression .
This training data is used to extrapolate/predict the values which don't have a corresponding second column-value.
The x value or the first column is the resource and the y value is the electricity consumed (with respect to the graph).
