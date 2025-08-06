# 🧠 Mental Health Detector

A machine learning project to detect suicidal intent from text using logistic regression and natural language processing (NLP). Built as part of a summer internship course on **Machine Learning In-Depth (with Python)**.


## 🚀 Project Summary

This project uses:
- Text preprocessing
- TF-IDF vectorization
- Logistic Regression

...to classify whether a piece of text expresses suicidal thoughts or not.


## 📂 Folder Structure

mental-health-detector/
│
├── mental_health_detector.ipynb # Main notebook
├── Suicide_Detection.csv # Dataset used
├── requirements.txt # List of Python dependencies
├── model/
│ ├── model.pkl # Trained ML model
│ └── vectorizer.pkl # Trained TF-IDF vectorizer
└── README.md # Project info



## 🧪 Model Performance

- **Accuracy:** `93.37%`
- **Precision/Recall/F1:** ~0.93 for both classes (1 = suicidal, 0 = non-suicidal)


## 🔧 Requirements

See `requirements.txt` file or install directly:

```bash
pip install -r requirements.txt



##🛠️ Tech Stack

Python 3.10+

pandas

numpy

scikit-learn

matplotlib

seaborn

## 🚀 Project Contents

- `notebooks/suicide_detection.ipynb` – Full ML workflow
- `requirements.txt` – Library dependencies
- `data/Suicide_Detection.csv` – Raw input text data
- `README.md` – Project overview and results

---
## 🔍 Performance

**Accuracy:** 93.3%  
**Precision / Recall / F1-score:** ~0.93 for both classes  

The model shows balanced performance on both non‑suicidal (class 0) and suicidal (class 1) posts.


##📊 Sample Output

Accuracy: 0.9337

Classification Report:
               precision    recall  f1-score   support

           0       0.93      0.94      0.93     23287
           1       0.94      0.93      0.93     23128



🙋‍♂️ Author
Vedansh Saun
Summer Internship - Machine Learning In-Depth (Python)


