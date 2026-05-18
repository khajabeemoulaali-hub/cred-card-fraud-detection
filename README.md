# Credit Card Fraud Detection Engine 🛡️

An end-to-end Machine Learning system deployed in Python to identify fraudulent credit card transactions while managing the heavy class imbalance typical of financial data.

## 📊 Key Highlights & Metrics
* **The Imbalance Challenge:** Handled a dataset where fraud accounted for less than **0.17%** of total transactions (284,315 legitimate vs 492 fraud cases).
* **Baseline Performance:** Initial Random Forest Classifier achieved a baseline fraud recall of **80.61%**.
* **Advanced Balancing (SMOTE):** Deployed Synthetic Minority Over-sampling Technique to artificially balance the classes 50/50, shooting the model's catch rate up to **86.73%**.
* **Threshold Optimization:** Implemented a custom probability trigger matrix (lowering the decision cutoff to 20%), maximizing true fraud capture up to **90.82%**.

## 🛠️ Tech Stack Used
* **Platform:** Google Colab
* **Libraries:** Pandas, NumPy, Scikit-Learn, Imbalanced-Learn (SMOTE), Matplotlib
*
