# Distributed SMOTE for Diabetes Prediction

This project investigates scalable handling of **class imbalance** in healthcare datasets using **Distributed SMOTE** and **Ensemble Methods** with **Apache Spark**.  
The CDC Diabetes dataset is used to demonstrate how oversampling techniques can improve fairness and predictive performance in medical AI systems.

---

## 📂 Repository Structure

```
.
├── Code.ipynb          # Jupyter Notebook with preprocessing, SMOTE, and model training
├── Diabetes_imb.csv    # Dataset (imbalanced diabetes health indicators)
├── Report.pdf          # Detailed project report and results
└── README.md
```

---

## 🚀 Features
- Implements **Distributed SMOTE** for balancing imbalanced datasets.
- Uses **Random Forest, Logistic Regression, and Gradient Boosted Trees** for classification.
- Evaluates models on **accuracy, F1-score, precision, recall**.
- Includes **fairness analysis** across demographic subgroups.
- Scalable design using **Apache Spark (PySpark)** for large datasets.

---

## 🔧 Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/Distributed-SMOTE-for-Diabetes.git
   cd Distributed-SMOTE-for-Diabetes
   ```

2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Code.ipynb
   ```

---

## ▶️ Usage
- Run all cells in **Code.ipynb** to preprocess the dataset, apply distributed SMOTE, and train models.
- Results include evaluation metrics, PCA plots, and fairness heatmaps.

---

## 📊 Dataset
- **Diabetes_imb.csv**: Derived from the CDC Diabetes dataset, with imbalanced target labels (`0` = non-diabetic, `1` = diabetic).
- Class distribution is skewed, motivating the need for oversampling.

---

## 📄 Report
For detailed methodology, experimental setup, and results, see **Report.pdf**.

---

## 📌 Notes
- Ensure **Apache Spark** is properly configured if running in distributed mode.
- The notebook can also run locally in a single-node setup for smaller datasets.

---

## 📜 License
This project is released under the MIT License.
