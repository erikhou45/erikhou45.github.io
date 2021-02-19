---
title: "Edge Facial Recognition Doorbell"
date: 2020-08-20T15:34:30-04:00
categories:
  - UC Berkeley Academic Project
tags:
  - computer vision
  - mobile development
  - deep learning
  - Docker
---

Applied transfer-learning to facial image encoding model on edge device to enhance performance and user privacy.

## Description

The project is focused on applying transfer learning to a pre-trained neural network at the edge in order to build a customized facial recognition system that can be applied used for smart doorbells. The benefit of transfer learning at the edge is that user-specific data and model wouldn't need to be uploaded to the cloud since uploading sensitive user data to the cloud could be a security concern.

We used FaceNet, a neural network developed in 2015 by reserachers at Google for face recognition as our base model and performed the transfer learning on Nvidia Jetson TX2. The result is an exciting proof of concept because it demonstrates that it is possible to avoid cloud training for detecting known user identities, allowing facial recognition to be deployed securely and avoiding the risks of transmitting user identities to the cloud.

## Outcome

The resulting model achieved over 99% accuracy on recognizing user identities even in the case of images with high degrees of light or shadow.

## Techniques
* supervised learning (classification) with SVM
* facial recognition
* image embedding with FaceNet
* transfer learning
* containerization
* model deployment at the edge

## Tools
* Keras
* sckit-learn
* Docker
* Nvidia TX2

## More Information
More information can be found at the following links:

* [Project White Paper](https://github.com/adamxjohns/w251project/blob/master/w251%20final%20project%20report%20final.pdf)

* [Project Repository](https://github.com/adamxjohns/w251project)



