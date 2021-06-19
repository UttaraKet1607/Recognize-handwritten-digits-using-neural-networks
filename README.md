# Recognize-handwritten-digits-using-neural-networks

## About the Dataset
The MNIST dataset is one of the most common datasets used for image classification and accessible from many different sources. In fact, even Tensorflow and Keras allow us to import and download the MNIST dataset directly from their API. There is no need of downloading the dataset separately.

The MNIST database contains 60,000 training images and 10,000 testing images taken from American Census Bureau employees and American high school students.

## Details of the Model
We will build our model by using high-level Keras API which uses TensorFlow on the backend. We will be using the the Sequential Model from Keras and add Conv2D, MaxPooling, Flatten, Dropout, and Dense layers. In addition, we have used Dropout layers fight with the overfitting by disregarding some of the neurons while training while Flatten layers flatten 2D arrays to 1D arrays before building the fully connected layers.

The information about all these layers and structure of the CNN model can be found here: https://drive.google.com/file/d/1Qp6rV9yLGyj_S8_MlAu4XLJybuLA3cII/view?usp=sharing 
