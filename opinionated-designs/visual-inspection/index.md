---
layout: home
title: Visual Inspection
nav_order: 2
has_children: true
parent: Opinionated Designs
---

# Visual Inspection

![MANUela Logo](https://github.com/sa-mw-dach/manuela/raw/master/docs/images/logo.png)

# Visual Inspection on OpenShift

This project is a sibling of the [MANUela](https://github.com/sa-mw-dach/manuela) IoT Edge demo project. It shows an exemplary solution blueprint for computer vision visual inspection in manufacturing. 

The demonstrator contains 2x3 parts. The ML infrastructure sections covers use cases of MLOps and DevOps engineers.
Data and ML engineers would focus on the ML application tasks.


## ML Infrastructure
1. [Deploy and manage the Computer Vision Annotation Tool (CVAT) on OpenShift Virtualization.](https://github.com/sa-mw-dach/manuela/raw/master/docs/cvat-cnv.md#install-cvat-in-a-openshift-virtualization-virtual-machine)
1. [Jupyter notebook as a Service with OpenDateHub. Model training in K8S jobs.](ml/README.md)
1. [Serverless (knative) images processing on OpenShift.](https://github.com/sa-mw-dach/manuela/raw/master/docs/runtime.md#installation)

## ML Application
1. [Image labeling with the Computer Vision Annotation Tool.](docs/cvat-cnv.md#image-labeling-with-the-computer-vision-annotation-tool)
1. [Training of a computer vision AI model for detecting anomalies in images (Darknet YOLOv4).](ml/README.md)
1. [Real-time manufacturing defect detection with TensorFlow based inferencing.](docs/runtime.md#demo-execution)


![visual-inspection](https://raw.githubusercontent.com/sa-mw-dach/manuela-visual-inspection/main/images/manu-vi.gif)


*ATTRIBUTION: Paul Bergmann, Michael Fauser, David Sattlegger, Carsten Steger. [MVTec AD](https://www.mvtec.com/company/research/datasets/mvtec-ad) - A Comprehensive Real-World Dataset for Unsupervised Anomaly Detection; in: IEEE Conference on Computer Vision and Pattern Recognition (CVPR), June 2019*