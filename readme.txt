Human activity Recognition using Machine Learning:

For the dataset, I selected the training.csv and test.csv files from the Kaggle competition.
Dataset link: https://www.kaggle.com/uciml/human-activity-recognition-with-smartphones

This is all the information I knew before I began:
1. The dataset has activity records for 30 individuals and some individual performed the Standing activity.
2. The data collected is recorded at a stretch for each individual, especially for each activity. This means the records of any given activity will actually be in time series.
3. There are many features in each record, but I am not including all as it might make the understanding of the data more difficult.
Based on the information I had, I decided that I’d plot a line graph for all individuals who performed the Standing activity over a time period with respect to a feature. I took the feature as the angle between X and mean Gravity, which should stay almost constant except for minor changes due to human error.

In this project, I did Activity Recognition using kaggle dataset, drew visualisations from the dataset and used machine learning algorithms for classifying activities. As per the results, Logistic Regression achieved the highest accuracy of 96%.

As a future perspective, anyone can try other algorithms, or choose different values of classifiers to improve the accuracy even further. Please feel free to share your thoughts and ideas.


libraries used:

1. Numpy
2. Pandas
3. Matplotlib
4. sklearn