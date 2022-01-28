## Milestone: PCA

_This Milestone will allow you to run full PCA_
_Depends: MATRIX_OPERATIONS_

- Which library provides a way to compute `full PCA/SVD`?
- Load the dataset `######.csv` as a matrix.
- What are the dimensions of your data matrix?
- Compute PCA on it (use scale and centering equal to TRUE). PCA will result in 2 matrices and 1 vector.
- Check the dimensions of the matrices and vectors from PCA.
- How many principal components do we have for this dataset?
- Where is stored the variance captured by each PC?
- What does the matrix samples-by-PCs mean?
- What does the matrix features-by-PCs mean?

- What happens if you `transpose the data matrix` before computing PCA?
- Check the dimensions of the resulting matrices and vectors from PCA.
- How many principal components do we have for this dataset?
- Where is stored the variance captured by each PC?
- What does the matrix samples-by-PCs mean?
- What does the matrix features-by-PCs mean?


## Milestone: PCA_2

_This Milestone will allow you to run truncated PCA_
_Depends: PCA_

- In the method above, we used a library to compute `full PCA/SVD`. However, in many cases computing all PCs takes a long time, so to compute only the first say `20` PCs, we can compute a `randomised truncated PCA/SVD`. Which library provides this PCA implementation?
- Load the dataset `######.csv` as a matrix.
- What are the dimensions of your data matrix?
- Compute PCA on it (use scale and centering equal to TRUE). PCA will result in 2 matrices and 1 vector.
- Check the dimensions of the matrices and vectors from PCA.
- How many principal components do we have for this dataset?
- Where is stored the variance captured by each PC?
- What does the matrix samples-by-PCs mean?
- What does the matrix features-by-PCs mean?
- What is the advantage of running truncated PCA instead of full PCA?


## Milestone: PCA_3

_This Milestone will allow you to get a deeper understanding of the power of PCA_
_Depends: PCA_2_

- How can you recreate the original data from the matrices output from PCA?
- How can you project new points into a computed PCA? You can multiply the 
