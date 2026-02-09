# 🧠 Autism Spectrum Disorder (ASD) Detection using Machine Learning & Deep Learning

This project focuses on **automatic detection of Autism Spectrum Disorder (ASD)** from facial images using a **hybrid approach** combining **Deep Learning (CNNs)** and **Machine Learning classifiers**.  
Multiple state-of-the-art models are implemented, evaluated, and compared to identify the most effective approach.

---

## 🚀 Key Features

- 📸 Image-based ASD classification (Autistic vs Non-Autistic)
- 🧠 Deep Learning models with **Transfer Learning**
- 🔍 Feature extraction using pre-trained CNNs
- 📊 Multiple ML classifiers for comparison
- 📈 Performance evaluation using accuracy, confusion matrix & classification report
- 🧪 Single-image prediction support

---

## 🛠️ Tech Stack

- **Python**
- **TensorFlow / Keras**
- **Scikit-learn**
- **OpenCV / PIL**
- **Matplotlib & Seaborn**
- **Google Colab**
- **XGBoost**

---

## 📂 Dataset Description

- Dataset consists of **facial images**
- Two classes:
  - `Autistic`
  - `Non_Autistic`
- Images are organized in class-wise directories
- Dataset is split into:
  - **80% Training**
  - **20% Testing**

---

## 🔄 Project Workflow

1. **Dataset Loading from Google Drive**
2. **Image Preprocessing & Validation**
3. **Dataset Splitting (Train/Test)**
4. **Model Training using Transfer Learning**
5. **Feature Extraction using CNNs**
6. **ML Classifier Training**
7. **Evaluation & Visualization**
8. **Single Image Prediction**

---

## 🧠 Deep Learning Models Used

### ✅ VGG16
- Pre-trained on ImageNet
- Custom fully connected layers added
- Fine-tuned last layers
- Input size: `224 × 224`

### ✅ InceptionV3
- Advanced CNN architecture
- Global Average Pooling
- Fine-tuning enabled
- Input size: `299 × 299`

---

## 🤖 Machine Learning Models Used

CNN-extracted features are fed into:

| Model | Purpose |
|-----|--------|
| Logistic Regression | Baseline classifier |
| Random Forest | Ensemble learning |
| XGBoost | Boosted tree classifier |

---

## 📊 Model Evaluation Metrics

- **Accuracy**
- **Confusion Matrix**
- **Precision, Recall, F1-score**
- **Training vs Validation Curves**
- **Class-wise Performance Analysis**

Visualization includes:
- Heatmaps for confusion matrix
- Accuracy & loss curves
- Feature importance (where applicable)

---

## 🔍 Single Image Prediction

The project supports **predicting ASD from a single image**:
- Image is preprocessed
- Features extracted using CNN
- Final prediction made using trained ML classifier




