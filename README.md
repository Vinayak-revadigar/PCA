# PCA
Performing PCA on Bangalore house pricing data to reduce dimensionality

Process Flow
1. Load the necessary libraries and import the dataset.
2. Separate the target variable (price) from the features.
3. Standardize the features using 'StandardScaler' to ensure they have zero mean and unit variance.
4. Perform PCA using 'PCA()' on the standardized features.
5. Calculate the explained variance ratio and cumulative explained variance.
6. Plot the scree plot to visualize the cumulative explained variance as a function of the number of principal components.
7. Determine the number of components to retain based on the desired variance threshold.
8. Perform PCA again with the selected number of components.
9. Calculate the loading scores (component loadings), which represent the contribution of each feature to each principal component.
10. Print the loading scores to see how each feature loads onto each principal component.
11. Define component names if you want to rename the components based on the features with high loadings.
12. Calculate the variance retained after performing PCA.
13. Print the explained variance ratio and the retained variance.
