# 🎙️ Speech Emotion Recognition using Deep Learning

A Deep Learning-based Speech Emotion Recognition (SER) system that classifies human emotions from speech using audio signal processing, feature extraction, and Convolutional Neural Networks (CNNs).

---

## 📌 Project Overview

Speech Emotion Recognition (SER) is the process of identifying human emotions from voice signals. Emotional cues such as pitch, tone, rhythm, and energy can be analyzed to classify emotions like happiness, sadness, anger, fear, and more.

This project leverages audio feature extraction techniques and deep learning to build an accurate emotion classification model using multiple publicly available speech datasets.

---

## 🚀 Features

- Speech emotion classification using Deep Learning
- Audio preprocessing and visualization
- Data augmentation for improved generalization
- Feature extraction using Librosa
- CNN-based emotion classification
- Performance evaluation with classification metrics
- Training history visualization

---

## 🎯 Emotions Classified

- 😀 Happy
- 😢 Sad
- 😠 Angry
- 😨 Fear
- 😐 Neutral
- 🤢 Disgust
- 😲 Surprise
- 😌 Calm

---

## 📂 Datasets Used

This project combines four popular speech emotion datasets:

- 🎤 RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song)
- 🎤 CREMA-D (Crowd-sourced Emotional Multimodal Actors Dataset)
- 🎤 SAVEE (Surrey Audio-Visual Expressed Emotion)
- 🎤 TESS (Toronto Emotional Speech Set)

---

## 🛠️ Tech Stack

- Python
- Jupyter Notebook
- TensorFlow / Keras
- Scikit-learn
- Librosa
- NumPy
- Pandas
- Matplotlib
- Seaborn

---

## 📚 Libraries Used

```python
pandas
numpy
librosa
matplotlib
seaborn
tensorflow
keras
scikit-learn
IPython
```

---

## 🔄 Project Workflow

1. Data Collection
2. Audio Preprocessing
3. Exploratory Data Analysis (EDA)
4. Audio Visualization
5. Data Augmentation
6. Feature Extraction
7. Data Preprocessing
8. CNN Model Training
9. Model Evaluation
10. Emotion Prediction

---

## 🎵 Audio Feature Extraction

The following audio features are extracted using **Librosa**:

- Zero Crossing Rate (ZCR)
- Chroma STFT
- MFCC (Mel Frequency Cepstral Coefficients)
- Delta MFCC
- Delta-Delta MFCC
- Root Mean Square (RMS)
- Mel Spectrogram
- Spectral Contrast
- Tonnetz

---

## 🔊 Data Augmentation Techniques

To improve model performance and reduce overfitting:

- Noise Injection
- Time Stretching
- Pitch Shifting

---

## 🧠 Deep Learning Model

The model is built using **TensorFlow/Keras** with:

- Conv1D Layers
- Batch Normalization
- Max Pooling
- Dropout
- Dense Layers
- Early Stopping
- ReduceLROnPlateau

---

## 📊 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

---

## 📁 Project Structure

```
Speech-emotion-recognition/
│
├── SER.ipynb
├── speech-emotion-recognition.ipynb
├── ser_model.h5
├── ser_model.pkl
├── README.md
```

---

## ▶️ Installation

Clone the repository

```bash
git clone https://github.com/Garima53/Speech-emotion-recognition.git
```

Navigate to the project

```bash
cd Speech-emotion-recognition
```

Install dependencies

```bash
pip install -r requirements.txt
```

or

```bash
pip install numpy pandas matplotlib seaborn librosa scikit-learn tensorflow keras jupyter
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

---

## 📈 Results

The model successfully classifies multiple speech emotions using extracted audio features and deep learning techniques.

Key highlights:

- Multi-dataset training
- Robust audio preprocessing
- Feature engineering with Librosa
- CNN-based classification
- Data augmentation for improved generalization

---

## 🚀 Future Improvements

- Transformer-based Speech Emotion Recognition
- LSTM/Bi-LSTM Models
- Real-time microphone emotion detection
- Flask/FastAPI deployment
- Streamlit web application
- Model optimization and hyperparameter tuning

---

## 👩‍💻 Author

**Garima Gupta**

Software Engineer | Machine Learning | Deep Learning | Java | Spring Boot | Angular

- GitHub: https://github.com/Garima53
- LinkedIn: *Add your LinkedIn profile*

---

## ⭐ Support

If you found this project useful, don't forget to ⭐ star this repository!
