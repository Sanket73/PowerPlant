# PowerPlant
PowerPlant_Data is a machine learning project focused on predicting the electrical energy output of a Combined Cycle Power Plant using environmental variables.

This project demonstrates practical implementation of **Artificial Neural Networks (ANNs)** for solving a real-world regression problem using **PyTorch**, along with proper data preprocessing, model validation, and performance evaluation.

# Project Highlights

Built an end-to-end deep learning regression model using PyTorch to predict power plant energy output from environmental features.
Implemented data preprocessing, feature scaling, batch training, validation monitoring, and model checkpointing for robust performance.
Achieved strong predictive accuracy with low MSE and high R² score, demonstrating effective modeling of nonlinear relationships.

# Dataset Description

The dataset contains 9568 observations and 5 numerical features:

* AT → Ambient Temperature

* V → Exhaust Vacuum

* AP → Ambient Pressure

* RH → Relative Humidity

* PE → Electrical Energy Output (Target Variable)

All features are continuous (float64) with no missing values.

# Project Workflow

1. Data Preprocessing

    * Feature & target separation

    * Train-test split

    * Feature scaling using StandardScaler

2. Tensor Conversion

    * Converted NumPy arrays to PyTorch tensors

    * Created TensorDataset and DataLoader

3. ANN Model Architecture
<img width="1408" height="768" alt="image" src="https://github.com/user-attachments/assets/fb4aa3f1-3db4-4eb4-8fde-9e4eeb72a054" />


4. Training Setup

    * Loss Function: Mean Squared Error (MSELoss)

    * Optimizer: Adam

    * Epochs: 100

    * Best model saved using validation loss

5. Evaluation

    * Training & Testing MSE

    * R² Score

    * Prediction vs Actual comparison

# Results & Performance

* Model achieves low Mean Squared Error

* Strong R² score, indicating good predictive capability

* Validation loss closely tracks training loss, suggesting minimal overfitting

* Predictions closely align with actual energy outputs

* This demonstrates effective learning of nonlinear dependencies between environmental conditions and power generation.

# Key Skills Demonstrated

* Deep Learning for Regression

* PyTorch Model Development

* Data Preprocessing & Standardization

* Model Evaluation & Validation Techniques

* Overfitting Monitoring

* Practical ML Pipeline Implementation

# Technologies Used
Languages ![Python](https://img.shields.io/badge/Python-3.10+-3776AB?logo=python&logoColor=white)

Libraries ![PyTorch](https://img.shields.io/badge/PyTorch-DeepLearning-EE4C2C?logo=pytorch&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)

Machine Learning ![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?logo=scikit-learn&logoColor=white)

Visualization ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C)

Environment ![Jupyter Notebook](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)
