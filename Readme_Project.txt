Here, we initially used SparkContext and SQLContext for our project. But later on after learning SparkSession, we have decided to work and move forward with SparkSession.
With SparkSession, we have now preprocessed the data and converted it into label and features format.
After that was done we have implemented 4 models here.
1) Logistic Regression : ROC around 0.99
2) Decision Trees: Accuracy around 91%
3) Random forest: Accuracy around 93%
4) Ensemble model using GBT: Accuracy around 91%.

We have used 3 files here.
1) OccupancyTraining
2) OccupancyData_1
3) OccupancyData_2

Last 2 are the testing data which is given to model after models were trained with OccupancyTraining.