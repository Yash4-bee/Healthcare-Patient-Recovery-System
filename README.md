# Healthcare-Patient-Recovery-System
Healthcare Patient Recovery Prediction Model using Deep Learning
# Project Overview:
    This project focuses on building a deep learning–based classification system to predict,
    whether a patient will recover after medical treatment.
    The objective is to support hospitals in identifying high-risk patients early and enabling data-driven clinical and operational decisions.

# Business Objective
    Hospitals often operate under resource constraints where early identification of patient outcomes is critical.
    
    This model aims to:
        1. Prioritize high-risk patients for closer monitoring
        2. Optimize ICU and hospital resource allocation
        3. Support clinicians in treatment planning and follow-up strategies

# Problem Statement
    Given a patient’s clinical and lifestyle attributes,
    predict whether the patient will recover after treatment.
    This is formulated as a binary classification problem.

# Target Variable
    Recovered (1 = Patient recovered, 0 = Patient did not recover)
    
# Dataset Description
    Total Records: 15,000 patients
    Total Features: 15 input variables
    Data Type: Fully numerical
    Feature Domains:
        Demographics (Age)
        Vital signs (Oxygen level, Heart rate, Blood pressure)
        Clinical indicators (Cholesterol, Sugar level, Days Hospitalized)
        Lifestyle and treatment-related factors

# Modeling Approach
    Algorithm: Deep Neural Network (Multi-Layer Perceptron)

# Why Neural Networks:
    Captures non-linear relationships between medical features
    Scales effectively with higher-dimensional clinical data
    
    Preprocessing:
      Train–test split
      Feature standardization
    Model Optimization:
      Dropout
      L2 regularization to reduce overfitting
      Early stopping for generalization control

# Outcome
  The final model demonstrates strong predictive performance while maintaining generalization,
  making it suitable as a decision-support tool rather than a black-box accuracy-only solution.

# Notebook Link
https://colab.research.google.com/drive/1lJx-ff0H7-5XINVAl1Y2pMGCGj0RcbzL?usp=sharing
