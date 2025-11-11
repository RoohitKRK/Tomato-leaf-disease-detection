# Tomato Leaf Disease Classification

## Project Overview
This repository contains the code and resources for a deep learning project focused on **classifying diseases in tomato plant leaves**. The goal is to build highly accurate models that can identify the specific disease affecting a tomato plant from an image of its leaf. The project leverages **transfer learning** with state-of-the-art Convolutional Neural Network (CNN) architectures.

## Dataset
The project utilizes a dataset of tomato leaf images across **10 different classes** (diseases and healthy states). Data is loaded using a combination of a `train.csv` metadata file and image files stored in a `Tomato_images` directory.

## Models and Approach
The primary approach involves training and evaluating different pre-trained models using the `tensorflow.keras` framework.

The following model architectures were explored:

* **EfficientNetB0**: A compact and efficient CNN architecture.
* **ResNet50**: A widely used residual network model.

Training includes data augmentation using `ImageDataGenerator` and performance monitoring with callbacks like `ModelCheckpoint` and `EarlyStopping`.

## Repository Structure

| File Name | Description |
| :--- | :--- |
| `Project_Efficientnetb0.ipynb` | Colab notebook for **EfficientNetB0** model training and evaluation. |
| `Project_resnet.ipynb` | Colab notebook for **ResNet50** model training, evaluation, and includes code for **Grad-CAM** visualization for model explainability. |
| `Pytorch.ipynb` | A notebook containing a model that saved a Keras InceptionV3 model. |
| `requirements.txt` | Python package dependencies for running the notebooks. |
| `LICENSE` | MIT License details for the project. |

## Getting Started
1.  Clone this repository.
2.  Install dependencies: `pip install -r requirements.txt`
3.  Place your dataset (including `train.csv` and the `Tomato_images` folder) in the appropriate structure as referenced in the notebooks.
4.  Run the notebooks in Google Colab or a local Jupyter environment.

---



