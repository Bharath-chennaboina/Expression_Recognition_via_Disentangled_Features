#  Facial Expression Recognition using Deep Learning

A real-time Facial Expression Recognition system developed as part of the **EE656 Course Project**. The project uses Deep Learning and Computer Vision techniques to detect human faces and classify facial expressions into different emotion categories.

---

##  Project Overview

Facial Expression Recognition (FER) is an important application of Artificial Intelligence and Computer Vision that enables machines to understand human emotions from facial images. This project detects faces from images or webcam input and predicts the corresponding emotion using a trained Convolutional Neural Network (CNN).

---

##  Features

- Real-time facial expression detection
- Face detection using OpenCV
- Emotion classification using Deep Learning
- User-friendly interface
- Supports webcam/live video input
- Fast and accurate predictions

---

##  Emotion Classes

The model classifies the following emotions:

-  Happy
-  Sad
-  Angry
-  Fear
-  Surprise
-  Neutral
-  Disgust

---

##  Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

## 📂 Project Structure

```
Facial-Expression-Recognition/
│
├── dataset/
├── models/
├── notebooks/
├── src/
│   ├── train.py
│   ├── predict.py
│   ├── webcam.py
│   └── utils.py
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

##  Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/facial-expression-recognition.git
```

Move into the project folder:

```bash
cd facial-expression-recognition
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

##  Running the Project

For webcam prediction:

```bash
python webcam.py
```

For image prediction:

```bash
python predict.py
```

To train the model:

```bash
python train.py
```

---

##  Model

The model is based on a Convolutional Neural Network (CNN) trained on a facial expression dataset. It learns facial features through multiple convolutional and pooling layers before classifying emotions using a Softmax output layer. CNN-based FER models are widely used for recognizing emotions from facial images. :contentReference[oaicite:0]{index=0}

---

##  Applications

- Human-Computer Interaction
- Smart Surveillance
- Mental Health Monitoring
- Driver Fatigue Detection
- Online Learning Analytics
- Healthcare
- Customer Experience Analysis

---

##  Future Improvements

- Improve prediction accuracy using transfer learning.
- Support multiple face detection simultaneously.
- Deploy as a web application.
- Optimize for mobile devices.
- Add emotion statistics dashboard.

---



---

##  License

This project is developed for educational purposes as part of the **EE656 Course Project**.
