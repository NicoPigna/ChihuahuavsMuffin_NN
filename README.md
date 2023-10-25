# ChihuahuavsMuffin_NN
A Machine Learning project: Neural Network structures to teach the AI to distinguish between a dog and a sweet.
In the code file some outputs are not shown as they were too long and made the file almost unreadable. Anyway everything is described in the report.

Abstract

In this report we present our project about neural networks. We are asked to use Keras, a Python library, to train different binary classifiers in order to distinguish between images of muffins and Chihuahuas from this data set (https://www.kaggle.com/datasets/samuelcortinhas/muffin-vs-chihuahua-image-classification). In particular, after the data preprocessing, i.e. converting images from JPG to grayscale pixel values and scaling them down, we are asked to:

1. experiment with at least 3 different architectures and training hyperparameters;
2. use 5-fold cross validation to compute the risk estimates;
3. discuss the obtained results, especially the influence of the choices of hyperparameters and network architectures on the cross-validated risk estimate.

Also, we have to use the zero-one loss to compute the cross-validated estimates.

Overall we follow the steps of the task trying to find the best model for our data. We start with a base multilayer neural network that we improve until we decide to move to a convolutional one that is more appropriate considering the data we have. We manage to achieve a test accuracy of more than 90% thanks to the final model.
