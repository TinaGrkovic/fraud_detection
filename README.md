# 🏦 Fraud Detection Project

## **Project Overview**
This project focuses on developing a machine learning model to detect fraudulent bank account activities. The primary goal was to maximize recall while balancing precision and F1 score. In the later stages, the focus shifted to maximizing profit, considering the real-world costs and benefits of detecting fraud.

The final model achieved an expected profit of $14.5 billion, optimized through Bayesian Hyperparameter Tuning and Threshold Optimization.

---

## ⚡ **Key Features**
- ✅ **Class Imbalance Handling:** Used SMOTE to balance a 99%/1% imbalanced dataset.
- ✅ **Multiple Optimization Techniques:** 
  - **Grid Search**
  - **Randomized Search**
  - **Bayesian Optimization** (*final model*)
- ✅ **Profit-Driven Threshold Selection:** Selected threshold based on maximizing financial outcomes, not just F1 score.
- ✅ **Explainable AI:** Identified top features influencing fraud detection.
- ✅ **Performance Tracking:** Maintained a comprehensive Model Comparison Excel file to track all iterations.

---

## 📊 **Final Results**
| **Metric**        | **Value**    |
|-------------------|--------------|
| F1 Score (Test)    | 0.94         |
| Recall (Test)      | 0.99         |
| Precision (Test)   | 0.89         |
| ROC AUC (Test)     | 0.9988       |
| **Expected Profit**| **$14.5B**   |

- **Optimal Threshold:** 0.0071
- **Final Model:** Gradient Boosting with Bayesian Optimization

---

## 📁 Data Access
The dataset (`BAN6025Project2Data.csv`) is hosted on Google Drive due to size limitations.

🔗 [Download the dataset here](https://drive.google.com/file/d/1955_-DMsVYlVefJUPvomWO1uzl7EqLdo/view?usp=drive_link)

**Instructions:**
1. Download the CSV from the link above.
2. Place it in the project directory before running the notebooks.

---

## **Getting Started**
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/fraud_detection.git
   cd fraud_detection
2. **Run the final notebook:**
   ```bash
   jupyter notebook notebooks/fraud_detection_final_model.ipynb

### **Repository Structure**
  ```bash
  fraud_detection/
  ├── Additional_Materials/
  │   ├── Bayesion Optimization.ipynb          # Bayesian optimization process
  │   ├── Model Comparison.xlsx                # Model tracking & performance metrics
  │   └── Postmortem.docx                      # Further analysis & final thoughts
  ├── final_model.ipynb                        # Final model notebook
  ├── Iterative Modeling Process.docx          # report documenting modeling process
  └── README.md                         


