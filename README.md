
# Mental Health and Stress Prediction Using Neural Networks

## 📖 Overview

This repository contains the implementation of a project aimed at **predicting mental health and stress levels** using **neural networks** and **psychological signals**. The project utilizes advanced machine learning techniques to analyze physiological signals and predict stress levels and mental health conditions effectively. 

Mental health and stress have become pressing issues in today's world. Leveraging **multimodal data** and neural networks, this project explores how physiological signals such as heart rate, temperature, and electrodermal activity can be processed to detect stress and mental health challenges.

---

## 📂 Dataset

The dataset used for this project can be accessed from the following link:

[WESAD Dataset - Download Here](https://drive.google.com/file/d/1c8nsz6pcf4Jp-9Q13VRV2FbWp67TxBHj/view?usp=drive_link)

### **About the Dataset:**
- The dataset contains **multimodal physiological data** collected from participants in a controlled environment.
- Key signals include:
  - **Electrodermal Activity (EDA):** Measures skin conductance, a key indicator of stress.
  - **Temperature (TEMP):** Tracks variations in body temperature during stress.
  - **Accelerometer (ACC):** Captures movement data for additional insights.
- Stress levels are labeled, enabling supervised machine learning tasks.

---

## 🛠️ Key Features
- **Neural Network Architecture**: Utilizes **Recurrent Neural Networks (RNN)** to capture temporal dependencies in the physiological signals.
- **Feature Engineering**: Employs techniques such as z-score normalization and sequence padding for robust preprocessing.
- **Stress Classification**: Predicts whether the participant is under stress or in a baseline condition.
- **Evaluation Metrics**: Precision, recall, F1-score, and accuracy are computed to assess model performance.

---

## 🧠 Techniques Used
- **Recurrent Neural Networks (RNN):** Designed to handle sequential data effectively.
- **Loss Function:** Binary cross-entropy for classification tasks.
- **Optimization Algorithm:** Adam optimizer for efficient training.
- **Preprocessing Techniques:**
  - Z-score normalization for feature scaling.
  - Sequence padding to standardize input length.

---

## 📈 Results
- Achieved 77% **accuracy** in predicting stress levels.
- Demonstrated the significance of multimodal sensor data in stress detection.
- Showcased the capability of neural networks to analyze complex physiological data.


## 🛠️ How to Run

### Prerequisites:
- Python 3.x
- Required libraries:
  - TensorFlow/Keras
  - NumPy
  - Pandas
  - Scikit-learn
  - Matplotlib


---

## 🌟 Future Enhancements
- Implement **LSTM** or **GRU** models to better capture long-term dependencies in physiological data.
- Incorporate additional features like **heart rate variability (HRV)** and **respiration rates**.
- Develop a user-friendly interface for deploying the model in real-world wearable devices.


