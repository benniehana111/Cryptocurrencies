# Cryptocurrencies

## Overview

This analysis uses unsupervised machine learning to analyze a dataset of 1252 cryptocurrencies from cryptocompare.com. The dataset includes 1252 cryptocurrencies; the variables include the currency name, the algorithm type, if the currency is traded (T/F), the proof type, total coins mined, and total coin supply. This dataset is analyzed using principal component analysis (PCA) and the K-means algorithm.

## Results

The dataset was cleaned, removing cryptocurrencies with missing variables and those with zero coins mined, reducing the dataset to 532 cryptocurrencies. Clustering was done using the algorithm, proof type, total coins mined, and total coins supply variables.

PCA analysis identified three principal components (PC1, PC2, PC3) in the data.

K-means analysis using an elbow curve selected four centroids for clustering the data.

A 3-D visualization of the principal compoents showed two dense clusters along the PC2 axis (one in the negative range [0 to -3, and one in the positive range [0 to +3]) with PC1 and PC3 values of zero. A third cluster centered on a PC2 value of 3, with PC3 values of 10-20 and PC1 values of zero. The fourth cluster comprised a single outlier, with PC2 of 1.5, PC3 of zero, and PC1 of 35.

![image](https://github.com/benniehana111/bikesharing/blob/main/3D%20cluster%20analysis.png)

## Summary

The results of this analysis identified three principal types of cryptocurrencies defined by principal components. Given the limited number of variables employed (four), a more detailed analysis would likely associate the principal components with individual variables allowing a more descriptive classification scheme.
