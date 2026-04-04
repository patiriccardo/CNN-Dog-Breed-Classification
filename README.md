# CNN Regularization & Hyperparameter Tuning for Image Classification

## Project Overview
This project focuses on the classification of 120 different dog breeds using the **Stanford Dogs Dataset** (20,580 images). The main objective was to explore and implement advanced **regularization techniques** to overcome overfitting and improve the model's ability to generalize on unseen data.

## Key Features & Methodologies
* **Deep Learning Framework:** Built with **TensorFlow** and **Keras**.
* **Overfitting Mitigation:** Systematic application of **Data Augmentation**, **Dropout** layers, **Early Stopping**, and **L2 Regularization**.
* **Hyperparameter Optimization:** Utilized **Keras-Tuner** to automate the search for optimal learning rates and architectural configurations.
* **Model Evaluation:** Detailed analysis of training/validation loss and accuracy curves to identify the "Robust Fit" point.
* **Transfer Learning:** Comparative analysis using **EfficientNetB7** to establish a performance baseline.

## Dataset
The [Stanford Dogs Dataset](http://vision.stanford.edu/aditya86/ImageNetDogs/) contains images of 120 breeds from around the world, based on ImageNet.

## Project Structure
* `StanfordDogs.ipynb`: Full pipeline from data loading to model evaluation.

## Main Results
The project successfully demonstrated how regularization can bridge the gap between training and validation accuracy, moving from an overfitted model to a more stable and generalizable architecture.

---
*Developed as part of the "Metodi Informatici per Statistica e Data Science" course @ University of Padua.*
