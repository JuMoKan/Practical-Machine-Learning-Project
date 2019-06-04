## K-Means
* senstitive to outliers --> K-medians, K-medoids (PAM, CLARA: PAM on samples)
* for categorical data: K-modes
* not suitable for non-convex shaped clusters --> density based, kernel k-means


## Hierarchical Clustering
* don't scale well
* can't undo a split / merge


## Alternative BIRCH : 
* sklearn: Birch does not scale very well to high dimensional data. 
As a rule of thumb if n_features is greater than twenty, it is generally better to use MiniBatchKMeans.

## Density and Grid-Based Clustering Methods
