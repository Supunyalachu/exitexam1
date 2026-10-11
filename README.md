# Mudra Recognition Using Deep Learning

## Project Overview
This project classifies Bharatanatyam hand gestures (Mudras) into five categories using a Convolutional Neural Network (CNN).

**Classes:** Musti, Pataka, Sikhara, Simhamukha, and Trisula.

## Project Contents
- `mudra_recognition.ipynb` — Data analysis, model training, evaluation, and error analysis.
- `app.py` — Interactive Streamlit application.
- `mudra_model.keras` — Trained CNN model.
- `labels.json` — Class labels in prediction order.
- `requirements.txt` — Required Python packages.
- `screenshots/` — Dataset preview and missing-value analysis.

## Installation
1. Clone or download this repository.
2. Install Python and create a virtual environment.
3. Install dependencies:

```bash
pip install -r requirements.txt
```

## Run the Application

Ensure that `app.py`, `mudra_model.keras`, and `labels.json` are in the project directory.

```bash
streamlit run app.py
```

Open the local URL displayed in the terminal.

## Model Evaluation
The notebook evaluates the model using accuracy, macro precision, macro recall, macro F1-score, a confusion matrix, and misclassification analysis.

## Dataset
The dataset contains 2,000 images across five Mudra classes, with 400 images per class. The class distribution is balanced.

## Limitations
The current model's test accuracy is approximately 43.67%. Predictions may be incorrect, particularly for visually similar hand gestures.
