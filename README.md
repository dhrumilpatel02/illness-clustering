# illness-detection

# Description of Analysis Conducted

-For Mr. John Hughes, we are conducting the analysis where we are building and evaluating the Clustering model based on the data which consists of 30 attributes for tumor measurement and 1 variable indicating the diagnosis done.
-SVM approach has already been carried out and we have its confusion matrix already provided by Mr. John Hughes in Figure 1.
-There are various types od clustering techniques, but here we will use the K-means Clustering technique.
-In K-means Clustering the algorithm tries to locate a local maxima in each iteration.

# Identifying the number of clusters required to optimize a K-means Model

-There are a few methods to identify the number of clusters required to optimize a K-means model i.e. Elbow method, average silhouette method and gap statistic method.
-We carry out both elbow and average silhouette method to determine the number of clusters.
-Elbow method - Figure 1 shows that a visible bend can be spotted at number 2, so it says that the dataset likely has 2 clusters.
-Average silhouette method - Figure 2 shows that the highest silhouette coefficient is seen to be for the cluster 2, so the dataset likely has 2 clusters.
-By the results from both the methods, we can conclude that there are 2 clusters to be required to optimize the K-means model.

# Compare the SVM Algorithm to the Clustering Algorithm

-In the output obtained for both the algorithms, in SVM, the confusion matrix depicts the True Positive of SVM (69) is more than Ture Positive of K-means Clustering (356).
-This automatically affects the False Negative of SVM (3) and False Negative of K-means Clustering (1).
-We also see a difference in the values of precision for B (Benign) for SVM (0.97) as compared to the values of precision for B (Benign) for Naïve Bayes (0.81).
-We also see a difference in the values of recall for M (Malignant) for SVM (0.95) as compared to the values of recall for M (Malignant) for K-means Clustering (0.61).
-We also see a difference in the values of f1-score for M (Malignant) for SVM (0.94) as compared to the values of f1-score for M (Malignant) for Naïve Bayes (0.76)
-The macro and weighted averages of both the algorithms differ from the each other, the values of SVM are higher in all.
-All these factors affect the overall accuracy on the algorithm which is 96% for SVM and 85% for K-means Clustering..

# How the clustering analysis helps if the dataset doesn’t include the dependent variable

-As clustering tries to find a structure in the data, it becomes very important for unsupervised learning.
-When the dependent variable is not included in the dataset, the clustering analysis organizes elements into groups where it can find any similarities.
-In this dataset, if the diagnosis column is not included, we can still carry out the analysis and make clusters.
-Distance based clustering is a great way to analyze when it is not labeled, it calculates and measures the distance between any two or more points and determines its nature, this is how clustering analysis helps us in unsupervised learning.
-The centroids play a very crucial role in determining the clusters,  different location of these centroids pan out a different analysis.
-These centroids are to relate to every data point, when all the points are covered, the grouping is concluded.
