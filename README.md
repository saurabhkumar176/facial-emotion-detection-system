# 🎭 Real-Time Facial Emotion Detection with Deep Learning

This project implements a **real-time facial emotion recognition system** using a **Convolutional Neural Network (CNN)** built with TensorFlow and Keras. It captures webcam video input, detects faces using OpenCV’s Haar cascades, and classifies emotions into one of seven categories.

---

## 📸 Demo

![Screenshot 2024-12-09 205438](https://github.com/user-attachments/assets/2a3274c0-bfef-418e-a968-b37ee378b095)



---

## 🧠 Supported Emotions

The model predicts one of the following emotions:
- 😠 **Angry**
- 🤢 **Disgust**
- 😨 **Fear**
- 😄 **Happy**
- 😐 **Neutral**
- 😢 **Sad**
- 😲 **Surprise**

---

## 🗂️ Project Structure
├── realtimedetection.py # Real-time detection script using webcam
├── trainmodel.ipynb # Jupyter Notebook to train the emotion model
├── facialemotionmodel.h5 # Trained CNN model for emotion classification
├── requirements.txt # Python dependencies
└── README.md # Project documentation (this file)

yaml
Copy
Edit

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/emotion-detector.git
cd emotion-detector
2. Install Dependencies
Install all required libraries using:

bash
Copy
Edit
pip install -r requirements.txt
3. Run Real-Time Emotion Detection
bash
Copy
Edit
python realtimedetection.py
Press Esc to exit the webcam feed.

🏗️ Model Training
If you wish to train the model yourself:

Open the trainmodel.ipynb notebook.

It uses the FER-2013 dataset.

The model architecture includes Conv2D layers, BatchNorm, MaxPooling, and Dense layers with softmax output for 7 classes.

📌 Note: Training can take time depending on your hardware.

📦 Dependencies
Main libraries used in this project:

TensorFlow

Keras

OpenCV

NumPy

Pandas

Scikit-learn

tqdm

Jupyter Notebook

See requirements.txt for full details.

✅ To-Do (Suggestions)
 Add model accuracy and confusion matrix plots

 Deploy using Flask/Django for web access

 Integrate voice feedback using text-to-speech

 Optimize model for mobile or edge devices

📃 License
This project is released under the MIT License. Feel free to use, modify, and share it with proper credits.

🙋‍♂️ Acknowledgments
FER-2013 Dataset

TensorFlow & Keras documentation

OpenCV community











Tools






