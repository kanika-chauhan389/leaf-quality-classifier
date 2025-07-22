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
- `README.md`: Project overview and usage guide
  
#  Dataset
This project uses a reduced version of the [PlantVillage dataset](https://www.kaggle.com/datasets/emmarex/plantdisease).  
You can also download the prepared dataset (200 images per class) from Google Drive:
🔗 [Download from Drive](https://drive.google.com/file/d/1XnIWIqOl5PWNLH0hT7VzfcWmT9CcOPFf/view?usp=drive_link)

# Tech Stack
- Python
- TensorFlow/Keras
- OpenCV & PIL (for preprocessing)
- Matplotlib
- Google Colab

## 🚀 Model Performance

| Metric        | Value |
|---------------|-------|
| Test  Acc     | 84%   |



# Applications
- Plant disease diagnosis
- Agricultural quality classification
- Educational demonstration of CNNs for image classification
