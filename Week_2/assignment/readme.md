# assignment 2
## download data
To use the dataset, you should move the dataset to  `assighment\camalab\dataset` or change the path in the code.
### cifar-10
[The CIFAR-10 dataset](http://www.cs.toronto.edu/~kriz/cifar.html) consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images. 
[download](http://www.cs.toronto.edu/~kriz/cifar-10-python.tar.gz)

### Mnist
[The MNIST database](https://github.com/WenDesi/lihang_book_algorithm/raw/master/data/train.csv) of handwritten digits, has a training set of 60,000 examples, and a test set of 10,000 examples. 
[download](https://github.com/WenDesi/lihang_book_algorithm/raw/master/data/train_binary.csv)

## Q1: k-Nearest Neighbor classifier
The Jupyter Notebook **knn.ipynb** will walk you through implementing the kNN classifier.

dataset: CIFAR-10

- Implement k-NN.
- Speed up distance matrix computation in k-NN by using partial vectorization.
- Determine the best value of the hyperparameter 'k' with cross-validation.

We use raw pixel values in this exercise, we will use other features in Q2.

For more efficient code execution in this exercise, we use 5000 images for train and 500 images for test. And you can change it by yourself.

After you ensure that your code is true, you can implement the algorithm on the whole dataset. But it's not recommended. Only if you have done some feature extraction to reduce the dimension.

## Q2: Logistic Regression classifier
The Jupyter Notebook logistic_regression.ipynb will walk you through implementing the classifier.

dataset: MNIST

You should choose and extract features on your own.
- Binary classification with Logistic Regression classifier.
- Multiclass classification with Logistic Regression classifier and "one vs all".

## Q3: Decision Tree classifier
You will complete the mission on your own in the Jupyter Notebook decision_tree.ipynb.

dataset: MNIST

- Binary classification or Multiclass classification.

## Q4: Optional
This is your chance to show off! Try to get higher accuracy.

Design and implement a new type of feature and select an algorithm, and use them for image classification on CIFAR-10. 




