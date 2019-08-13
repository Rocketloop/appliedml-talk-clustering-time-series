# Clustering Time Series

This is a GitHub repository to host the files from the presentation at the Meetup **Applied Machine Learning Rhine-Main #1**. 

We provide you two notebooks: 

    1. How to do Time Series clustering and how to prepare data for it. 
    2. How to calculate features from time series. 
    
We use *Google Trends* data for this purpose, which is also provided. Running the notebooks requires the following packages to be installed: 

pandas, numpy, matplotlib, warnings, IPython, fbprophet, stldecompose, scipy, pyclustering, sklearn, fastdtw, re, statsmodel and nolds. 

## Clustering

Initially, we clustered data in 3 ways: 

    1. On Time Series features, using Euclidean Distance
    2. On Time Series data, using Euclidean Distance
    3. On Time Series data, using DTW Distance
    
From the inputs received and conversations during the Meetup, we decided to implement **PCA** instead of feature extraction to reduce our dimension. Thus, we have a fourth kind of clustering now, 

    4. On PCA-modified Time Series, using Euclidean Distance 
    
The notebook has been updated to show results from it. 

## Coda

We invite you to run this notebook yourself and study the code to understand how we implemented our ideas. But most importantly, we want you to experiment with the parameters and ideas in this notebook. For example, you could experiment with the number of clusters, number of PCA dimensions, type of PCA kernel, adding more time-series features and so on. 

If you have any suggestions to optimize this code, ideas on how to generate better clusters or simply have questions on this topic, feel free to write to us at <applied-ml@rocketloop.de>. 