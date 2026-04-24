
## MAGIC Telescope Data Analysis
---
## 📷 Sample Output

![Correlation Matrix](images/correlation_matrix.png)

## 📌 Project Overview
This project focuses on classifying gamma-ray (signal) and hadron (background) events detected by the MAGIC (Major Atmospheric Gamma-ray Imaging Cherenkov) telescope.

The goal is to develop a machine learning model capable of accurately distinguishing between these two event types, which is critical in astrophysics for identifying sources of high-energy gamma radiation.

---
## 📂 Data

The dataset used in this project is included in the `data/` folder.

Source: MAGIC Gamma Telescope Dataset

---

## 📊 Dataset
- Source: MAGIC Gamma Telescope dataset  
- Observations: Event-based telescope readings  
- Features: 10 numerical variables  
- Target Variable:
  - `g` → Gamma (signal)
  - `h` → Hadron (background)

---

## 🔍 Exploratory Data Analysis (EDA)
Key analyses performed:
- Distribution plots of features  
- Class balance visualization  
- Feature relationship analysis (scatter plots)  
- Correlation matrix heatmap

---
## 📊 Correlation Matrix Heatmap

![Correlation Matrix Heatmap](images/correlation_matrix.png)

### Insights:
- Features exhibit varying distributions requiring scaling  
- Some degree of correlation exists between variables  
- Class distribution is reasonably balanced  

---

## ⚙️ Data Preprocessing
- Data loaded using **Pandas**
- No missing values detected  
- Feature scaling applied using **StandardScaler**
  - Mean = 0  
  - Variance = 1  

---

## 🤖 Model Development
- Model Used: **Logistic Regression**
- Reason:
  - Simple and interpretable baseline model  
  - Effective for binary classification  

### Train-Test Split:
- Training Set: 80%  
- Testing Set: 20%  

---

## 📈 Model Performance
- Accuracy: **79.31%**

### Evaluation Metrics:
- Precision  
- Recall  
- F1-score  
- Confusion Matrix  

The model demonstrates a solid ability to distinguish between gamma-ray and hadron events.

---

## 📊 Visualizations
The following visualizations were generated:
- Feature distribution plots  
- Correlation matrix heatmap  

(See `/images` folder)

---

## 🛠️ Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 🚀 Future Improvements
- Try advanced models:
  - Random Forest  
  - Support Vector Machines (SVM)  
  - Neural Networks  
- Hyperparameter tuning  
- Feature selection techniques  
- Model comparison and ensemble methods  

---

## 📌 Key Skills Demonstrated
- Data preprocessing and cleaning  
- Exploratory Data Analysis (EDA)  
- Data visualization  
- Feature scaling  
- Machine learning modeling  
- Model evaluation  
- Statistical thinking  

---

## 👤 Author
**Reagan Omondi**  
Data Analyst | Statistician | Machine Learning Enthusiast
