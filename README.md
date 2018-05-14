# ml-pca-pt2

Applying PCA: 
- Doing this in Python: can be done in plotly and/or scikit learn (both or tbd)
- There are as many PC’s as variables, discard the ones that contain the least information = the least variance = the PCs corresponding with the lowest eigenvalues! Decision rules:
    - Extract PCs until given percentage of variance explained
    - Retain PCs with a an eigenvalue (L) > 1
    - Scree plot
- Interpreting/labeling PCs
    - Idea of “loadings” → to what extent are original variables important for the PCs?
        - Loading = corr(X_i, PCj) = e_{ji} sqrt(L_j) when standardized variables are used
        - Useful for interpreting the meaning of PCs
    - Biplots: visual interpretation
