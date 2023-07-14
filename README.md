# credit-card-fraud-detiction

Dataset link : https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

# The code is performing an analysis on a credit card fraud dataset using Python. Here's a brief summary of what each section of the code does:
## 1.Importing necessary libraries:
numpy for numerical computations
pandas for data manipulation and analysis
matplotlib and seaborn for data visualization
gridspec for creating multi-plot grids
## 2.Reading the dataset:
The credit card fraud dataset is read from a CSV file using pandas' read_csv() function.
## 3.Exploring the dataset:
The columns of the dataset are printed using the print(data.columns) statement.
The describe() function is called on the dataset to get the statistical summary of the columns.
A sample of the dataset is taken using the sample() function to reduce the size of the dataset for faster processing.
## 4.Visualizing the dataset:
A histogram is plotted for all the columns of the dataset using the hist() function to understand the distribution of the data.
A correlation matrix is plotted using the heatmap() function of seaborn to identify the correlation between the different features of the dataset.
## 5.Preprocessing the dataset:
The dataset is divided into input features (X) and output variable (Y).
The dataset is then split into training and testing sets using the train_test_split() function from sklearn.
## 6.Building a Random Forest model:
A random forest classifier is created using the RandomForestClassifier() function from sklearn.
The training data is fit into the model using the fit() function.
Predictions are made on the test data using the predict() function.
## 7.Evaluating the Random Forest model:
The accuracy, precision, recall, F1-Score, and Matthews correlation coefficient are calculated using the corresponding functions from sklearn.metrics.
The confusion matrix is plotted using the heatmap() function of seaborn.
