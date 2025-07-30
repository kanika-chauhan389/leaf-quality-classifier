# 🍃 Leaf Quality Classifier — Tomato Plant Disease Detection

A deep learning project for classifying **tomato leaf diseases** using image data from the [PlantVillage dataset](https://www.kaggle.com/datasets/emmarex/plantdisease). This model classifies images into three classes:

- **Tomato___Bacterial_spot**
- **Tomato___Late_blight**
- **Tomato___Healthy**

Built with TensorFlow/Keras and trained on a custom-cleaned subset of the dataset.

---

## 🧠 Project Summary

The goal of this project is to automatically detect and classify tomato leaf diseases using a **Convolutional Neural Network (CNN)**. The project focuses on:

- Building a CNN model from scratch
- Applying image preprocessing and augmentation
- Evaluating performance with metrics like accuracy, F1-score, precision, recall, and ROC-AUC
- Visualizing training curves, confusion matrix, and predictions

---

## 🗂️ Dataset

📦 **Source**: [PlantVillage on Kaggle](https://www.kaggle.com/datasets/emmarex/plantdisease)  
🔢 **Total Classes Used**: 3  
🧪 **Dataset Split**:
- 70% Training
- 20% Validation
- 10% Testing

The dataset was filtered and split manually using a custom script.

---

## 🏗️ Model Architecture

A basic CNN with:

- 3 Convolutional + MaxPooling layers
- Flatten + Dense + Dropout
- Output: 3-class softmax

You can easily upgrade this model using transfer learning (e.g., `MobileNetV2`, `EfficientNetB0`, `ResNet50`).

---

## 🔍 Evaluation Metrics

Achieved results on test set:

| Metric              | Score   |
|---------------------|---------|
| ✅ Accuracy          | **87.39%** |
| 🔻 Log Loss          | **0.2374** |
| 🎯 F1 Score (Macro)  | **0.8726** |
| 🎯 Precision (Macro) | **0.8728** |
| 🎯 Recall (Macro)    | **0.8737** |

Confusion matrix and ROC-AUC curves are also plotted for deeper insights.

---

## 📊 Visualizations

- ✅ Accuracy & Loss curves
- ✅ Confusion Matrix
- ✅ ROC-AUC Curves (multi-class)
- ✅ Sample predictions with class labels

---

## 🛠️ Requirements

```bash
tensorflow
numpy
matplotlib
seaborn
scikit-learn
opencv-python
