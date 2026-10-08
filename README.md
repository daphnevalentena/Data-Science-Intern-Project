# ElevanceSkills Data Science Internship – Complete 6-Task Project

## 📌 Project Overview

This repository contains the complete work carried out during the **ElevanceSkills Data Science Internship**.

The internship project consists of six practical Artificial Intelligence and Data Science tasks covering **computer vision, deep learning, machine learning, audio classification, image classification, and interactive application development**.

The implementations were developed and tested primarily using **Python and Google Colab**, with models and supporting datasets maintained through Google Drive.

---

## 🎯 Objectives

The main objectives of the internship were to:

- Apply Artificial Intelligence and Data Science concepts to practical problems.
- Develop and evaluate machine learning and deep learning models.
- Work with image, audio, and structured data.
- Perform preprocessing and feature extraction.
- Build prediction pipelines for real-world applications.
- Develop interactive interfaces for model inference.
- Organize and document complete project workflows.

---

## 🚀 Tasks Completed

### Task 1 – Age and Gender Identification

Developed a computer vision system for identifying **age and gender from facial images**.

**Key areas:**
- Face image preprocessing
- Deep learning / CNN-based prediction
- Age estimation
- Gender classification
- Model training and evaluation
- Saved model inference

---

### Task 2 – Senior Citizen Identification

Extended the face-analysis workflow to identify **senior citizens** along with age and gender information.

**Key areas:**
- Face detection using OpenCV
- Haar Cascade face detection
- Age and gender prediction
- Senior citizen classification
- Combined face + age + gender + senior-citizen detection
- Video processing
- Gradio-based interface

The workflow also includes loading previously trained models instead of retraining unnecessarily.

---

### Task 3 – Voice Age, Gender and Emotion Analysis

Developed a voice-based analysis pipeline for predicting characteristics from speech/audio data.

**Key areas:**
- Audio dataset processing
- Audio feature extraction
- Voice gender classification
- Voice age/emotion prediction
- Machine learning and deep learning models
- Saved-model inference

---

### Task 4 – Sign Language Recognition

Developed an image-based **sign language recognition** system.

**Key areas:**
- Image preprocessing
- Hand/sign detection
- Feature extraction
- Machine learning classification
- Saved model loading
- Image-based sign prediction
- Interactive prediction workflow

---

### Task 5 – Car Colour Classification

Developed an image classification system for identifying the **colour of a car**.

**Key areas:**
- Image preprocessing
- Colour classification
- CNN-based image classification
- Model training and evaluation
- Class mapping
- Saved model inference

---

### Task 6 – Nationality-Based Person Attribute Detection

Developed a final interactive workflow that combines nationality selection with different person-attribute predictions.

The final workflow uses a **Gradio interface** with image upload, image preview and prediction results.

### Conditional Prediction Workflow

| Selected Nationality | Predictions |
|---|---|
| 🇮🇳 Indian | Age + Dress Colour + Emotion |
| 🇺🇸 United States | Age + Emotion |
| 🌍 African | Dress Colour + Emotion |
| Other | Nationality + Emotion |

### Task 6 Models

**Emotion Recognition**
- 7 emotion classes:
  - Angry
  - Disgust
  - Fear
  - Happy
  - Neutral
  - Sad
  - Surprise
- Best saved model: `task6_emotion_model.keras`
- Validation Accuracy: **50.07%**
- Validation Loss: **1.3371**

**Dress Colour Classification**
- 5 classes:
  - Black Dress
  - Blue Dress
  - Red Dress
  - White Dress
  - Yellow Dress
- Training images: **2510**
- Validation images: **626**
- Best validation accuracy: **99.20%**
- Final validation accuracy: **99.04%**
- Best saved model: `task6_dress_colour_model.keras`

The final tested Indian workflow produced:
- Nationality: Indian
- Age: 20.91 years
- Emotion: Happy
- Dress Colour: Blue

---

## 🛠️ Technologies Used

### Programming
- Python

### Machine Learning & Deep Learning
- TensorFlow
- Keras
- Scikit-learn

### Computer Vision
- OpenCV
- MediaPipe

### Data Processing
- Pandas
- NumPy

### Visualization
- Matplotlib
- Seaborn

### Application Development
- Gradio

### Development Environment
- Google Colab
- Google Drive
- GitHub

---

## 📂 Repository Contents

```text
Data-Science-Intern-Project/
│
├── Age_Gender_Identification_Final.ipynb
│
├── README.md
│
└── Additional project files
    ├── Reports
    ├── Screenshots
    └── Supporting documentation

Datasets and trained model files are maintained separately in Google Drive and are not uploaded to this GitHub repository.

💾 Model Management

The project uses separately stored trained models for the different tasks.

Examples include:

best_model.keras
senior_citizen_cnn_best.keras
senior_citizen_cnn_final.keras
voice_age_emotion_model.keras
voice_gender_svm.pkl
voice_gender_scaler.pkl
sign_language_model.pkl
car_colour_classifier.keras
task6_emotion_model.keras
task6_dress_colour_model.keras
📊 Project Outcome

The internship resulted in a collection of practical AI systems covering:

Face analysis
Age and gender identification
Senior citizen detection
Voice-based classification
Sign language recognition
Car colour classification
Emotion recognition
Dress colour classification
Nationality-based conditional prediction
Interactive Gradio applications

The project provided practical experience in the complete AI workflow:

Dataset → Preprocessing → Feature Extraction → Model Development → Evaluation → Model Saving → Prediction → Interactive Application

👩‍💻 Author

Daphne Valentena.S

B.Tech Artificial Intelligence and Data Science

ElevanceSkills Data Science Internship – 2026
