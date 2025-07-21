# Leaf Quality Classifier (CNN)

A Convolutional Neural Network (CNN) model built for classifying plant leaf images into quality categories using a subset of the PlantVillage dataset.

This project simulates real-world agricultural applications such as crop disease diagnosis or visual quality inspection of produce, using computer vision.

# Key Features
- Multi-class image classification using deep learning
- Uses 3 tomato leaf classes: Healthy, Early Blight, Late Blight
- Balanced dataset with resized 128x128 images
- Clean folder structure for train/val/test splits
- Model built with TensorFlow & trained on Google Colab
- Accuracy and loss visualization included

# Files Included
- `Leaf_Quality_Classifier.ipynb`: Full Colab notebook with training pipeline
- `model.h5`: Saved trained model
- `README.md`: Project overview and usage guide
#  Dataset
This project uses a reduced version of the [PlantVillage dataset](https://www.kaggle.com/datasets/emmarex/plantdisease).  
Please download it manually and place it in your working directory.

# Applications
- Plant disease diagnosis
- Agricultural quality classification
- Educational demonstration of CNNs for image classification
