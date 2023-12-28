# COVID-Resnet18

### Overview

Welcome to my Data Science Portfolio! This repository showcases my project, COVID-19 diagnosis through the analysis of CT images. 

### Description
In this project, we aim to leverage the power of deep learning for the crucial task of COVID-19 diagnosis through the analysis of CT images. We will develop a 2D Convolutional Neural Network (CNN) to discern patterns indicative of COVID-19 presence in the provided dataset.

We will construct a specialized 2D CNN tailored for the diagnosis of COVID-19 using chest CT images. The foundation of our CNN will be based on the Resnet-18 architecture, which will be adapted and fine-tuned to suit the specific requirements of binary classification, distinguishing between COVID-19 positive and negative cases. My approach involves training the CNN from scratch to ensure that the model learns intricate features and representations relevant to COVID-19 diagnosis. This process involves optimizing the network's parameters using the provided dataset and PyTorch dataloader. To enhance the interpretability and transparency of our model, we will employ two Class Activation Mapping (CAM) methods: GradCAM and EigenCAM. These visualization techniques will allow us to gain insights into the regions of the CT images that significantly contribute to the model's predictions. By visualizing the activated regions, we can better understand the decision-making process of the CNN and provide valuable insights for medical professionals.


GradCAM and EigenCAM will be employed to visualize the model's attention on specific regions of the input images. These visualizations serve as valuable tools for understanding the decision-making process of the CNN and can aid in the validation and interpretation of the model's predictions.

### Expected Outcomes:

A trained 2D CNN capable of accurately classifying COVID-19 cases from CT images. Visualization of model insights using GradCAM and EigenCAM, providing transparency into the decision-making process. A comprehensive understanding of the model's performance and its potential applications in the diagnosis of COVID-19. This project aligns advanced deep learning techniques with medical diagnostics, contributing to the ongoing efforts to combat the global COVID-19 pandemic.