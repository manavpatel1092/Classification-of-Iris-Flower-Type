# Iris-Flower-Type-Classification using MLP 

Overview of dataset:

The Iris Dataset has samples of three different types of iris flowers (Iris setosa, Iris virginica and Iris versicolor) with varying physical qualities and it consists of the following attributes:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The dataset can be found on UCI repository https://archive.ics.uci.edu/ml/datasets/iris.
The dataset can also be accessed directly through the python notebook by running the following code:
```
import sklearn
from sklearn import datasets
iris = datasets.load_iris()
```
Task:
- We run a multilayer perceptron (feed forward neural network) with two hidden layers and rectified linear nonlinearities on the iris dataset using the keras sequential interface to classify the 3 different types of iris flowers. 
- Then using GridSearchCV with StratifiedShuffle Split we tune the regularization strength and the number of hidden layers for the model.
- The resulting classification model has an test set accuracy of 94% with a loss of 20%.
