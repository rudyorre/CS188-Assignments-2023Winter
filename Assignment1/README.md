# Assignment 1

Welcome to our first assignment!

### Access
You can open the assignment in Colab by clicking [here](https://colab.research.google.com/drive/1NawPMGJXVIefsV86Q1zyjiq3FqlNVv-U?usp=sharing), or you can use the downloaded version of the notebook [(23W_CS188_Assignment1.ipynb)](./23W_CS188_Assignment1.ipynb).

### Goals
In the first assignment, you will learn:
* How to prepare data for image classification
* How to use Google Colab
* How to implement a k-Nearest Neighbor (kNN) classifier
* How to implement a linear/logistic/softmax regression classifier

Free free to raise issues in the Piazza forum if you find any bugs or have any questions about the assignment. 

Please do not directly copy code from other sources.

Please **do not use any Code AI** to derive the answers to the questions.

This assignment is due on **Sunday, Jan 29**.

❗**Once you have finished all the questions, it will still take approximately *30 minutes* to re-run the entire notebook in order to prepare the submission version. Make sure to allocate enough time for this task and start early.**

---

### Overview

In this assignment, you will be working with the [MiniPlaces dataset](https://github.com/CSAILVision/miniplaces), a small-scale version of the [Places2 dataset](http://places2.csail.mit.edu/), which is a large-scale dataset of scene images (10+ million images) with a wide variety of real-world environments (400+ unique scene categories). The MiniPlaces dataset is a subset of the [Places2 dataset](http://places2.csail.mit.edu/) and contains 100,000 images for training, 10,000 images for validation, and 10,000 images for testing, each of which has been annotated with one of 100 different scene categories. These images are divided into three folders: train, val, and test. 

The MiniPlaces dataset is a useful resource for developing and testing image classification models, particularly those that are designed to recognize different types of environments and scenes.

Your task for this assignment is to create two new datasets called *TinyPlaces-Binary* and *TinyPlaces-Multiclass* from the MiniPlaces dataset. Both datasets should be much smaller in size than the original MiniPlaces dataset (more details later).

In addition to creating the TinyPlaces datasets, you will also need to implement and evaluate the performance of the following classifiers on both datasets:
* k-Nearest Neighbor (kNN) Classifier
* Linear/logistic/sofrmax Regression Classifier

---
Good luck with your work!