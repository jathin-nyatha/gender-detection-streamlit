# 🧠 Real-Time Gender Detection using Deep Learning & OpenCV

This project implements a real-time gender detection system using computer vision and deep learning. The model is trained on facial features and can predict gender via webcam input using a custom-trained CNN.

![Demo](assets/demo.gif)

---

## 🚀 Features
- Real-time gender prediction via webcam
- Custom-trained Convolutional Neural Network (CNN)
- Uses OpenCV for face detection
- Trained on a custom face dataset
- Accuracy/Loss visualization included

---

## 📁 Project Structure
```
gender-detection-streamlit/
├── gender_dataset_face/      # Dataset: man/woman face images
├── detect_gender_webcam.py   # Real-time gender detection
├── train.py                  # Model training script
├── gender_detection.model    # Trained model (CNN)
├── plot.png                  # Accuracy/Loss visualization
├── requirements.txt          # Dependencies
├── .gitignore
├── LICENSE
└── README.md
```

---

## 🛠️ Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/jathin-nyatha/gender-detection-streamlit.git
cd gender-detection-streamlit
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Train the Model (Optional)
```bash
python train.py
```

### 4. Run the Real-Time Gender Detector
```bash
python detect_gender_webcam.py
```

---

## 🧠 Model Details
- CNN with Conv2D, MaxPooling, Dense, Dropout
- Dataset: Custom dataset organized as `/man` and `/woman`
- Face detection via OpenCV Haar Cascades

---

## 📊 Training Performance

![Training Plot](plot.png)

---

## 📄 License
This project is licensed under the [MIT License](LICENSE).

---

## 👨‍💻 Author
**Jathin Nyatha**  
[GitHub](https://github.com/jathin-nyatha)

---

## ⭐ Contributions
Contributions, issues, and feature requests are welcome! Feel free to ⭐ the repo.
