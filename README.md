# Spacecraft-Pose-Estimator

Developed a ResNet-50-based deep learning model to estimate spacecraft orientation and position from images. Built with TensorFlow and Streamlit, powered by the SPEED dataset.

## 📖 Overview
This project estimates the 3D pose of spacecraft using a trained deep learning model. Given an input image, the model outputs:
- Orientation as a quaternion vector (qₓ, qᵧ, q𝓏, q𝓌)
- Translation (x, y, z) representing position

It also provides:
- Confidence score
- Downloadable report (ZIP)
- Visualizations (Radar chart, 3D scatter plot)

- ## ✨ Features
- Upload spacecraft image
- Quaternion + translation predictions
- Radar and 3D scatter visualizations
- Confidence score indicator
- Downloadable result report (ZIP)
- Streamlit-based responsive UI
