# ❤️ Heart Disease Prediction - Milestone 1

This project is part of my Machine Learning journey.  
In **Milestone 1**, the goal is to analyze the dataset, apply ML models, and evaluate performance for predicting **heart disease**

<img width="688" height="554" alt="image" src="https://github.com/user-attachments/assets/73b1173f-f349-4e65-a243-22b170297344" />


## 📊 Dataset

- **Source**: [UCI Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/heart+disease)  
- **Target Variable**: `target` (1 = Heart Disease, 0 = No Disease)  
- **Features** include:  
  - `age`: Age of the patient  
  - `sex`: 1 = male, 0 = female  
  - `cp`: Chest pain type (0-3)  
  - `chol`: Serum cholesterol (mg/dl)  
  - `thalach`: Maximum heart rate achieved  
  - `exang`: Exercise-induced angina (1 = yes, 0 = no)  
  - ...and more.
  - 

## 🚀 Steps Implemented in Milestone 1

### 1️⃣ Importing Libraries
- Loaded essential Python libraries like **pandas, numpy, matplotlib, seaborn, sklearn**.

### 2️⃣ Loading the Dataset
- Read the **heart.csv** dataset using `pandas.read_csv()`.

### 3️⃣ Data Exploration (EDA)
- Checked dataset shape, columns, datatypes.  
- Handled **missing values** and verified dataset balance.  
- Used `df.describe()` and visualizations (histograms, heatmaps, pairplots).  

### 4️⃣ Feature Engineering
- Scaled numerical values using `StandardScaler`.  
- Encoded categorical values if needed.  

### 5️⃣ Splitting Dataset
- Split dataset into **training (80%)** and **testing (20%)** using `train_test_split`.  

### 6️⃣ Model Training
- Implemented baseline model: **Logistic Regression**.  
- Also tested **Random Forest** and **KNN** classifiers.  

### 7️⃣ Hyperparameter Tuning
- Used three approaches for optimization:  
  - Manual tuning (trying different values manually).  
  - RandomizedSearchCV (random selection of hyperparameters).  
  - GridSearchCV (systematic selection from all combinations).  

### 8️⃣ Model Evaluation
- Evaluated performance using:  
  - Accuracy, Precision, Recall, F1-score.  
  - Confusion Matrix & Classification Report.  

### 9️⃣ Saving Results
- Saved trained models in **models/**.  
- Saved evaluation results and plots in **results/**.

## ⚙️ Installation & Usage

### 🔹 Install Dependencies
```bash
pip install -r requirements.txt
