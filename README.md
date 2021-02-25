# Classifying-Facial-Attributes-and-Accessories-with-LeNet-Project-based-AI-course

This repo is the part of project assigned on Aritificial Intelligence course (109.1【工管系】IM6507701 人工智慧 Artificial Intelligence), Taiwan Tech.

The topic is a Classifying Facial Attributes and Accessories with LeNet (Not pubblishing)
This problem will teach you to create datasets by using Roboflow and training dataset from your created dataset.

Dataset is gathering from google (might be license some image)
We have arranged three groups for single-label, three groups for dual-label and one group for multi-label (three labels)
by there are three labels i.e. mustache, wearing hat and wearing eyeglasses.


# Environment
The code is developed using python > 3.6 and training is able on both CPU/GPU.

# Quick Start
Installation
  1. Install Tensorflow >= v2.0
  2. Also, Colab-Notebook and/or Jupyter-notebook are available for training and testing.



# Directory and how to train

```
$ Dataset
|
|(single-label)
├── 001 (36 ea.) - mustache
├── 010 (60 ea.) - wearing hat
|
|(dual-label)
├── 011 (32 ea.) - mustache + wearing hat
├── 101 (47 ea.) - mustache + wearing eyeglasses
├── 110 (19 ea.) - wearing eyeglasses + hat
|
|(multi-label)
└── 111 (15 ea.) - mustache + wearing eyeglasses + hat
```

You have to use Roboflow to create dataset (Amount of data propotional for implementing in training, validating, and testing set, you can define by yourself on website).
https://roboflow.com/

How to create dataset(limited 1000 images per month per dataset)
https://docs.roboflow.com/adding-data

You can train and inference samples on cnn-single-multi-label.ipynb file.
-  cnn-single-multi-label.ipynb

```
Whole project
$ root
|
├── Datasets (Folder)
├── Assignment 2 (PDF problem)
└── cnn-single-multi-label.ipynb
```
