# Adversarial Reprogramming

This repository is an attempt to implement **Adversarial Reprogramming** in Keras. 

* G. Elsayed, I. Goodfellow, J. Sohl-Dickstein *Adversarial Reprogramming of Neural Networks* ([PDF](https://arxiv.org/pdf/1806.11146.pdf)) 

Here, Inception V3 model is reprogrammed for MNIST classification.

The code is tested on Keras 2.1.3 and Tensorflow 1.4.0

To train the model, run adversarial_reprogramming.py

The model achieves 92.88% training accuracy and 93.47% test accuracy. The trained weights can be downloaded using this [link](https://drive.google.com/file/d/1PUaoonDEdfseL9F0lFONrEDednB2KUCd/view).

![Alt text](imgs/4_new.png?raw=true "Title")

This image is classified as "hammerhead" by Inception V3 model with 0.9041 probability.


The imgs subfolder contains 10 images (one for each MNIST class) of adversarial program which gave the highest class probability. The file imgs.npy contains these 10 image arrays. 
