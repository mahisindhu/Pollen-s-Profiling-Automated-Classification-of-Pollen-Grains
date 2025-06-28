# Pollen-s-Profiling-Automated-Classification-of-Pollen-Grains
This project focuses on automating the classification of pollen grains using deep learning. It includes a trained CNN model and a Flask web application to provide an interactive interface for users to upload images and receive predictions.

Features:

Image classification using Convolutional Neural Networks (CNN)

Preprocessed dataset of pollen grain images

Flask web interface for real-time predictions

Label encoding for consistent class identification

Upload and predict image classes with confidence scores

Project Structure:

pollen_classification/
├── app.py                       # Flask web application
├── model.h5                    # Trained Keras model (ignored in repo)
├── label_encoder.pkl           # Label encoder for class names (ignored in repo)
├── dataset/                    # Pollen image dataset (ignored in repo)
├── templates/                  # HTML templates (index, predict, logout)
├── static/                     # Static files (CSS, uploaded images)
├── pollen_grain_classification.ipynb  # Model training notebook
└── .gitignore                  # Files/folders to exclude from version control


Instructions to Run:

Clone the repository and navigate to the directory.

Install required Python packages.

Place model.h5 and label_encoder.pkl in the root folder.

Run app.py using Flask.

Open the browser at http://127.0.0.1:5000 to use the app.

Note:
The model file (model.h5) exceeds GitHub’s upload limit and must be added manually.

Applications:

Botanical research

Pollen classification automation

Image-based taxonomy tools
