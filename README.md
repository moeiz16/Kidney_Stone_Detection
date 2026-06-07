# Kidney Stone Detection using CNN and SVM with GUI

A machine learning and deep learning-based biomedical application designed to detect and classify kidney stones from CT scan images. This project combines the deep feature extraction capabilities of a **Convolutional Neural Network (CNN)** with the robust classification power of a **Support Vector Machine (SVM)**, wrapped inside an intuitive Graphical User Interface (GUI).

## 🚀 Features
- **Hybrid Architecture:** Uses a CNN to extract complex visual features from CT scan images and a Support Vector Machine (SVM) as the top-level classifier for precise detection.
- **Interactive GUI:** Easy-to-use desktop interface for uploading CT images, viewing preprocessing results, and getting instant diagnostic output.
- **Image Preprocessing:** Includes basic filtering and normalization pipelines tailored for CT scan analysis.
- **Performance Evaluation:** Provides accurate classification metrics differentiating normal scans from those showing kidney stone anomalies.

## 🛠️ Tech Stack & Libraries
- **Language:** Python
- **Deep Learning / ML:** TensorFlow / Keras, Scikit-Learn
- **Image Processing:** OpenCV, PIL (Pillow), NumPy
- **GUI Framework:** Tkinter / PyQt (depending on implementation choice)
- **Development Environment:** Jupyter Notebook (for model training) & Python Scripts (for execution)

## 📁 Repository Structure
```text
├── dataset/                  # Sample or pointer to CT scan images (Normal / Stone)
├── models/                   # Saved weights for trained CNN and SVM models (.h5, .pkl)
├── notebooks/                # Jupyter notebooks tracking model training & evaluation
├── app.py / gui.py           # Main application script to launch the GUI
├── requirements.txt          # File containing necessary dependencies
└── README.md                 # Project documentation
