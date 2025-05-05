# Tumor Invasion: Brain Tumor Detection and Visualization

**Tumor Invasion** is an AI-powered graduation project designed to improve the diagnosis and surgical planning of brain tumors. Leveraging deep learning, interpretable models, and immersive 3D visualization through virtual reality, this platform aims to assist medical professionals in identifying and understanding brain tumors more effectively.

## 🔍 Project Overview
- **Goal**: Enhance brain tumor diagnosis and simulation using AI and VR.
- **Challenge**: Tumors vary by location and invasiveness; image distortions complicate detection.
- **Solution**: Combine CNNs, segmentation, Grad-CAM, and a secure web/mobile app for accurate predictions and visualization.

## 🚀 Features
- AI-based tumor detection and classification
- 2D and 3D segmentation models
- Grad-CAM for model interpretability
- Flask backend for secure image upload and prediction
- Flutter-based mobile app for scan viewing
- 3D tumor visualization in virtual reality

## 📂 Folder Structure
```
Graduation_Project-main/
├── AI Models/           # Jupyter notebooks for model training and evaluation
├── Flask/               # Backend server for inference and API endpoints
├── Flutter/             # Mobile application frontend (Dart)
├── README.md            # Project documentation
```

## 🧠 Core Technologies
- **Python**, **NumPy**, **Pandas**, **Matplotlib**, **Seaborn**
- **TensorFlow**, **Keras**, **OpenCV**
- **Flask** (backend API)
- **Flutter** (frontend mobile interface)
- **Grad-CAM**, **Segmentation**, **3D Modeling**

## ⚙️ How to Run

### Backend (Flask)
```bash
cd Flask
pip install -r requirements.txt
python app.py
```

### Mobile App (Flutter)
```bash
cd Flutter
flutter pub get
flutter run
```

## 📦 Packages
- flask
- tensorflow
- keras
- opencv-python
- numpy
- matplotlib
- seaborn

## 📈 Sample Notebooks
Located in the `AI Models/` folder:
- `2D Segmentation.ipynb`
- `3D Segmentation.ipynb`
- `BrainTumor-CNN.ipynb`
- `GradCaam.ipynb`

## 🙋‍♀️ Contribution
This project was developed as a graduation project and is not currently open for external contributions.

## 📫 Contact
If you'd like to learn more or collaborate, please reach out via LinkedIn or email.

---

> Empowering medical professionals with intelligent diagnostic tools.
