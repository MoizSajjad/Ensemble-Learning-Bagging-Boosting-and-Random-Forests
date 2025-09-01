BaggingBoosting_RandomForest
📌 Introduction

This repository contains a Jupyter Notebook that demonstrates the use of ensemble learning techniques to improve classification performance compared to a baseline Decision Tree. The notebook explores Bagging, AdaBoost, and Random Forests, analyzing how these methods affect accuracy and robustness.

⚡ Methods Implemented

Baseline Model

Decision Tree classifier for reference performance.

Bagging

Ensemble of Decision Trees using Bagging (Bootstrap Aggregating).

AdaBoost

Adaptive Boosting with shallow trees (stumps) and deeper trees.

Effect of number of estimators and tree depth on accuracy.

Random Forest

Ensemble of Decision Trees with feature randomness.

📊 Results & Visualizations

Accuracy Comparison (Decision Tree, Bagging, AdaBoost, Random Forest).

Confusion Matrices for performance evaluation.

Bar Charts comparing test accuracies across models.

Effect of Hyperparameters:

Number of estimators vs. accuracy (Bagging & AdaBoost).

Tree depth effect on AdaBoost performance.

🚀 How to Run

Clone this repository:

git clone https://github.com/MoizSajjad/BaggingBoosting_RandomForest.git
cd BaggingBoosting_RandomForest


Install required dependencies:

pip install -r requirements.txt


Open the Jupyter Notebook:

jupyter notebook BaggingBoosting_RandomForest.ipynb

📂 Repository Structure
├── BaggingBoosting_RandomForest.ipynb   # Main notebook
├── requirements.txt                     # Dependencies (numpy, pandas, matplotlib, sklearn)
└── README.md                            # Project documentation

🎯 Learning Outcomes

Understand the working of Bagging, Boosting, and Random Forests.

Visualize performance improvements over a single Decision Tree.

Explore how hyperparameters (estimators, depth) impact accuracy.
