# Preliminary Analysis of Integrating Feature Pyramid Network on MobileNets Architecture

This work is is submitted as part requirement for the MSc degree in Machine Learning at University College London

# Abstract

One of the most problematic obstacles that obstruct the deployment of Deep Learning to real-time application is its heavy memory requirement and computational cost.

In attempt to address the problem, several lightweight models have been developed, notably the MobileNets family and Single Shot Detector (SSD). The combination of these two models achieved a remarkable performance on public datasets, showing its great potential to be a real-time object detector. However, SSD-based model still struggles with detecting
small objects in a given image.

This dissertation investigates the use of Feature Pyramid Networks (FPN) for generating rich informative multiscale feature maps in MobileNetV2, using its high resolution layers. Our hypothesis is by putting high resolution feature maps into the detection task, one could ultimately recognise small objects. Our experimental results showed that this is not the case, nevertheless, the overall performance of our model is better than the baseline with a significant reduction in running time.

# Installation

The code was inherited from the Tensorflow Object Detection API. We acknowledge the Tensorflow team who has created and currently manages this tool.

Please refer to their instruction of how to install the API: https://github.com/ddhgiang/models/blob/master/research/object_detection/g3doc/installation.md. 

The instruction for training and inference task is also given: https://github.com/ddhgiang/models/blob/master/research/object_detection/g3doc/running_locally.md

# 
