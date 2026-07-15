# 📰 Fake News Detection using Machine Learning

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![License](https://img.shields.io/badge/License-MIT-green)

## 📌 Project Overview

Fake News Detection is a Natural Language Processing (NLP) project that classifies news articles as **Fake** or **Real** using Machine Learning algorithms.

The project performs text preprocessing, converts news articles into numerical vectors using **TF-IDF Vectorization**, trains multiple classification models, and predicts whether an input news article is genuine or fake.

---

## 🚀 Features

- News text preprocessing
- Data cleaning and normalization
- TF-IDF Vectorization
- Multiple Machine Learning models
- Manual news prediction
- Performance evaluation using Classification Report
- High accuracy on test data

---

## 📂 Dataset

This project uses two datasets:

- **Fake.csv**
- **True.csv**

Both datasets contain:

- Title
- Text
- Subject
- Date

After preprocessing, only the **text** column is used for training.

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Regular Expressions (re)

---

## 📊 Machine Learning Models

The following algorithms were implemented:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

---

## ⚙ Workflow

1. Import Libraries
2. Load Fake and Real News datasets
3. Assign labels
4. Merge datasets
5. Shuffle data
6. Clean text using preprocessing
7. Split dataset into Training and Testing sets
8. Convert text using TF-IDF
9. Train Machine Learning models
10. Evaluate performance
11. Predict custom news articles

---

## 📈 Model Performance

| Model | Accuracy |
|--------|-----------|
| Logistic Regression | **98.65%** |
| Decision Tree | **99.58%** |
| Random Forest | **99.01%** |

---

## 📁 Project Structure

```
Fake-News-Detection/
│
├── Fake.csv
├── True.csv
├── manual_testing.csv
├── Fake_News_Detection.ipynb
├── README.md
└── requirements.txt
```

---

## ▶ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Fake-News-Detection.git
```

Move into the project folder

```bash
cd Fake-News-Detection
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the notebook

```bash
jupyter notebook
```

---

## 📦 Required Libraries

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
```

Install using

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## 🧪 Example Prediction

Input:

```
Donald Trump just couldn’t wish all Americans a Happy New Year...
```

Prediction:

```
Fake News
```

Input:

```
WASHINGTON (Reuters) - The head of a conservative Republican faction...
```

Prediction:

```
Not A Fake News
```

---

## 📊 Future Improvements

- Deep Learning (LSTM/Bi-LSTM)
- BERT-based News Classification
- Web Application using Flask or Streamlit
- Live News API Integration
- Model Deployment on Cloud

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Push the branch
5. Open a Pull Request

---

## 📄 License

This project is licensed under the GNU General Public License v3.0.

---

## 👨‍💻 Author

**Vansh Srivastava**

B.Tech CSE (Data Science)

GitHub: https://github.com/Vansh-Srivastava

LinkedIn: https://www.linkedin.com/in/vansh-sri
