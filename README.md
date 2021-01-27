# Human activity Recognition using Machine Learning
* Explored and understood the dataset.
* Visualized the dataset.
* Set time series for each subject(activity).
* Classified the human activities using Machine Learning algorithms.

## Code and Resources Used
**Python Version:** 3.7
**Packages:** pandas, numpy, Sklearn, matplotlib.

## Dataset
For the dataset, I selected the training.csv and test.csv files from the Kaggle competition.**[Dataset link](https://www.kaggle.com/uciml/human-activity-recognition-with-smartphones)**

## Important points
1. The dataset has activity records for 30 individuals and some individual performed the Standing activity.
2. The data collected is recorded at a stretch for each individual, especially for each activity. This means the records of any given activity will actually be in time series.
3. There are many features in each record, but I am not including all as it might make the understanding of the data more difficult.
Based on the information I had, I decided that I’d plot a line graph for all individuals who performed the Standing activity over a time period with respect to a feature. I took the feature as the angle between X and mean Gravity, which should stay almost constant except for minor changes due to human error.

## Methodology
In this project, the human activity Recognition using kaggle dataset is been implemented.

* Drew visualisations from the dataset
  - The percenage values show that the data size for each activity is comparable. The dataset is equally distributed.
  
    ![alt text](https://github.com/vikasbhadoria69/Human-activity-Recognition-using-Machine-Learning/blob/master/Images/1.png)
    
    
    ![alt text](https://github.com/vikasbhadoria69/Human-activity-Recognition-using-Machine-Learning/blob/master/Images/2.png)

  - Accelerometer constitutes the maximum features, followed by Gyroscope. Other features are very less
  
   ![alt text](https://github.com/vikasbhadoria69/Human-activity-Recognition-using-Machine-Learning/blob/master/Images/3.png)
   
   - Taking a closer look at the graph, one can see that each line on an average, transitions between a maximum range of 0.2–0.3 values. This is indeed the expected behaviour as slight variations can be attributed to minor human errors.
   
    ![alt text](https://github.com/vikasbhadoria69/Human-activity-Recognition-using-Machine-Learning/blob/master/Images/4.png)
    
## Results

* Four Machine Learning models has been tested. The accuracy of each is as follows
  - Logistic Regression accuracy: 95.86019681031559%
  - K Nearest Neighbors Classifier accuracy: 90.02375296912113%
  - Random Forest Classifier accuracy: 92.63657957244655%
  - Support Vector Classifier: 93.92657957244655%
  
 * Clearly seen that Logistic Regression performed the best with the highest accuracy.
  - ![alt text](https://github.com/vikasbhadoria69/Human-activity-Recognition-using-Machine-Learning/blob/master/Images/5.png)
   
## Conclusion 
Using Machine Learning techniques to detect human activities can give much better accuracy and easy to use rather than the traditional threshold technique. As a future perspective, anyone can try other algorithms, or choose different values of classifiers to improve the accuracy even further. Please feel free to share your thoughts and ideas.

## Codes:
"Human activity Recognition using Machine Learning.ipynb" contains all the codes and graphs. 

