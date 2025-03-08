## 🏥 Heart Disease Prediction using Deep Learning  

### 📌 Overview  
This project focuses on predicting **heart disease** using **deep learning models**:  
- **CNN (Convolutional Neural Network)**  
- **LSTM (Long Short-Term Memory)**  
- **GRU (Gated Recurrent Unit)**  

The dataset is preprocessed and split into training/testing sets, and multiple evaluation metrics are used to compare model performance.  

---

### 📂 Dataset  
The dataset contains selected features related to **heart disease diagnosis**. The target variable (`Heart Disease`) is **one-hot encoded** for classification.  

---

### ⚙️ Technologies Used  
- Python 🐍  
- TensorFlow & Keras  
- NumPy & Pandas  
- Scikit-Learn  
- Matplotlib & Seaborn  

---

### 🚀 Models Implemented  
- **CNN**: Feature extraction with `Conv1D` layers.  
- **LSTM**: Handles sequential dependencies in data.  
- **GRU**: Optimized alternative to LSTM.  

Each model is trained with different **test sizes (0.2, 0.3)** for comparison.  

---

### 📊 Evaluation Metrics  
- **Precision & Recall**  
- **F1-score**  
- **MCC (Matthew’s Correlation Coefficient)**  
- **Specificity & Sensitivity**  
- **False Positive & False Negative Rates**  

Results are visualized using **bar plots** for better comparison.  

---

### 📌 Results  
✅ The **CNN model** achieved the best accuracy of **93.94%** on the **80/20 split**.  

📊 **Accuracy Scores:**  
#### **70/30 Split:**  
- 🧠 **CNN:** 92.93%  
- 🔄 **LSTM:** 88.38%  
- 🔁 **GRU:** 90.40%  

#### **80/20 Split:**  
- 🧠 **CNN:** **93.94%** ✅ (Best)  
- 🔄 **LSTM:** 92.42%  
- 🔁 **GRU:** 90.91%  

Would you like me to draft a **full README.md** including installation steps, dataset details, and usage instructions? 🚀 

---

### 📝 To-Do List  
✅ Implement CNN, LSTM, and GRU  
✅ Compare models on different test sizes  
⬜ Hyperparameter tuning  
⬜ Add more datasets for generalization  

---

### 📜 License  
This project is **open-source** under the **MIT License**.  

---
