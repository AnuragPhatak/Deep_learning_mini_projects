# Deep Learning Projects Portfolio

This repository showcases two deep learning projects implemented using Keras and TensorFlow. Each project focuses on solving real-world problems through Artificial Neural Networks (ANNs). The repository includes well-documented code, model evaluation, and visualizations to ensure clarity and reproducibility.

---

## **Projects Overview**

### **1. MNIST-Fashion Classification**
- **Objective**: To classify grayscale images of clothing articles into one of 10 categories (e.g., T-shirt, Trouser, Dress, etc.) using the Fashion MNIST dataset.
- **Dataset**: 
  - **Training Set**: 60,000 images
  - **Test Set**: 10,000 images
- **Highlights**:
  - Data preprocessing with normalization.
  - Model architecture:
    - Flatten Layer
    - Dense Hidden Layer (ReLU activation)
    - Output Layer (Softmax activation)
  - Training with Adam optimizer and Sparse Categorical Crossentropy loss.
  - Performance evaluation with metrics like accuracy, confusion matrix, and classification report.
  - Visualized predictions for comparison between actual and predicted labels.
- **Outcome**: Achieved high accuracy on the test dataset with detailed performance analysis.

---

### **2. Predicting Concrete Compressive Strength**
- **Objective**: To predict the compressive strength of concrete (in MPa) based on mixture composition and age using an ANN.
- **Dataset**: Contains features like cement, water, coarse aggregate, fine aggregate, and concrete age (days).
- **Highlights**:
  - Feature scaling with `StandardScaler`.
  - Model architecture:
    - Dense Hidden Layers (ReLU activation)
    - Output Layer (Linear activation for regression)
  - Hyperparameter tuning using GridSearchCV with K-Fold cross-validation.
  - Performance evaluation using metrics like Mean Squared Error (MSE), Mean Absolute Error (MAE), and R² Score.
  - Visualized training and validation loss to ensure robust model training.
- **Outcome**: Built a regression model capable of accurately predicting concrete strength based on input features.

---

