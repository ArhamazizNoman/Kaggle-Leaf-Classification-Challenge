Kaggle Leaf Classification Challenge
<img alt="License" src="https://img.shields.io/badge/license-MIT-blue.svg">

This repository contains a Jupyter notebook implementing a solution to the Kaggle Leaf Classification Challenge. The project uses PyTorch to build a multi-modal neural network that combines Convolutional Neural Networks (CNN) for image processing, Recurrent Neural Networks (GRU) for shape features, and Feed-Forward Neural Networks (FFNN) for margin and texture features to classify leaf species.

Table of Contents
Features
Dataset
Requirements
Installation
Usage
Results
Contributing
License
Features
Data preprocessing and visualization
Multi-modal architecture integrating images and feature vectors
Training with validation and performance monitoring
Kaggle submission generation
Dataset
The dataset includes approximately 1,584 leaf images with three additional feature types (margin, shape, texture) for each sample, totaling 99 species to classify.

Requirements
Python 3.x
PyTorch
NumPy, Pandas, Matplotlib
scikit-image
data_utils.py (provided in the challenge)
Installation
Clone the repository:


(https://www.kaggle.com/competitions/leaf-classification/overview)
Install dependencies:


pip install -r requirements.txt
Usage
Download the dataset from Kaggle
Run the notebook cells sequentially
Train the model and generate predictions
Submit submission.csv to Kaggle
Results
Achieves competitive performance on the Kaggle leaderboard with a multi-modal approach leveraging all available data modalities.

Contributing
Feel free to fork and improve the model or add new features!

License
This project is licensed under the MIT License - see the LICENSE file for details.

