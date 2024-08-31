## Deep Learning for Age Prediction via Facial Recognition

This project is intended to train a deep learning model on images of faces to determine whether customers at a retail location are old enough to purchase alcohol.

The project files are intentionally left out of the repository due the large size of the JPG Faces file. 

The overview of the project results can be found in the Jupyter Notebook file. 

The requirements.txt file displays the necessary library and package versions needed for pushing the code to github.

The following libraries and packages are used in this project:
- pandas as pd
- numpy as np
- tensorflow as tf
- seaborn as sns
- matplotlib.pyplot as plt
- tensorflow.keras.preprocessing.image import ImageDataGenerator
- tensorflow.keras.applications.resnet import ResNet50
- tensorflow.keras.models import Sequential
- tensorflow.keras.layers import GlobalAveragePooling2D, Dense
- tensorflow.keras.optimizers import Adam
- tensorflow.keras.callbacks import ReduceLROnPlateau, EarlyStopping

This Jupyter notebook works on web based applications and locally. Simply open the "ComputerVision.ipynb" file. 
