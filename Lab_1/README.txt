Siddh Bhagat

TODO: 
Lab Assignment 1: Modeling Neural Networks

Working Arrangements

You may complete this assignment individually or in a group of up to 2 students. If you are working with a partner, you must submit your report individually. Write down the name of your partner in the report.
Goals

In this assignment you will practice writing back propagation code and training Neural Networks and Convolutional Neural Networks. The goals of this assignment are as follows:

Understand Neural Networks and how they are arranged in layered architectures.
Understand and be able to implement (vectorized) back propagation.
Implement various update rules used to optimize Neural Networks.
Implement Batch Normalization and Layer Normalization for training deep networks.
Implement Dropout to regularize networks.
Understand the architecture of Convolutional Neural Networks and get practice with training them.
Gain experience with a major deep learning framework, such as TensorFlow or PyTorch.
Learn about Pruning techniques and apply it into a Tensorflow or Pytorch model
Setup

You can work on the assignment in one of two ways: remotely on Google Colaboratory or locally on your own machine. Regardless of the method chosen, ensure you have followed the setup instructions before proceeding.

Option A: Google Colaboratory (Recommended)

Download. Download the starter code containing Colab notebooks.

If you choose to work with Google Colab, please familiarize yourself with recommended workflow from the setup instructions.

Note. Make sure you are periodically saving your notebook (File -> Save) so that you don’t lose your progress if you step away from the assignment and the Colab VM disconnects.

Once you have completed all Colab notebooks except collect_submission.ipynb, proceed to the submission instructions.

Option B: Local Development

Download. Download the starter code containing jupyter notebooks.

Install Packages. Once you have the starter code, activate your environment (according to the setup instructions) and run pip install -r requirements.txt.

Retrieve CINIC-10. Next, you will need to make sure you have the modified CINIC-10  dataset. Go into the ece662/datasets and a folder called cinic-10-small-npz should be in there with 3 .npz files (train.npz, test.npz and valid.npz)

Start Jupyter Server. After you have the CINIC-10 data, you should start the Jupyter server from the assignment1 directory by executing jupyter notebook in your terminal.

Complete each notebook, then once you are done, go to the submission instructions.

 

Q1: Fully-connected Neural Network (20 points)

The notebook Q1-FCNetworks.ipynb you will implement fully-connected networks of arbitrary depth.

Q2: Batch Normalization (10 points)

In notebook Q2-BatchNorm.ipynb you will implement batch normalization and use it to train deep fully-connected networks.

Q3: Dropout (10 points)

The notebook Q3-Dropout.ipynb will help you implement Dropout and explore its effects on model generalization.

Q4: Convolutional Networks (30 points)

In the IPython Notebook Q4-CNNs you will implement several new layers that are commonly used in convolutional networks.

Q5: PyTorch / TensorFlow on CINIC-10 (10 points)

For this last part, you will be working in either TensorFlow or PyTorch, two popular and powerful deep learning frameworks. You only need to complete ONE of these two notebooks. You do NOT need to do both, and we will not be awarding extra credit to those who do.

Open up either Q5-Pytorch.ipynb or Q5-Tensorflow.ipynb. There, you will learn how the framework works, culminating in training a convolutional network of your own design on CINIC-10 to get the best performance you can.

 

Q6: Pruning Pre-trained Model (20 points)

The notebook Q6-Pruning.ipynb  will introduce you to two different pruning types and have you apply it in a pre-trained model.