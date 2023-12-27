# Project-Introduction-Eco-Acoustic-Species-Detection

In this project, I am developing machine learning models for the automated detection of bird and frog species in tropical soundscapes. Using the data provided by the Rainforest Connection (RFCx), a leader in conservation technology, my focus is on overcoming the limitations of traditional deep learning models by creating a system that can accurately identify species with limited training data. 

The ultimate goal is to contribute to the development of a scalable, real-time monitoring system for remote ecosystems, providing valuable insights into environmental changes and supporting swift conservation efforts.

## Explanation :

The model is based on Resnet101 for its training. During each epoch, the model is trained on the training dataset, and its performance is evaluated on the validation dataset. The training progress, including losses and validation accuracy, is printed for each epoch. The function uses a copy of the best-performing model weights and returns the trained model. Additionally, a learning rate scheduler is employed to adjust the learning rate based on the validation loss, contributing to improved training stability.

## Data source :

https://www.kaggle.com/competitions/rfcx-species-audio-detection/data
