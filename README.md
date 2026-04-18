# 🧠 Handwritten Digit Recognition using KNN

This project implements the **K-Nearest Neighbors (KNN)** algorithm from scratch to classify handwritten digits using the MNIST dataset.

---

## 🚀 Features

* Implemented **KNN from scratch** using Python
* Used **MNIST dataset (CSV format)**
* Distance-based classification (Euclidean distance)
* Majority voting for prediction
* Basic performance optimization using subset sampling

---

## 📊 Dataset

* Dataset: MNIST (Handwritten digits 0–9)
* Each image is **28×28 pixels (784 features)**
* CSV format with:

  * `label` → actual digit
  * `pixel0` to `pixel783` → image data

---

## 🛠️ Tech Stack

* Python
* NumPy
* Pandas
* Matplotlib

---

## ⚙️ How it Works

1. Load dataset using Pandas
2. Split into training and testing sets
3. Compute Euclidean distance between test and training samples
4. Select **k nearest neighbors**
5. Use **majority voting** to predict label
6. download the dataset from https://github.com/phoebetronic/mnist
---

## 📈 Accuracy

* Evaluated on a subset of the dataset for faster computation
* Achieves good accuracy for handwritten digit classification

---

## ▶️ How to Run

```bash
pip install numpy pandas matplotlib
```

```bash
python your_file_name.py
```

---

## 📂 Project Structure

```
├── train.csv
├── knn_mnist.ipynb / .py
├── README.md
```

---

## 💡 Notes

* KNN is a **lazy learning algorithm**, so prediction can be slow on large datasets
* Subset of data is used to improve execution time

---

## 🔥 Future Improvements

* Optimize KNN using vectorization
* Use KD-Tree / Ball Tree for faster search
* Compare with other ML models

---

## 👨‍💻 Author

Aditya
