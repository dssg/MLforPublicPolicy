In this homework, you'll continue to build the Machine Learning pipeline. The goal is to improve the pipeline based on the feedback from previous assignments, and add a few components based on what we've covered in the past few lectures. More specifically, you need to:

 Coding Assignment:

1. Fix and improve the pipeline code you submitted for the last assignment based on the feedback from the TAs. if something critical was pointed out in the feedback, you need to fix it. 

2. Add more classifiers to the pipeline. I’d recommend at least having Logistic Regression, K-Nearest Neighbor, Decision Trees, SVM, Random Forests, Boosting, and Bagging. The code should have a parameter for running one or more of these classifiers and your analysis should run all of them.

3. Experiment with different parameters for these classifiers (different values of k for example, as well as parameters that other classifiers have). You should look at the sklearn documentation to see what parameter each classifier can take and what the default values sklearn selects.

4. Add additional evaluation metrics that we've covered in class to the pipeline (accuracy, precision at different levels, recall at different levels, F1, area under curve, and precision-recall curves)

5. Once you've set up the improved pipeline, you can run the data from the last assignment and compare the performance of each classifier on each evaluation metric and other dimensions (such as training/test speed). The code should produce a comparison table.

Report:

You should also write a short report (1-2 pages) that compares the performance of the different classifiers across all the metrics for the data set used in the last assignment. Which classifier does better on which metrics? Which one runs faster? What would be your recommendation to someone who's working on the credit model?

It is ok (and encouraged) to talk to other students in the class about the homework but you need to each write and submit your own code and report. It's also ok to consult any web sources - google is a good friend for these types of problems.
