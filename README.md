
# 🌿 AI-Powered Plant Disease Detection

This project leverages deep learning and computer vision to automatically detect plant leaf diseases from images. Using a custom-trained Convolutional Neural Network (CNN), the model classifies leaves into three categories: **Healthy**, **Powdery**, and **Rust**. The goal is to help farmers and agricultural experts identify diseases early and take timely action.

## 🔍 Features
- Trained on a labeled dataset of plant leaf images
- Achieves high accuracy in classifying plant diseases
- Streamlit-based user interface for uploading and predicting disease from images
- Treatment suggestions based on disease classification (optional extension)

## 📁 Dataset
The dataset is divided into three classes:
- **Healthy**
- **Powdery**
- **Rust**
[text](https://www.kaggle.com/datasets/rashikrahmanpritom/plant-disease-recognition-dataset/data)

And structured into:
- `Train/`
- `Validation/`
- `Test/`

## 🚀 How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/Anzar1008/plant-disease-detection.git
   cd plant-disease-detection
   ```

2. Activate the environment:
   ```bash
   conda activate plantdisease
   ```

3. Run the app:
   ```bash
   streamlit run plant_disease_app.py
   ```

4. Upload a plant leaf image to get an instant prediction.

## 📊 Model
- Custom CNN model built with TensorFlow and Keras
- Image preprocessing: resizing to 224x224, normalization
- Model trained with early stopping and evaluated using:
  - Accuracy
  - Precision
  - Recall
  - F1 Score

## 📦 Libraries Used
- TensorFlow / Keras  
- NumPy  
- PIL (Pillow)  
- Streamlit  
- Scikit-learn

## 📌 Future Work
- Add more disease classes and plant types
- Deploy on Streamlit Cloud or Hugging Face Spaces
- Add real-time webcam-based detection
- Integrate multilingual support for farmers

---

*Created with ❤️ for agriculture and AI innovation.*
