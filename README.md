# 🌸 Iris Flower Classification using Ensemble Learning

This repository focuses on building and evaluating a high-performance machine learning pipeline on the classic **Iris Dataset** using advanced **Ensemble Learning** methodologies. The goal is to optimize multi-class classification accuracy by combining multiple base estimators.

---

## 🛠️ Ensemble Techniques Implemented

To achieve robust predictive stability, the project utilizes the following ensemble architectures:

- **Max Voting / Hard & Soft Voting:** Aggregating predictions from diverse underlying algorithms (like Logistic Regression, SVM, and Decision Trees).
- **Bagging (Random Forest Classifier):** Training multiple decision tree estimators in parallel to reduce model variance.
- **Boosting (AdaBoost / Gradient Boosting):** Sequentially correcting errors from baseline estimators to reduce predictive bias.

---

## 📊 Dataset Structure

The system processes the standard Iris dataset containing 150 instances tracking four core physical features:

1. Sepal Length (cm)
2. Sepal Width (cm)
3. Petal Length (cm)
4. Petal Width (cm)

---

## 💻 Tech Stack & Dependencies

- **Python 3.x**
- **scikit-learn** (For dataset sourcing, model pipelines, and ensemble algorithms)
- **pandas & numpy** (For structured matrix processing)
- **matplotlib & seaborn** (For confusion matrix heatmap plots and classification boundaries)

---

## 🚀 How to Run Locally

Follow these quick implementation steps to clone, configure, and execute the ensemble model pipeline locally on your machine:

### 1. Clone and Enter the Repository

```bash
git clone [https://github.com/amirsohail100/my_first_ensemble-_learning_basics.git](https://github.com/amirsohail100/my_first_ensemble-_learning_basics.git)
cd my_first_ensemble-_learning_basics
```

An optimized machine learning pipeline implementing Ensemble Learning (Voting, Bagging, Boosting) on the classic Iris Dataset to achieve high-accuracy multi-class classification.
