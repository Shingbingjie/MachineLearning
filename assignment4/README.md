# K-means Clustering
This exercise focuses on implementing the K-means clustering algorithm and using it for image compression. The exercise is divided into several parts:

Finding closest centroids: Implementing the function find_closest_centroids, which assigns each data point to the closest centroid.

Computing centroid means: Implementing the function compute_centroids, which computes the mean of the points assigned to each centroid.

K-means on a sample dataset: Running the K-means algorithm on a toy 2D dataset to understand how it works.

Random initialization: Exploring how random initialization affects the outcome of the K-means algorithm.

### Image compression with K-means:
* Loading an image and visualizing it.
* Preprocessing the image by reshaping it into a 2D matrix of pixel colors.
* Running K-means on the image to find the 16 colors that best group the pixels.
* Visualizing the colors and centroids.
* Assigning each pixel to its closest centroid to compress the image.
* Reconstructing the image based on the centroid assignments to see the compression effects.
