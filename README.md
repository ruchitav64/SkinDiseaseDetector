# 🧠 Skin Disease Detector using CNN

A web application that detects common skin diseases like Acne, Eczema, and Psoriasis from uploaded images using a Convolutional Neural Network (CNN).

## 🔧 Tech Stack
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python (Flask), TensorFlow/Keras
- **Model**: CNN (trained on HAM10000 dataset)

## 📦 Features
- Upload an image through a simple interface
- Get instant prediction of skin condition
- Trained model saved and used for inference

## 🗃 Dataset 
[Kaggle Link](https://www.kaggle.com/code/mpwolke/skin-diseases-cnn)

> ⚠️ Note: Dataset is **not included** in this repo. Please download it separately.

> ⚠️ Note: The trained model file (skin_disease_detector_model.h5) is not included in this repository to reduce size and because it can be easily generated.
To generate the model, run the training script:
python train_model.py
This will train the CNN using the dataset and automatically save the trained model as skin_disease_detector_model.h5 inside the model/ directory.

📁 Directory Structure
```bash
skin-disease-detector/
│
├── static/
│   ├── styles.css
│   └── script.js
│
├── templates/
│   └── index.html
│
├── model/
│   └── skin_disease_detector_model.h5  # Trained model
│
├── app.py
├── train_model.py
├── requirements.txt
└── README.md
```
## 🚀 Run Locally

```bash
git clone https://github.com/ruchitav64/SkinDiseaseDetector.git
cd skin-disease-detector
pip install -r requirements.txt
python app.py



