# RiceNet: A Deep Convolutional Neural Network Architecture for Rice Grain Classification

## Description

This repository contains the code and resources for a deep learning project focused on training a Convolutional Neural Network model for rice grain classification task. The model has been trained and evaluated, and this readme provides an overview of the process and results.

## Model Training and Checkpoint

The deep learning model was trained using rice grain images and images were augmented first, then the images were prepared into batches and resized. The training was performed using tensorflow framework.

During the training process, checkpoints were saved at regular intervals to keep track of the model's progress. The final trained model checkpoint is available in the repository. The saved checkpoint file is named **training_7** and can be found in the **"\code\training_7\training_7\cp.ckpt"**.

## Model Evaluation

To evaluate the trained model, the saved checkpoint was loaded, and **code\Data\Dataset\items_val_test_set\test** was used for testing. The evaluation results demonstrated that the model achieved an impressive accuracy of **96.871%**. This accuracy score reflects the model's ability to generalize and perform well on unseen data.

## Repository Structure

- `training_7/`: This directory contains the saved model checkpoint files.
- `data/`: If applicable, this directory contains the rice grain imaging dataset.
- `code/`: This directory contains the source code used for training, evaluating the model, and any other relevant scripts.
- `README.md`: You are currently reading this file, which provides an overview of the project.

## Getting Started

To reproduce the results or explore the project further, follow these steps:

1. Navigate to the `code/` directory, where you'll find the code files.
2. Run the jupyter notebook for loading the saved checkpoint and evaluating the model on the dataset .

## Dependencies

List any specific dependencies or libraries required to run the code successfully, along with their version numbers.

- Tensorflow version 2.9.1
- matplotlib==3.7.2 
- scikit-learn==1.3.0 
- scipy==1.10.1
- cuda11.7.0-cudnn8-ubuntu20.04
- Jupyter-notebook==1.0.0

## Contact Information

If you have any questions, suggestions, or feedback regarding this project, please feel free to contact Nusrat Mohi Ud Din at nusratmohiuddin92@gmail.com.

---

By providing clear and concise information about the training process, model evaluation, and repository structure, this readme file effectively communicates the key aspects of your project to anyone who wants to understand, reproduce, or build upon your work.