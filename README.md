# 🌾 Paddy Disease Classification using Deep Learning

## 📌 Project Overview
This project focuses on building a **deep learning-based image classification model** to identify **10 different paddy leaf diseases**. The aim is to assist farmers and researchers by providing a fast, automated, and reliable method of detecting crop diseases using computer vision techniques.

By leveraging **EfficientNet with Transfer Learning**, along with **data balancing and augmentation**, the model achieves high accuracy even with a limited dataset.

---

## 📂 Dataset
- The dataset consists of **10 classes** of paddy diseases.  
- Each class originally had an **imbalanced number of images**.  
- To ensure fairness:
  - A balanced dataset was created with **250 images per class (total 2500 images)**.  
  - Data augmentation was applied to simulate real-world variations.  

---

## 🛠️ Tech Stack & Tools
- **Programming Language**: Python  
- **Libraries**: TensorFlow/Keras, NumPy, Pandas, Matplotlib, Seaborn  
- **Model Architecture**: EfficientNet (Transfer Learning)  
- **Visualization**: Matplotlib & Seaborn for EDA and training plots  
- **Environment**: Jupyter Notebook / Google Colab  

---

## 🚀 Project Workflow
1. **Data Preparation**
   - Loaded the dataset and performed Exploratory Data Analysis (EDA).  
   - Balanced the dataset by randomly sampling 250 images per class.  
   - Applied augmentation (rotation, flip, zoom, shift).  

2. **Model Development**
   - Used **EfficientNet** as the base model with transfer learning.  
   - Added custom dense layers for classification.  
   - Trained on balanced data with 80-20 train-validation split.  

3. **Evaluation**
   - Achieved strong accuracy across validation sets.  
   - Visualized training curves (loss vs. accuracy).  
   - Tested on unseen data for real-world validation.  

---

## 📊 Results
- The model effectively classifies paddy diseases into 10 categories.  
- Data balancing + augmentation improved performance.  
- Results show promise for **real-world agricultural applications**.  

---

## 📷 Sample Visualizations
- **Class Distribution Bar Plot**  
- **Training vs Validation Accuracy/Loss**  
- **Confusion Matrix** for evaluating predictions  

---

## 🔮 Future Scope
- Expand dataset with **real-world farm images**.  
- Explore other models like ResNet, DenseNet, Vision Transformers.  
- Deploy as a **mobile/web application** for farmers.  
- Integrate with drones or IoT devices for large-scale disease monitoring.  

---

## 📌 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/paddy-disease-classification.git
   cd paddy-disease-classification
