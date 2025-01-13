# DermaDetect-AI-Powered-Skin-Cancer-Detection


This repository contains the implementation details of DermaSnapNet, a project aimed at building an advanced deep learning-based model for skin cancer detection using the HAM10000 dataset. The project integrates MobileNet with Random Forest and Snapshot Ensemble techniques to classify dermoscopic images into seven distinct classes of skin lesions.
##Objectives
Early detection of skin cancer to improve patient outcomes and reduce mortality.
Development of efficient and accurate deep learning models tailored for medical image classification.
Implementation of hyperparameter optimization techniques to achieve robust model performance.


## Key Features
### Dataset:
Utilized the HAM10000 dataset containing 10,000 labeled dermoscopic images. It represents a diverse collection of seven classes:

Melanocytic Nevi
Basal Cell Carcinoma
Squamous Cell Carcinoma
Benign Keratosis
Dermatofibroma
Vascular Lesions
Melanoma

### Model Architectures:

Model 1: MobileNet as a feature extractor + Random Forest classifier.
Model 2: MobileNet integrated with dense layers, enhanced by the Snapshot Ensemble technique.

### Hyperparameter Tuning:

Systematic exploration using Keras Tuner.
Tuned parameters: dense layer units, activation functions, dropout rates, and optimizers.

### Preprocessing:

Image resizing, normalization, and augmentation.
Techniques like horizontal/vertical flips, rotations, and zooming.

### Evaluation Metrics:

Accuracy, Precision, Recall, F1 Score.
Confusion matrix and training-validation loss graphs.

### Results
Model Accuracy:

Snapshot Ensemble Model: ~97.48% validation accuracy.
Random Forest Model: Comparable robust classification performance.
F1 Score: Achieved an F1 score of 0.963, highlighting effective precision-recall balance.

## Conclusion
DermaSnapNet demonstrates the efficacy of integrating MobileNet with advanced classification techniques for real-world medical image analysis. By leveraging ensemble learning and systematic hyperparameter optimization, the model achieves state-of-the-art performance in skin lesion classification.


