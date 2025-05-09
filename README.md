Project Overview
This project aims to develop a machine learning model to assist in the early detection of Parkinson’s Disease (PD) using spiral drawing data. The model leverages Convolutional Neural Networks (CNN) and Residual Networks (ResNet) to classify spiral drawings, which are commonly used in clinical assessments for Parkinson’s patients. By detecting motor irregularities like tremors and bradykinesia, this system aims to provide a reliable, non-invasive, and scalable diagnostic tool.

Problem Statement
Parkinson’s Disease primarily affects motor function, leading to issues such as tremors, slow movement, and rigidity. Early diagnosis of PD is crucial to improving treatment outcomes, but most patients are diagnosed in later stages, which significantly hampers therapeutic interventions. This project addresses the need for early diagnosis by automating the analysis of spiral drawings to detect PD symptoms at an earlier stage.

Objective
The main objective of this project is to:

Develop a machine learning model capable of classifying Parkinson's-related motor dysfunctions using spiral drawing images.

Compare the performance of CNN and ResNet in detecting subtle features within spiral drawings that could indicate Parkinson’s Disease.

Create a reliable, scalable, and easy-to-use tool for early detection of Parkinson's Disease to aid healthcare professionals.

Model Description
The project utilizes two deep learning architectures:

Convolutional Neural Network (CNN): A simple yet powerful model for image classification, designed to capture spatial hierarchies of features in spiral drawings.

Residual Networks (ResNet): A more advanced architecture that helps mitigate the vanishing gradient problem, allowing the model to learn deeper, more complex patterns in the spiral data.

Dataset
The dataset consists of spiral drawings from Parkinson’s Disease patients, along with control group data. These images are preprocessed for noise removal, normalization, and resizing before being fed into the model.

Technologies Used
Python

TensorFlow/Keras

OpenCV (for image preprocessing)

NumPy, Pandas (for data manipulation)

Matplotlib (for visualization)
