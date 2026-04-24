# medical-image-classification-cnn
#### 📌 Goal

The goal of this project was to develop an automated system for medical image classification to enable diagnosis of periodontal disease. Manual classification of medical images is time-consuming, making it inefficient in healthcare environments with heavy workloads. This project  explored the use of Convolutional Neural Networks (CNNs) to improve classification efficiency and accuracy.

---

#### 🔬 Methodology

1. Processed a periodontal disease dataset consisting of “Normal” and “Inflammation” classes
2. Performed image preprocessing, including resizing and format standardization
3. Applied data augmentation techniques (rescaling, shearing, zooming, flipping) to improve model generalization
4. Designed a 10-layer CNN architecture with convolutional, pooling, dropout, and dense layers using Keras Sequential API
5. Configured model training using Adam optimizer, binary cross-entropy loss, and accuracy metrics
6. Trained and evaluated the model using training, validation, and test datasets

---

#### 📊 Results

- Achieved:
    - **Accuracy:** 70.45%
    - **Precision:** 70.20%
    - **Recall:** 92.86%
    - **F1-Score:** 80.00%
- Model demonstrated strong recall, indicating effective detection of inflammation cases
- Successfully validated the potential of CNN for medical image classification tasks
