# Breast Cancer Diagnosis Predictor

## Overview

This project is a machine learning-based web application developed using **Python** and **Streamlit** to predict whether a breast tumor is **Benign** or **Malignant** based on diagnostic measurements.

The application allows users to enter tumor characteristics through an interactive interface, processes the data using a trained machine learning model, and presents the prediction along with confidence scores and visual insights.

This project is intended for educational purposes to demonstrate the practical application of machine learning in healthcare and should not be used for clinical diagnosis.

---

## Features

- Interactive Streamlit interface
- Real-time prediction
- Benign/Malignant classification
- Prediction probability
- Radar chart visualization
- User-friendly dashboard

---

## Dataset

The model is trained using the **Breast Cancer Wisconsin (Diagnostic)** dataset, a publicly available dataset widely used for machine learning research and educational projects.

---

## Installation

Create a virtual environment:

```bash
conda create -n breast-cancer-diagnosis python=3.10
```

Activate it:

```bash
conda activate breast-cancer-diagnosis
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Usage

Run the application using:

```bash
streamlit run app/main.py
```

The application will open in your browser, where you can enter diagnostic measurements and receive an instant prediction with visualization.

---

## Project Structure

```
app/
assets/
data/
model/
README.md
requirements.txt
```

---

## Learning Note

This project was built as part of my machine learning learning journey and is based on concepts demonstrated in publicly available breast cancer prediction projects. I used it to understand model training, preprocessing, and deployment with Streamlit while experimenting and making my own improvements.

---

## Author

Priyanshu Yadav
