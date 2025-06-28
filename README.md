🌾 Pollen Profiling: Automated Classification of Pollen Grains
This project 🌱 focuses on the automated classification of pollen grains using a deep learning model. It aims to help researchers and botanists accurately identify different pollen species 🧬 using image-based analysis.

📁 Project Structure

pollen_classification/
├── app.py                          # 🧠 Flask web app
├── model.h5                        # 🤖 Trained Keras model (gitignored)
├── label_encoder.pkl               # 🏷️ Label encoder (gitignored)
├── dataset/                        # 🖼️ Pollen image dataset (gitignored)
├── templates/                      # 🧩 HTML files (index, predict, logout)
├── static/                         # 🎨 Static assets (CSS, images)
├── pollen_grain_classification.ipynb  # 📓 Model training notebook
└── .gitignore                      # 🚫 Files ignored by Git

🧠 Model Overview
This project uses a Convolutional Neural Network (CNN) to classify images of pollen grains. The model is trained on a labeled dataset of pollen images and predicts the class along with confidence scores 📊.

🌐 Web Interface (Flask)
The user-friendly web app offers:

🏠 Home page for uploading images

🔍 Prediction with class name and confidence

🔁 Logout and navigation

🚫 Git-ignored Files
To keep the repo clean and within GitHub's limits:

model.h5 (⚠️ >100MB)

label_encoder.pkl (🔐 Serialization)

dataset/ (📂 Training images)

Python installer & __pycache__/ (⚙️)

🚀 How to Run
🧬 Clone the repo:

git clone https://github.com/mahisindhu/Pollen-profiling.git
cd Pollen-profiling
📦 Install dependencies:

🏃 Run the Flask app:


set FLASK_APP=app.py
set FLASK_ENV=development
flask run
🔗 Open in browser:
http://127.0.0.1:5000
✅ Requirements
Python 3.10+

Flask 🌐

TensorFlow/Keras 🤖

NumPy, scikit-learn 📚
