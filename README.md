# Perceptron and SVM implementation

In this project, the Pegasos algorithm for training support vector classifiers was implemented using OOP including the implementation of its hinge loss function for sentiment data classification of customer reviews on music albums as positive or negative. In addition, the Logistic regression model was implemented using OOP including the log loss function on the same data.

Moreover, the bottlenecks in the code are the linear algebra operations: computing the dot product, scaling the weight vector, and adding the feature vector to the weight vector, therefore, they were tackled by
- Replacing orinary numpy mathematical operations with linear algebra operations from [Scipy](https://docs.scipy.org/doc/scipy/reference/linalg.blas.html).
- Using sparse vectors.
- Replacing the vector scaling operations with blas functions.
