# Meat Quality Assessment - Deep Learning Project
#### Aqsa Anwar
**[GitHub Repository](https://github.com/aqsaakhan/CSCA-5642-Introduction-to-Deep-Learning-Final-Project)**

## 1. Introduction
This project serves as the final project for my **['Introduction to Deep Learning'](https://github.com/aqsaakhan/CSCA-5642-Introduction-to-Deep-Learning-Final-Project)** course. Since, meat assessment is a critical process to ensure comsumer's safety and product quality in the food industry, there is a dire need for a model to accurately classify the meat if it's fresh of spoiled. The traditional manual methods of meat quality assessments are time-consuming and are more prone to human error. Traditional computer vision techniques struggle with the subtle visual differences between fresh and spoiled meat. In this project, we aim at building a deep learning model capable of classifying meat images as either fresh or spoiled.

### 1.1. Dataset Overview
For this project I have selected the **[Meat Quality Assessment Dataset from Kaggle](https://www.kaggle.com/datasets/crowww/meat-quality-assessment-based-on-deep-learning)** This dataset was created by O. Ulucan, D. Karakaya, and M. Turkan from the Department of Electrical and Electronics Engineering at Izmir University of Economics in Turkey. These images were collected using an IP camera in a supermarket in Izmir, Turkey, as part of a university-industry collaboration project.

The original purpose of this dataset was to develop a meat quality assessment system based on deep learning techniques. The work was published in the 2019 Innovations in Intelligent Systems and Applications Conference (ASYU).

The dataset consists of 1896 high-resolution images (1280x720 pixels) equally divided between fresh and spoiled meat samples.

- Total images: 1896
- Fresh meat images: 948
- Spoiled meat images: 948
- Image dimensions: 1280x720 pixels

### 1.2. Project Objectives

The objective of this project is to develop a deep learning model that can accurately classify images of meat as either fresh or spoiled. This is a binary image classification problem where the input is a high-resolution (1280x720) image of a meat sample, and the output is a prediction of whether the meat is fresh or spoiled.

I'll perform the following key steps:

- **Data Loading and Initial Exploration:** In this step, we'll load our dataset and do some initial inspection to better understand our data
- **Exploratory Data Analysis:** Then We'll perform EDA to gain insights about data; we'll analyze the class distributions and RGB channel distributions.
- **Data Preprocessing:** This step will envolve data cleaning if requirede, and image preprocessing.
- **Data Augmentation:** Then we'll create data generator for augmentation.
- **Model Development and Evaluation:** We'll develop and evalute the performance of various models including:
    - MobileNetV2
    - Custom CNN
    - ResNet
- **Model Performace Comparison:** In this step we'll compare performace of the models and identify the best perfoming model for our problem.
- **Hyperparameter Tuning:** Then we'll perform hyperparameter tuning on the best performing model to further optimize its perfomance.
- **Final Comparison:** Lastly, we'll compare the performance of tuned vs not-tuned model.
- **Results and Analysis and Conslusion:** Then we'll conlude our project findings and analysis.
