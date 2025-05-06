**Brain Tumor Detection Using Deep Learning**
A deep learning project for classifying brain MRI scans into Tumor or No Tumor using a Convolutional Neural Network (CNN) trained on MRI datasets.

Table of Contents
Overview
Tech Stack
How to Run
Model Architecture
License

**Project Overview**
This project automates the detection of brain tumors in MRI images using a CNN trained on a labeled dataset. It includes:

Image preprocessing using OpenCV/Keras
A CNN model trained using TensorFlow/Keras
Real-time image classification with confidence scores

**Tech Stack**
Python
TensorFlow / Keras
OpenCV
Jupyter Notebook or Google Colab (for experiments)

How to Run
bash
Copy
Edit
# 1. Clone the repo
git clone https://github.com/YOUR_USERNAME/Brain-Tumor-Detection.git
cd Brain-Tumor-Detection

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run the code
Brain_MRI.ipynb

🧠 Model Architecture
text
Copy
Edit
Input Layer (150x150x3)
→ Conv2D → MaxPooling
→ Conv2D → MaxPooling
→ Flatten → Dropout
→ Dense → Dense (Softmax)
Optimizer: Adam

Loss: Categorical Crossentropy

Accuracy: ~95% on validation set


Jupyter Notebook
Code available in notebooks/brain_tumor_detection.ipynb

📁 File Structure
cpp
Copy
Edit
Brain-Tumor-Detection/
├── app.py
├── train_model.py
├── utils.py
├── models/
├── static/
├── templates/
├── requirements.txt
└── README.md
📄 License
MIT License — feel free to use and modify!
