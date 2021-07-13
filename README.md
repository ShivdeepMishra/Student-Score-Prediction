## TSF Task 01- Student Score Prediction using Supervised ML
Predict the percentage of an student based on the no. of study hours. This is a simple linear regression task as it involves just 2 variables.

### Author
Shivdeep Mishra

### Date
02-07-2021

### Programming Language
Python

### Task File
Task 01- Prediction using Supervised ML.ipynb

### Data Source
http://bit.ly/w-data

### EDA
The dataset has two columns and 25 rows. "Hour" is the feature column and "Score" is the target column. And it doesn't have any null value in either column. It contains two types of data, float and integer type.

According to Hours summary, minimum value is 1.1, maximum value is 9.2 and the average study hours value is 5.012. And as per Score column, minimum value is 17.0, maximum value is 95.0 and average score is 51.48.

The relative scatter plot and correlation matrix shows between Hours and Score shows that there is strong positive correlation between them.

### ML Model used
The simple linear regression has been used to train and test the data.

### Results
If a student studies for 9.25 hrs/ day, predicted score will be 92.38611528261494.

Mean Squared Error: 18.943211722315272 

Root Mean Squared Error: 4.352380006653288 

Mean Absolute Error: 3.9207511902099244

### Credits
The Spark Foundation

Xaltius Pte. Ltd.
