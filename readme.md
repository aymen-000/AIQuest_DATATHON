# Anemia Detection using Conjunctiva Images

## Project Description

This project aims to detect anemia based on images of the conjunctiva (the inner part of the lower eyelid). Anemia is a condition characterized by a lack of healthy red blood cells, and it can often be detected by examining the color of the conjunctiva. Using a Convolutional Neural Network (CNN) implemented in TensorFlow, this model classifies images into anemic and non-anemic categories.

## Dataset

The dataset used for this project is sourced from Kaggle and can be found [here](https://www.kaggle.com/datasets/t2obd1a1253kmit/clean-augmented-anemia-dataset). The dataset consists of augmented images of the conjunctiva, labeled as anemic or non-anemic.

## Model Architecture

The model is built using a Convolutional Neural Network (CNN) architecture, which includes:

- Convolutional layers for feature extraction
- Max-pooling layers for down-sampling
- Fully connected layers for classification

Data augmentation techniques such as rotation, zoom, and flip were applied to enhance the training process and prevent overfitting.

## Training

The model was trained using TensorFlow. Key details include:

- Loss function: Binary Crossentropy
- Optimizer: Adam
- Metrics: Accuracy
- Training epochs: 100
- Validation split: 20%

## Results

The model achieved an accuracy of 91% on the validation set. Below are some sample predictions and the accuracy plot over the epochs.

### Sample Predictions:

![Sample Predictions](https://github.com/aymen-000/AIQuest_DATATHON/blob/main/imgs/anemia_results.PNG)

### Accuracy Plot:

![Accuracy Plot](https://github.com/aymen-000/AIQuest_DATATHON/blob/main/imgs/accuracy.PNG)

### Loss Plot:

![Loss Plot](https://github.com/aymen-000/AIQuest_DATATHON/blob/main/imgs/loss.PNG)

### Model Archtacteur :

![model](https://github.com/aymen-000/AIQuest_DATATHON/blob/main/imgs/mode.PNG)


The plot shows the training and validation accuracy over 100 epochs, demonstrating the model's learning progression.

## Usage

To use this model, clone the repository and ensure you have the necessary dependencies installed:

```bash
git clone https://github.com/aymen-000/AIQuest_DATATHON.git
cd AIQuest_DATATHON
pip install -r requirements.txt
