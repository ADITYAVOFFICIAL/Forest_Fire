# Forest Fire Detection using Convolutional Neural Networks

Forest-fire detection model using TensorFlow and Keras, achieving 91.38% training accuracy and 90.10% validation accuracy. This convolutional neural network (CNN) significantly enhances early detection capabilities for forest fires, integrating advanced deep learning techniques for accurate prediction and prevention.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Dependencies](#dependencies)
- [Project Structure](#project-structure)
- [Code Explanation](#code-explanation)
  - [Data Loading](#data-loading)
  - [Data Preprocessing](#data-preprocessing)
  - [Model Architecture](#model-architecture)
  - [Model Training](#model-training)
  - [Evaluation and Visualization](#evaluation-and-visualization)
- [Results](#results)
- [Model Saving](#model-saving)
- [Usage](#usage)
- [License](#license)

## Project Overview
This project involves building a binary classifier using a CNN to detect forest fires. The model is trained on a dataset of images, categorized as either 'Fire' or 'Non-Fire'.

## Dataset
The dataset used for training consists of images stored in two directories:
- `Fire`: Contains images with forest fires.
- `Non_Fire`: Contains images without forest fires.

The dataset is loaded from a directory structure and is processed into a pandas DataFrame for further processing.

## Dependencies
The project relies on the following Python libraries:
- `pandas`
- `numpy`
- `matplotlib`
- `tqdm`
- `keras`
- `tensorflow`
- `seaborn`
- `sklearn`

## Accuracy and Loss Graphs


![Accuracy g](https://user-images.githubusercontent.com/75358720/150759562-1f60fe55-f36e-43c8-9b75-9a36100cbf98.jpg)
![loss graph](https://user-images.githubusercontent.com/75358720/150759589-dceb2e2f-65f0-43b0-ac36-0eb589e1fb05.jpg)

You can install the required packages using:
```bash
pip install -r requirements.txt 



