# CNN Brain Tumor: Multi-Class Brain Tumor Classification

### Updated: Tensorflow 2.16 Classification Accuracy 99.6%
[CNN Classification using Tensorflow 2.16](https://www.kaggle.com/code/guslovesmath/cnn-tumor-classifying-tensorflow-2-16-99-6)

## Overview
This repository contains the code and documentation for a Convolutional Neural Network (CNN) designed to classify brain tumors into multiple categories, including Glioma, Meningioma, No Tumor, and Pituitary. The model achieves a high accuracy rate of 99.4%, making it a robust tool for medical diagnostics. This project demonstrates how advanced CNN models, with optimized learning rates and early stopping mechanisms, can significantly enhance the accuracy and efficiency of brain tumor diagnosis, leading to improved medical treatment outcomes.

## Files Included
1. **CNN_Keras_JN_GY.ipynb**: The Jupyter Notebook with the final version of the CNN model. It includes the complete code for model building, training, evaluating, and fine-tuning.
   
2. **Medical Diagnostics CNN - Power Point.pdf**: A PowerPoint presentation providing an overview of the project, including the problem statement, methodology, and results.

3. **Medical Diagnostics - Report.pdf**: A comprehensive report detailing the construction, evaluation, and findings of the model, including methodology and results.

4. **history_2.npy**: A NumPy file containing the training history of the model. This includes metrics such as loss and accuracy for each epoch, useful for analyzing the model's performance over time.

5. **model_2.h5**: The saved model file in HDF5 format. This contains the architecture, weights, and training configuration of the final, optimized CNN model, ready for deployment or further research.

## Project Details
- **Project Language:** Python, TensorFlow, Keras, Pandas, NumPy, Seaborn, Matplotlib.
- **Model Accuracy**: 99.4% on a large dataset of MRI brain tumor images.
- **Categories Classified**: Glioma, Meningioma, No Tumor, and Pituitary.
- **Key Techniques Used**: Data augmentation, fine-tuning of learning rates with the Adam optimizer.
- **Performance Enhancements**: Implementation of EarlyStopping and ReduceLROnPlateau callbacks to prevent overfitting and optimize learning rates during training.
