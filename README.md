# INM705_CW
Image Analysis Coursework


## File Description
FasterRCNN_config.ipynb notebook reads config.yaml file under fruit-images-for-object-detection folder. There are three categories in the YAML file, path_settings, model selection, and hyperparameters for training. They can be changed and notebook can be executed with changing parameters. The minimum loss will be saved as a checkpoint under fruit-images-for-object-detection/checkpoints folder. Inference file Inference_Load_Checkpoints.ipynb can be used to load from a checkpoint and test the images.

Checkpoints could not be uploaded to Github. Instead they are on dropbox server.
https://www.dropbox.com/scl/fo/ym0gc1dvvhdmixzr2nd7v/AABaV2M4Gdv6aeilR8AzfCY?rlkey=iwqkfrnvijh9jelj6rf6l9iwj&st=31ucpn0h&dl=0


## 🎶 Project Description
This project uses deep learning techniques using Resnet50 or MobileNet as backbone to predict the classes of Fruits Image Dataset.


## 🎯 Objectives:
The main objective is to accurately estimate the correct class of the fruit images and predict the bounding boxes of the fruits within the images.


## 🎶 Dataset 
Train and Test Dataset can be downloaded from kaggle website.
https://www.kaggle.com/datasets/mbkinaci/fruit-images-for-object-detection/download?datasetVersionNumber=1

## 📈 Results:
Test results demonstrate that training with MobileNet as the backbone architecture is faster than with ResNet50.
