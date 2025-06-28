# 🌾 Pollen Profiling - Automated Classification of Pollen Grains

Welcome to **Pollen Profiling**, a deep learning-based pollen grain classification project using **TensorFlow** and **Keras**.

---

## 🚀 Project Overview

This project focuses on classifying pollen grain species from microscopic images using a **Convolutional Neural Network (CNN)**. It includes:

- ✅ A custom-trained Keras model (`model.h5`)  
- ✅ Preprocessed pollen image dataset (excluded from Git)  
- ✅ A simple Flask-based web application

---

## 📁 Directory Structure

```
Pollen-Profiling/
│
├── app.py                         # Flask backend & routing
├── model.h5                       # Trained model (gitignored)
├── label_encoder.pkl              # Label encoder (gitignored)
├── dataset/                       # Pollen image dataset (gitignored)
├── static/                        # CSS & uploaded images
├── templates/                     # HTML templates
├── pollen_grain_classification.ipynb  # Training & model building notebook
├── .gitignore
└── README.md
```

---

## 🚫 Files Ignored via `.gitignore`

To keep the repository clean and lightweight:

```gitignore
dataset/
*.h5
*.pkl
*.pyc
__pycache__/
python-*.exe
```

These files must be downloaded or generated locally before running the project.

---

## 📊 Model Details

- **Type:** Convolutional Neural Network (CNN)  
- **Framework:** TensorFlow & Keras  
- **Model File:** `model.h5`  
- **Accuracy:** ~XX% *(replace with your model's accuracy)*  
- **Encoder File:** `label_encoder.pkl` (used for decoding predictions)

---

## 🌐 Web Application (Flask)

The app features:

- 📤 Upload an image
- 🔍 Predict pollen species
- 🧠 Display prediction & confidence level
- 🔁 Logout navigation

---

## ▶️ How to Run

### 🔧 Install dependencies:

```bash
pip install -r requirements.txt
```

### 🚀 Start the Flask server:

```bash
set FLASK_APP=app.py
set FLASK_ENV=development
flask run
```

Open your browser at [http://127.0.0.1:5000](http://127.0.0.1:5000)

---

---

🎥 Demo Video
Watch the full working demo here:
🔗 Pollen Grain Classification - Demo Video https://drive.google.com/file/d/1XDMeMH1Ip4MKBbDlEBdvL4C42rIKF9-C/view?usp=sharing

---

## 📄 Project Notes

- GitHub restricts pushing files larger than **100MB**, so `model.h5` is **excluded** from version control.
- Please generate or request the model and dataset files as needed.

---

## 📧 Contact

**Yamini Mahi Sindhu Mypala**  
GitHub: [mahisindhu](https://github.com/mahisindhu)
