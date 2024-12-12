## This is a short description of how I went about the project.
Since I am just beginning with ML, I first had to learn all of the libraries associated with it. Pandas, Numpy were 
the ones I learnt first along with Matplotlib. Then I went on to learn scikitlearn for application of algorithms.
The basic workflow of this project, which was also provided in the tasks, is:
1. I first loaded my data and all the initial setup.
2. Next I prepared my data so that there were no missing or duplicate values.
3. Then I proceeded to normalize the values in each column by using z-score values as almost all of the data columns followed a normal distribution.
4. Next I had to decide which data to use for testing and which for training, since I had all of the data. I did this by
5. I then figured out which features were actually indicative towards whether a transaction is fraud.
6. A major challenge was class imbalance, since
7. I then proceeded to apply popular classification algorithms on my data.
8. Then I made an ROC-AUC curve of various models. The curve with the maximum area under it represents the best model for the classification of given data.
