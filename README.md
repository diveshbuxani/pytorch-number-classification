# PyTorch Number Classification

This is a simple neural network I made using PyTorch to classify handwritten digits (0-9).  
Link to the dataset I used: https://www.kaggle.com/code/wwsalmon/simple-mnist-nn-from-scratch-numpy-no-tf-keras  
(Instead of actual images as input, each input is a vector of length 784 representing the grayscale values of the pixel)

## Requirements
- PyTorch
- NumPy
- Pandas

## Usage
Run `num_classification.ipynb` to train the model on the dataset.

## Dataset
Uses `train.csv` - contains handwritten digit images (784 pixel features) with labels.

## Model
- 3-layer neural network with dropout regularization
- Trained with SGD optimizer
- ~80% training / 20% test split
- Achieves about 94% test accuracy
