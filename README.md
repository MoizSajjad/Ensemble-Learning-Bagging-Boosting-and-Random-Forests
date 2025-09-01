# Bagging, Boosting & Random Forests

## Introduction  
This repository contains a Jupyter Notebook that demonstrates **ensemble learning techniques** for classification.  
The notebook compares a baseline Decision Tree with **Bagging, AdaBoost, and Random Forests**, showing how ensembles improve accuracy and robustness.  

---

## Methods Implemented  
- **Baseline Model**: Decision Tree classifier for reference performance.  
- **Bagging**: Bootstrap Aggregating with Decision Trees.  
- **AdaBoost**: Adaptive Boosting with shallow and deeper trees, analyzing effect of estimators and depth.  
- **Random Forest**: Ensemble of Decision Trees with feature randomness.  

---

## Results & Visualizations  
- Accuracy comparison across models.  
- Confusion matrices for classification performance.  
- Bar charts of test accuracies.  
- Effect of hyperparameters:  
  - Number of estimators (Bagging & AdaBoost).  
  - Tree depth in AdaBoost.  

---

## How to Run  

1. **Clone this repository**  
   ```bash
   git clone https://github.com/MoizSajjad/BaggingBoosting_RandomForest.git
   cd BaggingBoosting_RandomForest

2. Install dependencies
pip install -r requirements.txt

Repository Structure
BaggingBoosting_RandomForest/
│── BaggingBoosting_RandomForest.ipynb   # Main notebook
│── requirements.txt                     # Dependencies
└── README.md                 
