<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>K-means Clustering</title>
</head>
<body>

<h1>K-means Clustering</h1>

<p>K-means clustering is a popular unsupervised machine learning algorithm used for partitioning data into groups, or clusters, based on similarity. The algorithm aims to minimize the within-cluster variance, meaning that data points within the same cluster are as similar to each other as possible, while being as dissimilar as possible to data points in other clusters.</p>

<h2>How it Works</h2>

<ol>
    <li><strong>Initialization:</strong> Choose the number of clusters (K) and randomly initialize K centroids.</li>
    <li><strong>Assignment:</strong> Assign each data point to the nearest centroid, forming K clusters.</li>
    <li><strong>Update:</strong> Recalculate the centroids as the mean of all data points assigned to each cluster.</li>
    <li><strong>Repeat:</strong> Repeat steps 2 and 3 until convergence (when centroids no longer change significantly or a maximum number of iterations is reached).</li>
</ol>

<h2>Applications</h2>

<p>K-means clustering is widely used in various fields, including:</p>

<ul>
    <li><strong>Customer Segmentation:</strong> Grouping customers based on purchasing behavior.</li>
    <li><strong>Image Compression:</strong> Reducing the size of an image by clustering similar pixel values.</li>
    <li><strong>Anomaly Detection:</strong> Identifying outliers or anomalies in data.</li>
    <li><strong>Market Analysis:</strong> Analyzing market trends and segmenting products or services.</li>
</ul>

<h2>Advantages and Limitations</h2>

<p><strong>Advantages:</strong></p>

<ul>
    <li>Simple and easy to implement.</li>
    <li>Works well with large datasets.</li>
    <li>Fast convergence.</li>
</ul>

<p><strong>Limitations:</strong></p>

<ul>
    <li>Requires the number of clusters (K) to be specified in advance.</li>
    <li>Sensitive to the initial placement of centroids, which can result in different solutions.</li>
    <li>Assumes clusters are spherical and of similar size.</li>
    <li>May converge to a local optimum instead of the global optimum.</li>
</ul>

<h2>Example</h2>

<p>In this example, we apply k-means clustering to a dataset of iris flowers to group them into different species based on their sepal length and width.</p>

</body>
</html>
