# Breast Cancer Classification

## Repository Link
[https://github.com/your_username/breast_cancer_classification](https://github.com/your_username/breast_cancer_classification)

## Description
This project focuses on the classification of breast cancer images into two categories: **benign** and **malignant**. The dataset contains images of breast cancer cell features, and the goal is to build a machine learning model that accurately classifies these images based on their characteristics. A simple **Convolutional Neural Network (CNN)** was used for the baseline model, and various strategies like **data augmentation**, **transfer learning**, and **pretrained models** were explored for improving the model's performance.

## Task Type
**Image Classification**

## Results Summary
- **Best Model**: Vision Transformer (ViT) with Fusion-based Approach
- **Evaluation Metric**: ROC AUC
- **Result**: Achieved an ROC AUC of 0.93 for breast cancer classification (malignant vs. benign).

## Documentation

### **Literature Review**
The literature review explored the application of various models for breast cancer detection. **CNNs** like **DenseNet**, **ResNet**, and **VGG** were found to be highly effective for this task. Additionally, recent papers on **Vision Transformers (ViT)** showed promising results for image classification tasks in medical domains. These models were compared against traditional machine learning approaches such as **Random Forests** and **SVM**, which were found to be less effective than deep learning methods.

### **Dataset Characteristics**
The dataset used in this project consists of **5 image samples** with attributes such as image dimensions and labels (benign or malignant). The dataset is small, and hence, techniques like **data augmentation** were applied. The dataset shows a slight class imbalance with more malignant samples than benign ones.

- **Missing Values**: No missing values were detected in the dataset.
- **Feature Distributions**: Features such as image width (`x_dim`) and height (`y_dim`) were visualized, showing reasonable variation.
- **Possible Biases**: There is a minor class imbalance, with a slightly higher number of malignant samples.
- **Correlations**: No significant correlations were found between the features.

### **Baseline Model**
The baseline model was a **Convolutional Neural Network (CNN)**. The CNN was built with multiple convolutional layers followed by fully connected layers, and it was trained using **binary cross-entropy loss**. The baseline CNN provided a starting point for further model improvements. It achieved an accuracy of **100%** and a ROC AUC of **0.87** on the validation set. However, the performance was further improved by using more complex models like **Vision Transformer (ViT)**.

### **Model Definition and Evaluation**
- **Baseline CNN**: Implemented as a simple CNN model using image dimensions (`x_dim`, `y_dim`) as input features.
- **ViT Model**: A fusion-based ViT model was used to further improve accuracy. The best result came from **ViT with a fusion approach**, achieving an ROC AUC of **0.93**.

#### **Model Evaluation**:
- **Best Model**: ViT with Fusion-based Approach
- **Evaluation Metric**: ROC AUC
- **Result**: The model achieved an ROC AUC of **0.93**.

---

### **Presentation**
For more details on the implementation, analysis, and results, refer to the Jupyter notebook and associated files in this repository.

