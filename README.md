
# K-nearest-neighbors

A algorithm can be apply in both Classification cases and Regression cases. 

It is called lazy learning algorithm because of it does not contain any training stage just using the provided data and major voting to get information.

## Brute force KNN
- Calculate distance from point need to check to other in dataset
- Select K nearest data points
- For regression: averaging k nearest data points to get value
- For classification: using major voting to get the class of data point

## KD Tree KNN
- Split the data into regions by median values coordiantes
- Create binary tree where each node is a region

## Ball Tree KNN
- Split the data into hypershphere
- Each node is a ball containing a subset of data
- Choose a centroid and radius to enclosed points
