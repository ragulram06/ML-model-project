# 📬 SMS Spam Detection

[![Python](https://img.shields.io/badge/python-3.11-blue?logo=python\&logoColor=white)](https://www.python.org/)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

A simple **SMS spam detection** project using **Naive Bayes** and **TF-IDF** features in Python. Classifies messages as `spam` or `ham` with visualization of results.

---

## 🔹 Features

* Detect spam messages in real-time
* Visualizations for:

  * Class distribution
  * Confusion matrix
  * ROC curve
* Easy to extend with other classifiers or datasets

---

## 📊 Screenshots

**Class Distribution**
![Class Distribution](screenshots/class_distribution.png)

**Confusion Matrix**
![Confusion Matrix](screenshots/confusion_matrix.png)

**ROC Curve**
![ROC Curve](screenshots/roc_curve.png)

> Replace `screenshots/...` with actual images from your notebook.

---

## ⚙️ Installation

1. Clone the repository:

```bash
git clone <your-repo-url>
cd <repo-folder>
```

2. Install dependencies:

```bash
pip install pandas scikit-learn matplotlib numpy
```

3. Run the notebook or Python script.

---

## 🛠 Usage

```python
from your_script import check_spam

msg = "http://free-gift-online-login-security.com"
print(check_spam(msg))  # Output: 'spam' or 'ham'
```

---

## 🧠 How It Works

1. **Load dataset** of labeled SMS messages (`spam` or `ham`).
2. **Preprocess text** using TF-IDF vectorization.
3. **Train a Multinomial Naive Bayes classifier**.
4. **Evaluate performance** using:

   * Accuracy
   * Confusion matrix
   * ROC curve and AUC

---

## 📈 Results

* High accuracy on test data
* Effective spam detection for short messages
* Visualizations help interpret performance

---

## ⚠️ Notes

* The dataset is slightly imbalanced, so metrics like **precision, recall, and F1-score** are recommended.
* Stop words are removed to improve TF-IDF features.

---

## 📂 Folder Structure

```
├── notebook.ipynb
├── README.md
├── requirements.txt
├── screenshots/
│   ├── class_distribution.png
│   ├── confusion_matrix.png
│   └── roc_curve.png
```

---

