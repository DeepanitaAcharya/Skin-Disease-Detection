# Skin Disease Detection from Facial Images Using Deep Learning

📌 Project Overview

This project focuses on detecting selected skin diseases from facial images using deep learning and image processing techniques.

The proposed system takes a facial image as input, detects the face, extracts the relevant facial region, 
preprocesses the image, and uses a deep learning model to classify the visible skin condition.

 ⚠️ This project is an academic research prototype and is not intended to provide medical diagnosis.

🎯 Objectives

- Detect the face from an input image.
- Extract the relevant facial/skin region.
- Preprocess images for deep learning.
- Develop a deep learning-based classification model.
- Classify selected skin conditions.
- Display the predicted condition with confidence scores.
- Evaluate the model using standard performance metrics.
- Develop a simple interface for testing the model.

🦠 Target Skin Conditions

The project currently focuses on five classes from the Fitzpatrick17k dataset:

1. Acne
2. Eczema
3. Psoriasis
4. Rosacea
5. Lichen Planus

📊 Dataset

The project uses the **Fitzpatrick17k** dermatology dataset.

The selected subset contains **2,104 images** across the five target classes.

| Class | Images |
|---|---:|
| Psoriasis | 706 |
| Acne | 518 |
| Lichen Planus | 491 |
| Eczema | 287 |
| Rosacea | 102 |
| **Total** | **2,104** |

The dataset annotations are provided through the official Fitzpatrick17k repository.

## 🔬 Proposed Methodology
Input Facial Image
        ↓
Face Detection
        ↓
Face / Skin Region Extraction
        ↓
Image Preprocessing
        ↓
Deep Learning Model
        ↓
Disease Classification
        ↓
Prediction + Confidence

🧠 Deep Learning Approach
🛠️ Technologies
Python
Google Colab
TensorFlow / Keras
OpenCV
MediaPipe
NumPy
Pandas
Scikit-learn
Matplotlib
Streamlit
GitHub

📈 Planned Evaluation
The model will be evaluated using:
Accuracy
Precision
Recall
F1-score
Confusion Matrix

🚧 Project Status
Completed
Literature survey
Dataset collection and selection
Fitzpatrick17k dataset analysis
Selection of five target classes
Google Colab and Google Drive setup
Initial dataset analysis
GitHub repository setup


In Progress / Planned
Face detection
Image preprocessing
Model development and training
Model evaluation
Streamlit interface
Testing
Final documentation
