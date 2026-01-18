# Student Performance GradeClass Prediction 🎓📊

This project applies **Machine Learning** to analyze student performance data and predict the final **GradeClass** using academic and lifestyle features.

The dataset is taken from **Kaggle**: *Students Performance Dataset*.

---

## 📌 Project Goal
Build a classification model that predicts **GradeClass** based on features such as:
- Study time per week
- Absences
- Parental support
- Tutoring
- Extracurricular activities
- GPA
- and more

---

## 🧠 Machine Learning Model
- **Random Forest Classifier**
- **Stratified K-Fold Cross-Validation (5 folds)** to ensure balanced class distribution in each split

---

## ⚙️ Workflow
1. Load dataset from Kaggle  
2. Data exploration (EDA) and statistics  
3. Check class distribution (imbalance)  
4. Select important features  
5. Scale features using **MinMaxScaler**  
6. Train model using **Stratified K-Fold**  
7. Evaluate performance using:
   - Accuracy
   - Confusion Matrix
   - Precision / Recall / F1-score
8. Visualize results

---

## ✅ Evaluation Metrics
- **Accuracy**
- **Confusion Matrix**
- **Classification Report**
  - Precision
  - Recall
  - F1-score

---

## 📊 Visualizations
- Confusion Matrix Plot  
- Classification Report Heatmap (Precision / Recall / F1-score)

---

## 🛠️ Technologies Used
- Python
- pandas, numpy
- scikit-learn
- matplotlib

---

## 📁 Files
- `student_performance_ml.ipynb` → main notebook
- `README.md` → project documentation

---

## 🔗 Dataset Source
Kaggle Dataset: Students Performance Dataset

---

## 👤 Author
**Faris**
