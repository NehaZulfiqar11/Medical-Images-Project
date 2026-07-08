# Alzheimer's Disease Classification Using Deep Learning

## Overview

This project presents a deep learning-based framework for the automatic classification of Alzheimer's disease using brain MRI images. The proposed approach utilizes convolutional neural networks (CNNs) for feature extraction and image classification to assist in the early detection of Alzheimer's disease. The implementation is developed using Python in Google Colab and leverages TensorFlow/Keras for model development.

The project includes data preprocessing, model training, validation, performance evaluation, and visualization of classification results.

---

## Features

- Alzheimer's MRI image classification
- Deep learning-based image analysis
- Image preprocessing and normalization
- Training, validation, and testing pipeline
- Performance evaluation using classification metrics
- Visualization of training history
- Google Colab implementation
- Easy-to-use notebook

---

## Dataset

The project uses an Alzheimer's MRI dataset containing multiple disease categories.

Typical classes include:

- Non Demented
- Very Mild Demented
- Mild Demented
- Moderate Demented

The dataset is preprocessed before model training by resizing images, normalizing pixel values, and organizing them into training, validation, and testing sets.

---

## Methodology

The overall workflow of the proposed system is shown below:

```
MRI Dataset
      │
      ▼
Image Loading
      │
      ▼
Image Preprocessing
(Resize, Normalization)
      │
      ▼
Dataset Splitting
(Training, Validation, Testing)
      │
      ▼
Deep Learning Model
      │
      ▼
Model Training
      │
      ▼
Prediction
      │
      ▼
Performance Evaluation
      │
      ▼
Classification Results
```

---

## Technologies Used

- Python
- Google Colab
- TensorFlow
- Keras
- NumPy
- OpenCV
- Matplotlib
- Scikit-learn

---

## Performance Evaluation

The trained model can be evaluated using various performance metrics, including:

- Training Accuracy
- Validation Accuracy
- Training Loss
- Validation Loss
- Confusion Matrix
- ROC Curve
- Precision
- Recall
- F1-Score

---

## Project Structure

```
Alzheimer-Disease-Classification/
│
├── Alzheimer_Classification.ipynb
├── README.md
├── requirements.txt
│
├── Dataset/
│
├── Results/
│   ├── Accuracy.png
│   ├── Loss.png
│   ├── Confusion_Matrix.png
│   ├── ROC_Curve.png
│   ├── Methodology.png
│   └── Sample_Predictions.png
│
└── Models/
```

---

## Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Alzheimer-Disease-Classification.git
```

Navigate to the project directory

```bash
cd Alzheimer-Disease-Classification
```

Install the required libraries

```bash
pip install -r requirements.txt
```

---

## Running the Project

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Upload or mount the MRI dataset.
3. Install the required Python packages.
4. Execute all notebook cells sequentially.
5. Train the deep learning model.
6. Evaluate the trained model.
7. Visualize the generated performance metrics.

---

## Expected Results

The notebook generates:

- Training Accuracy Curve
- Validation Accuracy Curve
- Training Loss Curve
- Validation Loss Curve
- Confusion Matrix
- ROC Curve
- Classification Report
- Sample Predictions

---

## Future Improvements

- Integrate transfer learning models such as EfficientNet and Vision Transformer.
- Improve classification performance using ensemble learning.
- Apply data augmentation techniques to improve model generalization.
- Optimize the model for real-time clinical applications.
- Deploy the model using Streamlit or Flask for web-based diagnosis.

---

## Author

**Neha Zulfiqar**

PhDAIF25M005

---

## Supervisor

**Dr. Muhammad Farooq**

---

## License

This project is intended for academic and research purposes only. It may be used for educational and non-commercial research with proper acknowledgment.

---

## Acknowledgement

The author sincerely thanks **Dr. Muhammad Farooq** for his valuable guidance and continuous support throughout this research project. Appreciation is also extended to the developers of TensorFlow, Keras, Scikit-learn, and the contributors of the Alzheimer's MRI dataset for providing open-source resources that made this work possible.
