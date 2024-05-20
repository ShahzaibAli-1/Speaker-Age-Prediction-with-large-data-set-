# 🎙️ Speaker Age Prediction from Audio Recordings

## Introduction
The **Speaker Age Prediction from Audio Recordings** project aims to predict the age of speakers based on acoustic features extracted from audio recordings. This documentation provides an overview of the project, including its purpose, methodology, and implementation details.

## Overview
The project utilizes machine learning techniques to predict the age of speakers from audio recordings. The workflow involves several key steps:

1. **📊 Data Collection:** Audio recordings of speakers with associated age labels are collected for training and testing the model.
2. **🎼 Feature Extraction:** Relevant acoustic features such as pitch, intensity, duration, spectral centroid, and others are extracted from the audio recordings.
3. **🧹 Data Preprocessing:** The extracted features are preprocessed to handle missing values, normalize data, and prepare it for model training.
4. **🤖 Model Training:** A linear regression model is trained using the preprocessed data to predict speaker age based on the extracted features.
5. **📉 Model Evaluation:** The trained model is evaluated using various metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared (R2) coefficient of determination.

## Code Implementation
The project's code is implemented in Python using popular libraries such as NumPy, pandas, librosa, and scikit-learn. The main components of the code include:

- **📂 Data Loading and Cleaning:** Audio data is loaded from CSV files and cleaned to remove duplicates and handle missing values.
- **🔍 Feature Extraction:** Acoustic features are extracted from audio recordings using the librosa library.
- **🧠 Model Training:** A linear regression model is trained using gradient descent optimization.
- **📝 Model Evaluation:** The trained model is evaluated using standard regression metrics to assess its performance.

## Usage
To use the project code:

1. 📦 Install the required libraries: `numpy`, `pandas`, `librosa`, `scikit-learn`.
2. 🗂️ Prepare the audio dataset in CSV format with columns for filenames, age labels, and other relevant information.
3. 🖥️ Execute the provided Python scripts or Jupyter notebooks to load, preprocess, train, and evaluate the model.
4. 📊 Visualize the results and evaluate model performance using appropriate metrics.

## Conclusion
The **Speaker Age Prediction from Audio Recordings** project demonstrates the application of machine learning techniques to predict speaker age based on acoustic features extracted from audio recordings. By training a linear regression model and evaluating its performance, the project aims to provide accurate predictions of speaker age.

## Contributor
- [Shahzaib Ali](https://github.com/ShahzaibAli-1)
- [Abdul Ahad](https://github.com/AbdulahadIltaf)

## Copyright
© 2024 [Shahzaib Ali](https://github.com/your_username)  [Abdul Ahad](https://github.com/AbdulahadIltaf). All rights reserved.
