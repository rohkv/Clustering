# Clustering
Performed hierarchical clustering using Dendrogram and k-means clustering to segregate passengers based on their air miles (balance, accrual), CC usage and points collected for target marketing.
First we standardize the dataset after removing the ID# and Award column. 
Then do Hierachical clustering using Euclidean distance and Ward method.
We get 3 significant clusters based on this approach. 
To perform k-means clustering, we find the bend in the 'Elbow graph' and then take that number as our k. 
Based on this, we formed 2 significant clusters and now we can use this output for target marketing
