🌿 Green Crop Analyzer

Plant disease detection web application using MobileNetV2 and TensorFlow, trained on the PlantVillage dataset, with real-time leaf image classification via Streamlit.

📌 Overview

Green Crop Analyzer is an end-to-end deep learning project that identifies plant diseases from leaf images. It leverages transfer learning with MobileNetV2 to accurately classify crop health conditions across multiple plant species.

The project includes:

Model training and fine-tuning using TensorFlow

Image preprocessing and data augmentation

A Streamlit-based web app for real-time predictions

🧠 Model Details

Architecture: MobileNetV2 (pretrained on ImageNet)

Technique: Transfer Learning + Fine-tuning

Input Size: 128 × 128 RGB images

Number of Classes: 15

Dataset: PlantVillage (Kaggle)

🖼️ Supported Classes

The model predicts plant health and diseases for:

Pepper (Bell)

Potato

Tomato

Including healthy leaves and multiple disease categories.

🛠️ Tech Stack

Python

TensorFlow / Keras

MobileNetV2

Streamlit

NumPy, Pillow

📊 Key Features

Transfer learning for efficient training

Data augmentation for better generalization

Real-time prediction via web interface

Multiple image upload support

Image preprocessing, data augmentation, fine-tuning

📌 Notes

Dataset and trained model are not included in the repository due to size constraints

This project was developed and trained using Google Colab

⚠️ Note: If GitHub preview does not render correctly, please open the notebook using the Colab link provided at the top.

