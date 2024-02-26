# Hand Writing Recognition Using Convolutional Neural Networks

## Introduction
This CNN-based model for recognition of hand written digits attains a validation accuracy of 99.2% after training for 12 epochs. Its trained on the MNIST dataset on Kaggle.

![1]![image](https://github.com/9RP6/Handwritting-recognization/assets/96533361/84c7b9f1-5f22-4504-b09a-a66394882626)

## Usage
The model architecture and weights are saved in the files `model_architecture.json` and `model_weights.h5`. Note that these weights are compatible only with the Tensorflow backed.

To train the model run `train.py`. The file `test.py` generates a file `predictions.csv` which contains the predicted labels to the images in the test set. This file can be used for submission at Kaggle. `display_random.py` displays 25 random images from the test set along with their predicted labels.

![2]![image](https://github.com/9RP6/Handwritting-recognization/assets/96533361/5a245468-18a8-48b0-ba90-9737634786b2)


## Requirements

* Python 2.7
* [Tensorflow](https://www.tensorflow.org/)
* [Keras](https://keras.io/)
* [h5py](http://www.h5py.org/)
* numpy
* matplotlib
* pandas

## Dataset

* The model is trained on the MNIST dataset downloaded from [Kaggle](https://www.kaggle.com/c/digit-recognizer). 

* The file `train.csv` contains pixel intensity values as flattened vectors for 42000 images and their corresponding labels. Similarly, `test.csv` has pixel intensity values for 28000 unlabelled images.

## The Model

<img src="https://github.com/Shobhit117/digit-recognizer/blob/master/model.png">


