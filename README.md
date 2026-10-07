# RetinAI

RetinAI is a computer vision and deep learning project for detecting and classifying stages of **Diabetic Retinopathy** from retinal fundus images.

The project combines a trained deep learning model with a Django-based web application, allowing users to upload retinal images and receive model-based classification results.

## Tech Stack

- Python
- Django
- PyTorch / Deep Learning
- MobileNetV3
- Transfer Learning
- Computer Vision
- SQLite3
- AWS EC2
- Kaggle Diabetic Retinopathy Dataset

## Key Features

- Upload retinal fundus images through a web interface
- Classify stages of diabetic retinopathy using a trained deep learning model
- Transfer learning using a pre-trained MobileNetV3 architecture
- Model training using more than 40,000 retinal images
- Patient data storage using SQLite3
- Django-based backend and web interface
- Deployment on AWS EC2

## Project Overview

The goal of RetinAI is to apply deep learning to retinal image analysis and assist in identifying different stages of diabetic retinopathy.

The model was trained using the Kaggle Diabetic Retinopathy dataset containing more than 40,000 retinal images. Transfer learning was applied using a pre-trained MobileNetV3 model to improve training efficiency and classification performance.

The trained model was integrated into a Django web application where users can upload retinal images for classification.

## Application Workflow

1. User uploads a retinal fundus image.
2. The image is processed before being passed to the trained model.
3. The MobileNetV3-based model performs diabetic retinopathy classification.
4. The predicted result is returned through the Django web interface.
5. Patient-related information can be stored using SQLite3.

## Running the Web Application Locally

Install Django and the required project dependencies:

```bash
pip install django
```

Navigate to the project directory and run:

```bash
python manage.py runserver
```

The application will be available locally at:

```text
http://localhost:8000/
```

## Model Development

The deep learning pipeline includes:

- Retinal image preprocessing
- Transfer learning using MobileNetV3
- Training on 40,000+ diabetic retinopathy images
- Model evaluation and classification
- Integration of the trained model with the Django application

## Deployment

The RetinAI web application was deployed on an **AWS EC2 instance**, with **SQLite3** used for storing application and patient-related data.

## Portfolio Note

This repository represents my work on applying computer vision and deep learning techniques to diabetic retinopathy classification and integrating a trained machine learning model into a deployable Django web application.

The project demonstrates experience across model development, transfer learning, backend web development, database integration, and cloud deployment.
