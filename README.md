# Nucleus MaskRCNN

This repository contains scripts and resources for training and utilizing MaskRCNN with a ResNet 101 backbone on the Nucleus dataset. The model is designed for instance segmentation tasks, specifically focusing on delineating nuclei within images.

## Files

### 1. Nucleus_MaskRCNN_50epochs.h5:
Pre-trained model weights after 50 epochs of training.

### 2. nucleus_training.py:
Python script for training the MaskRCNN model on the Nucleus dataset.

### 3. nucleus_prediction.py:
Python script for making predictions using the pre-trained model.

## Folder Structure

- **images:**
Input images for training and prediction.

- **masks:**
Ground truth masks corresponding to the images in the 'images' folder.

- **annots:**
Annotations in CSV format providing information about bounding boxes and class labels.

## Usage

### Training and Prediction

Run the `nucleus_training.py` script to train the MaskRCNN model. Adjust hyperparameters and configurations as needed for your dataset.

```bash
python nucleus_training.py

To make predictions using the pre-trained model, run the following command:

```bash
python nucleus_prediction.py





