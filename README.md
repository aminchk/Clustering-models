# Clustering-models : 

Clustering aims to divide a data set into different homogeneous groups. The objective of clustering is to 
construct classes automatically based on the available instances (or observations).

![image](https://user-images.githubusercontent.com/121105876/235478496-1152e343-5100-4723-b04e-e9b822fcdc96.png)

Use of four clustering methods: 

KMeans: It is easy to implement, and applicable to any type and size of data. However, the number of classes must be fixed a priori, and the final result depends on the initial (random) selection of class centres.

Hierarchical Ascending Classification (HAC): The main advantage is that the progressive clustering of data and the increase in dispersion within a group produced by aggregation can be visualised using the dendrogram. It is not necessary to define the number of classes in advance, and the dendrogram gives an idea of the appropriate number of classes into which the data can be grouped.

Mixed classification: Combines the two previous methods and reduces their disadvantages. It consists of three steps: application of the K-Means method, then a hierarchical ascending classification applied on the centroids obtained in the first step and finally application of a K-Means algorithm using the centroids obtained in the CAH step as initial centroids.  

Mean Shift Algorithm: This technique consists of transforming a digital image A (sequence of bits) into a second B (shorter sequence of bits) that can restore the same or similar information, using a decompression algorithm.

Datasets used (found on the internet): "Ruspini.csv", "fromages.txt" and 
