# Principal-Component-Analysis
PCA from scratch on IRIS dataset

Procedure:

- Standardize the Data: Ensure that each feature has zero mean and unit variance.
- Compute Covariance Matrix: Calculate the covariance matrix to understand the data's variance structure.
- Compute Eigenvalues and Eigenvectors: Derive the eigenvalues and eigenvectors from the covariance matrix.
- Sort Eigenvalues and Select Principal Components: Sort eigenvalues in descending order and choose the top k eigenvectors corresponding to the k largest eigenvalues.
- Transform the Data: Project the data onto the selected principal components to obtain the reduced dataset.
