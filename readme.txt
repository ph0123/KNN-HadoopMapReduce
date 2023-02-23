The code is modified from https://github.com/ShamithaUdupa/K-Nearest-Neighbour-in-Hadoop


Run this code: 
    hadoop jar <jarfile> knn <HDFS testing data> <HDFS training data> <HDFS outpur folder> <number of neighbors - k> <NumReducer>
Example: 
    hadoop jar knn.jar knn /tmp/KNN-root/input.txt /tmp/KNN-root/iris2.txt /tmp/KNN-root/output 1 1
