# Brain Tumor Classification using CNNs

Ameena Gaji (Craft and Hawkins Department of Petroleum Engineering), agaji1@lsu.edu

This project seeks to classify brain MRI scans for early detection of glioma, pituitary, and meningioma tumors using Convolutional Neural Networks (CNN). With the aid of CNNs which provide fully automated detection, diagnostic abilities of clinicians and radiologists will be enhanced thereby shortening the time required for patient diagnosis ultimately saving lives.

<img width="817" alt="Screenshot 2023-12-02 at 12 59 02 AM" src="https://github.com/Meegaj/Machine_learning/assets/125159642/dd6d7f66-ceb0-4002-9e55-936837ae4f6d">

# Methodology
- The proposed CNN model employed image preprocessing techniques, including image resizing to 160x160 pixels using OpenCV.
- Implemented data augmentation strategies like rotations,shifts and flips using Keras'ImageDataGenerator to enrich the dataset and enhance model generalization.
- Encoded labels into a numerical format suitable for CNN processing.
- Split the dataset into 85% training and 15% testing.

# CNN Architecture
- The CNN architecture comprises of 5 convolutional layers.
- Batch normalization was applied for training stabilization and acceleration.
- Max pooling and global average pooling were employed to reduce spatial dimensions and parameters.
- Dropout layers were included to prevent overfitting.
- Dense layers for included feature interpretation and a ‘Softmax’ output layer for multi-class classification.

# Results
- A training accuracy of 99.71% after 25 epochs was achieved, indicating strong learning capability.
- Validation accuracy of 90.8% after 25 epochs, demonstrating model effectiveness on unseen data.
- AUC values for classifying different tumor types were near perfect, signifying excellent model performance.
- Performance Metrics such as; accuracy, precision, recall, F1 score, ROC curves, and confusion matrix were all reported for model evaluation.

# Future Work
Hyperparameter optimization and the use of pre-trained models such as VGG16, ResNet etc. should be deployed for enhanced model performance.

# Reference
Feel free to use the code, however please reference appropriately.
