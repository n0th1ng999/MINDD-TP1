# 📞 Telemarketing Success Prediction (MINDD-TP1) 

## 🚀 Overview
This project applies **data mining + machine learning** to predict the success of telemarketing calls promoting long-term bank deposits.

💡 Why? To help banks reduce wasted calls and **focus on customers most likely to subscribe**.

Dataset 📊: Portuguese retail bank (2008–2013), including the turbulent 💥 global financial crisis. A realistic, high-variance environment for building predictive models.

---

## 🎯 Objectives (to refine as project develops)

* **Define success criteria** → Decide whether to optimize for recall (catch as many potential subscribers as possible) or precision (minimize wasted calls).
* **Explore customer & campaign patterns** → Identify key features (e.g., age, job, call duration) that drive deposit subscriptions.
* **Build predictive models** → Train and compare ML algorithms to predict likelihood of subscription.
* **Support marketing strategy** → Translate findings into **actionable recommendations** for campaign managers.

---

## 📂 Dataset

* **Source**: Portuguese retail bank (2008–2013)
* **Features**: demographics 👤, socio-economic factors 💼, campaign details 📞
* **Target Variable**: `y` → deposit subscription (yes/no)

---

## 🔄 Methodology: CRISP-DM

1. **Business + Data Understanding** 🔍

   * Frame the problem, set goals, and success criteria.
   * Explore dataset with descriptive stats + EDA visuals.

2. **Data Prep** 🧹

   * Handle missing values, outliers, encodings, and scaling.
   * Address class imbalance with resampling ⚖️.

3. **Modelling** 🤖

   * Test algorithms such as Logistic Regression, Decision Trees, Random Forests, Gradient Boosting 🌲⚡
   * Use hyperparameter tuning + cross-validation for optimization.

4. **Evaluation** 📊

   * Metrics: Accuracy ✅, Precision 🎯, Recall 🔁, F1-score ⚖️, ROC-AUC 📈
   * Perform error analysis + interpret feature importance.

---

## 📦 Deliverables

* 🐍 Python code for all CRISP-DM phases.
* 📑 Written report including:

  * Problem statement + success criteria
  * Exploratory data analysis (EDA) results
  * Data cleaning & preprocessing decisions
  * Modelling experiments + reasoning
  * Evaluation metrics + limitations
  * Conclusions & actionable recommendations

---

## ⚙️ Requirements

* Python 3.8+ 🐍
* Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `imbalanced-learn`

---

## 🏃 How to Run

1. Clone the repo ⬇️
2. Install dependencies → `pip install -r requirements.txt`
3. Run the Jupyter notebooks or scripts following the CRISP-DM workflow 🧩

---

## 💡 Conclusions (to be finalized after modelling)

* Predictive models can provide valuable **business insights**.
* Results will guide smarter marketing campaigns 📈.
* Future work could deploy the best model in a real-time decision support system ⚡.

---

## 📜 License

Academic use only ✍️🎓
