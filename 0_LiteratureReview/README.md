# Literature Review

## 1. Models Commonly Used for Breast Cancer Detection

Breast cancer detection has been a critical medical task extensively studied in the domain of computer vision. Several machine learning models have been employed for breast cancer diagnosis, particularly convolutional neural networks (CNNs).

- **Convolutional Neural Networks (CNNs)**: These models have been widely used due to their ability to capture spatial hierarchies in image data. CNN architectures such as DenseNet, ResNet, and VGG were successfully applied to breast cancer classification tasks using histopathological images and mammograms. DenseNet, in particular, was noted for its dense connections between layers, which allowed for better feature reuse and more efficient training.
- **Pre-trained Models**: Transfer learning, where pre-trained models like VGG16, ResNet50, and DenseNet were fine-tuned for specific tasks, was found to be effective in improving model performance when limited labeled data were available.

## 2. Format of the Training Data

The format of the training data used for breast cancer detection depended on the type of imaging modality employed. In this case, the dataset was found to contain images labeled as "benign" or "malignant," which is common for breast cancer detection.

- **Image Data**: The images were typically provided in formats like PNG or JPEG, often representing mammograms or histopathological slides. Each image was associated with a label (benign or malignant).
- **Data Augmentation**: Since the dataset was often too small, techniques such as horizontal flipping, rotation, and scaling were commonly applied to augment the data. These transformations were shown to help the model generalize better and prevent overfitting.

## 3. Amount of Training Data Typically Used

The amount of training data used varied depending on the complexity of the model and the nature of the problem. For breast cancer detection:
- **Small to Medium-sized Datasets**: Datasets like the one used in this study typically contained thousands of labeled images, which were used in academic studies and competitions. For example, the "BreakHis" dataset was found to contain over 7000 images across benign and malignant categories.
- **Transfer Learning**: Pre-trained models like DenseNet worked well even with smaller datasets when their weights were fine-tuned. This allowed the model to leverage knowledge from large datasets like ImageNet.

## 4. Pretrained Models for Breast Cancer Detection

Pretrained models played a crucial role in the success of machine learning models for medical image analysis. Some pretrained models frequently used include:
- **DenseNet**: DenseNet121, as used in this study, was a deep CNN that demonstrated good performance in image classification tasks. It was particularly useful in medical image analysis due to its efficient use of parameters.
- **ResNet and VGG**: ResNet50 and VGG16 were also commonly employed pretrained models in this domain. They were fine-tuned for breast cancer detection tasks and showed promising results.
- **EfficientNet**: A newer architecture, EfficientNet was optimized for both accuracy and computational efficiency, and it has increasingly been applied in the field of medical imaging.

## Summary of Literature Review

In the domain of breast cancer detection using deep learning, **CNN-based models** like **DenseNet** were commonly used for binary classification tasks such as distinguishing between benign and malignant tumors. The training data typically consisted of labeled image data (usually in formats such as PNG), and various data augmentation techniques were applied to improve model generalization. **Pretrained models**, especially **DenseNet**, **ResNet**, and **VGG**, were frequently employed for transfer learning, improving performance even with smaller datasets. These approaches were validated through a variety of medical imaging datasets and achieved remarkable results in breast cancer classification tasks.
