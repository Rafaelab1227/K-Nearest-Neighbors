# K-Nearest-Neighbors
K Nearest Neighbors built in R.

This project has as gold the creation of a k-means function that allows the user to select a data base, the number of centers and the type of distance calculation in order to perform a simple clusterisation.
The steps on how it works are the following:

1. It is needed to set a directory where the data is uploaded.
2. It is require to load the library ggplot2
3. It is necessary to give value to the arguments of the function detailed below

Mykmean(x, y, Nclus, distance)

Where,
X= column in numeric format that correspond to x axis.
Y= column in numeric format that correspond to y axis.
Nclus = number of clusters needed during the process and for the final solution.
Distance= type of distances, the options are the following:
      a. Euclidean,
      b. SEuclidean,
      c. Manhattan or,
      d. Maximum

This function gives the next results:

1. Number of iterations needed in order to complete the require clusterisation
2. Record of the plots of each iteration.
3. List named “Results” which contains.
        a. Data frame called “Data” that contains the value of the x and y axis, its coordinates, the cluster group at which they were finally assigned, and the error measured as the distance from the centroid of the cluster.
        b. Data frame called “Clusters” that gives the final number of clusters and each coordinates in the plane.
        c. Data frame named “Error” which contains the measure of error at the end of each iteration.
        
The data selected for performing a demonstration on how this function works is the Iris data set.
