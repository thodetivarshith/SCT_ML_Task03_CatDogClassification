# 🐱🐶 Cat vs Dog Image Classification using SVM

## 📌 Overview

This project implements a **Support Vector Machine (SVM)** to classify images of cats and dogs using the Kaggle Dogs vs. Cats dataset.

## 📂 Dataset

- Source: Kaggle Dogs vs. Cats Dataset
- Images are resized to **64 × 64**
- Converted to grayscale
- Flattened into feature vectors

## 🛠 Technologies Used

- Python
- NumPy
- OpenCV
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## 📁 Project Structure

```
SCT_ML_Task03_CatDogClassification/
│
├── data/
│   ├── train/
│   └── test1/
│
├── notebook/
│   └── Task03_CatDog_SVM.ipynb
│
├── models/
│   └── svm_cat_dog.pkl
│
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

## 🚀 Installation

```bash
git clone <repository-url>

cd SCT_ML_Task03_CatDogClassification

pip install -r requirements.txt
```

## ▶️ Run

Open the notebook:

```
Task03_CatDog_SVM.ipynb
```

Run all cells.

## 📊 Model

- Algorithm: Support Vector Machine (SVM)
- Kernel: Linear
- Image Size: 64 × 64

## 👨‍💻 Author

**Varshith**

Machine Learning Intern — SkillCraft Technology

---


## Results

- Model: Support Vector Machine (Linear Kernel)
- Image Size: 64 × 64
- Color Mode: Grayscale
- Accuracy: 35% (trained on a 100-image sample)

## Future Improvements

- Train on a larger dataset
- Use color images instead of grayscale
- Apply feature extraction (e.g., HOG)
- Compare different SVM kernels
- Build a CNN for higher accuracy
- 
⭐ If you found this project useful, please give it a star.
