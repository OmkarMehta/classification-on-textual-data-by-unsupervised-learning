# Classification-on-textual-data-by-unsupervised-learning
Unsupervised learning

The main aim of this project would be to classify the documents into 20 groups without using labels. We will use K-means clustering for this. We will also evaluate the performance of the clustering.

K-means clustering involves two steps which are repeated simultaneously until convergence:
1. Reassign each data point to the cluster whose centre is nearest to it.
2. Place the centroids of the cluster to the mean of the data points that are currently in the cluster.

We work with "20 Newsgroups" dataset. It is a collection of approximately 20,000 documents, partitioned (nearly) evenly across 20
different newsgroups, each corresponding to a different topic. Each topic can be viewed as a "class".

For the sake of understanding, we will use two classes: 1. Computer technology: ['comp.graphics','comp.os.ms-windows.misc','comp.sys.ibm.pc.hardware','comp.sys.mac.hardware']
2. Recreational Activity: ['rec.autos','rec.motorcycles','rec.sport.baseball','rec.sport.hockey']

We will use all the documents in these two classes and without using the labels, try to retrieve the known classes.
We would like to evalulate how purely the a priori known classes can be reconstructed through clustering.

