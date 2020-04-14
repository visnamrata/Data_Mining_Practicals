# Data_Mining_Practicals

Program 1: Create a file “people.txt” with the following data:
Age Age Group Height Status Years Married
21 adult 6.0 single -1
2 child 3 married 0
18 adult 5.7 married 20
221 elderly 5 widowed 2
34 child -7 married 3
i) Read the data from the file “people.txt”.
ii) Create a rule set E that contain rules to check for the following conditions :
The age should be in the range 0-150.
The age should be greater than years married.
The status should be married or single or widowed.
If age is less than 18 the age group should be child, if age is between 18 and 65 the age group should be adult, if age is more than 65 the age group should be elderly.
iii) Check whether rule set E is violated by the data in the file people.txt.
iv) Summarize the results obtained in part(iii)
v) Visualize the results obtained in part(iii)

Program 2 : Perform the following preprocessing tasks on the dirty_iris dataset.
i) Calculate the number and percentage of observations that are complete.
ii) Replace all the special values in data with NA.
iii) Define these rules in a separate text file and read them.
(Use editfile function in R (package editrules). Use similar function in Python).
Print the resulting constraint object.
Species should be one of the following values: setosa, versicolor or virginica.
All measured numerical properties of an iris should be positive.
The petal length of an iris is atleast 2 times its petal width.
The sepal length of an iris cannot exceed 30cm.
The sepals of an iris are longer than its petals.
iv) Determine how often each rule is broken (violatedEdits). Also summarize and plot the result.
v) Find outliers in sepal length using boxplot and boxplot.stats

Program 3 : Load the data from wine dataset. Check whether all attributes are standardized or not (mean is 0 and standard deviation is 1). If not, standardize the attributes. Do the same with Iris dataset.

Program 4 : Run Apriori algorithm to find frequent itemsets and association rules
4.1 Use minimum support as 50% and minimum confidence as 75%
4.2 Use minimum support as 60% and minimum confidence as 60%

Program 5 : Use Naive bayes, K-nearest, and Decision tree classification algorithms and build classifiers. Divide the data set in to training and test set. Compare the accuracy of the different classifiers under the following situations:
5.1 a) Training set = 75% Test set = 25%
5.1 b) Training set = 66.6% (2/3rd of total), Test set = 33.3%
5.2 Training set is chosen by i)hold out method ii)Random subsampling iii)Cross-Validation. Compare the accuracy of the classifiers obtained.
5.3 Data is scaled to standard format.

Program 6 : Use Simple Kmeans, DBScan, Hierachical clustering algorithms for clustering. Compare the performance of clusters by changing the parameters involved in the algorithms.
