# Dimensionality Reduction
MNIST is a computer vision dataset, classic example is the set of handwritten digits
- digit can be represented as a point in 784-dimensional space
- MNIST digits intuitively live in a lower dimensional subspace than 784
- goal of dimensionality reduction is to think of other ways to encode information in lower dimensions, losing only irrelevent information -- [source](http://colah.github.io/posts/2014-10-Visualizing-MNIST/)

### PCA, principal component analysis
applying orthogonal tranformations to convert a set of correlated variables into a set of linearly uncorrelated variables, called principle components
- orthogonal transformations preserve euclidean distance between points, so in 2&3-dimensional euclidean space, rotations, reflections or improper rotations (combination)
- number of principle components is less than or equal to number of original variablesx