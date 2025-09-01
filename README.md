Lung Cancer Prediction using Deep Learning

 Overview
This project uses deep learning techniques to predict lung cancer from medical imaging data.
It was implemented in Google Colab using TensorFlow/Keras with transfer learning and data augmentation.

Features
Preprocessing of medical images (resize, normalization, augmentation)
Deep learning model built with MobileNetV2
Training, validation, and testing pipelines
Performance evaluation using accuracy, loss curves, and classification metrics
Easy-to-run .ipynb notebook in Google Colab

Dataset
Dataset: IQ-OTH/NCCD Lung Cancer Dataset
Images: 1,097 (after preprocessing)
Training: 767
Validation: 165
Test: 165
Image size: 256 × 256 × 3
(Dataset not included in repo due to size; can be downloaded separately.)

Tech Stack
Python 3
TensorFlow / Keras
NumPy, Pandas
Matplotlib, Seaborn
Google Colab

Results
Achieved classification accuracy of around 88% on test data.
Model performance can be further improved with hyperparameter tuning and larger datasets.

How to Run
Open the notebook in Colab
Upload dataset to Google Drive and set dataset_path in the notebook.
Run all cells to train and evaluate the model.

Future Work

Improve accuracy with advanced architectures (e.g., ConvMixer, EfficientNet).
Deploy the model as a web app for easy use.
Integrate explainable AI (Grad-CAM) for model interpretability.
