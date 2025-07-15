# 🎭 Emotion Detection with VGG16 (FER2013 Dataset)

This project implements an emotion recognition system using **Transfer Learning** with a pre-trained **VGG16** model. The system classifies facial expressions into 7 emotions using the **FER2013 dataset**.

## 📌 Features
- Fine-tuned VGG16 on 48x48 grayscale face images
- Image preprocessing and real-time augmentation
- Emotion classes: Angry, Disgust, Fear, Happy, Sad, Surprise, Neutral
- Visual training metrics (accuracy, loss)

## 🚀 Technologies Used
- Python, TensorFlow/Keras
- VGG16 (ImageNet weights)
- FER2013 Dataset (Kaggle)
- Matplotlib, NumPy, Pandas

## 📁 Structure
- `Emotion_Detection_with_VGG16_Transfer_Learning_on_FER2013.ipynb`: Main notebook
- `/train` and `/test`: Folder structure expected for training/testing
- `.h5`: Model weights (if saved separately)

## 📊 Results
- Achieved >60% accuracy after fine-tuning
- Model generalizes well on unseen faces


## ✅ How to Run
1. Upload `FER2013` images in proper `/train` and `/test` folders.
2. Run the notebook on [Google Colab](https://colab.research.google.com/).
3. Evaluate model and test on custom images.

## 📌 Future Work
- Convert to Streamlit app for live emotion detection
- Integrate webcam for real-time face emotion recognition

## 🔗 Dataset
[Kaggle: FER2013 Dataset](https://www.kaggle.com/datasets/msambare/fer2013)

---

💻 **Author:** [@kashifcodes92](https://github.com/kashifcodes92)  
📫 Feel free to connect or contribute!
