# unsupervised-machine-learning-challenge

You are on the data science team of a medical research company that’s interested in finding better ways to predict myopia, or nearsightedness. Your team has tried—and failed—to improve their classification model when training on the whole dataset. However, they believe that there might be distinct groups of patients that would be better to analyse separately. So, your supervisor has asked you to explore this possibility by using unsupervised learning.

You have been provided with raw data, so you’ll first need to process it to fit the machine learning models. You will use several clustering algorithms to explore whether the patients can be placed into distinct groups. Then, you’ll create a visualisation to share your findings with your team and other key stakeholders.

## Summary

### Part 1: Prepare the Data
* CSV file was loaded into a Pandas DataFrame.
* MYOPIC column was removed from the dataset.
* Data is standardised using a scaler.

### Part 2: Apply Dimensionality Reduction
* Dimensionality reduction was performed, the number of features changed from 14 to 10.
* Explained variance is at 0.9187361702915189.
* The dataset is further reduced using t-SNE to 3 features.

### Part 3: Perform a Cluster Analysis with K-means
* Elbow plot was created, the best number of clusters is between 2 and 3.

### Part 4: Make a Recommendation
* Based on the findings, the patients can be clustered into 3 clusters. 