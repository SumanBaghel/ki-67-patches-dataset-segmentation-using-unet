# ki-67-patches-dataset-segmentation-using-unet

This project was developed during my internship at NETR AI PVT. LTD., Indian Institute of Technology (IIT), Bhilai.

## Table of Contents

- [Overview](#Overview)
- [Dataset](#Dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Result](#result)

## Introduction

This project aims to perform image segmentation using the U-Net architecture, a powerful deep learning model for image segmentation tasks. The dataset used in this project is the Ki-67 Patches dataset, which consists of high-resolution images of cell nuclei labeled with Ki-67, a protein associated with cell proliferation.
U-Net is well-suited for image segmentation due to its encoder-decoder design, enabling it to capture both high-level and low-level features in images. This makes it particularly effective for tasks such as cell segmentation in medical images. 

## Dataset

The Ki-67 Patches dataset can be accessed from zip file {images.zip}. It contains images of cell nuclei, and each image is paired with corresponding segmentation masks {segmentation.zip} that outline the boundaries of the nuclei. Preprocessing steps, including data  normalization, have been applied to enhance model performance.

## Installation

To run this project, follow these steps:

1. Clone this repository to your local machine.
2. Set up a Python environment (e.g., using virtualenv or conda).
3. Download the Ki-67 Patches dataset and place it in the appropriate directory (if not done already).

## Usage

1. Open the Jupyter Notebook provided in the repository: ki-67-patches-dataset-segmentation-using-unet.ipynb.
2. Follow the step-by-step instructions in the notebook to load the dataset, preprocess the data, and train the U-Net model.
3. Experiment with hyperparameters, data augmentation settings, or model architecture to improve performance.
4. Monitor the training process and evaluate the model on test data.
5. Visualize the segmentation results and analyze the model's performance.

## Result

Here is sample result:

![download](https://github.com/SumanBaghel/ki-67-patches-dataset-segmentation-using-unet/assets/89180252/bb159cc0-6c18-40b0-a549-b60192baece9)






