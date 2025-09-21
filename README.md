# 🧑‍💻 Adult Census Income Prediction
## This project is based on learning in OSTAD.com e-learning Data Science and Machine Learning Course ##
This project predicts whether a person earns **>50K** or **<=50K** annually using the **Adult Census Income dataset**.  
It demonstrates a full ML pipeline with preprocessing, visualization, multiple models, and hyperparameter tuning.

---

---

## 🚀 Workflow
1. **Preprocessing**
   - Handle missing values & duplicates
   - Encode categorical features
   - Scale numerical features  

2. **Visualization**
   - Class distribution
   - Correlation heatmap
   - Feature vs income analysis  

3. **Modeling**
   - Logistic Regression (~83% accuracy)  
   - Decision Tree (tuned, ~85%)  
   - Random Forest (~86%)  
   - XGBoost (tuned, ~88%)  

4. **Evaluation**
   - Accuracy  
   - Confusion Matrix  
   - Classification Report  

---

## 🎯 Results
- Logistic Regression → ~83%  
- Decision Tree (tuned) → ~85%  
- Random Forest → ~86%  
- XGBoost (best) → **~88%**

---

## 📜 Dataset
- [UCI Repository](https://archive.ics.uci.edu/ml/datasets/adult)  
- [Kaggle Version](https://www.kaggle.com/datasets/uciml/adult-census-income)

---

## 🔧 Setup
Clone the repo and install requirements:
```bash
git clone https://github.com/shaownXjony/adult-income-ml.git
cd adult-income-ml
pip install -r requirements.txt
