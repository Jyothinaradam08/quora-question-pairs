# Quora Question Pairs – Duplicate Question Detection

A machine learning and NLP-based web application that determines whether two questions have the same meaning or are duplicate questions.

## 🚀 Live Demo

👉 **Streamlit App:** [Click here to try the application](https://quora-question-pairs-tjwoushtvmxvgh5q2qgbe4.streamlit.app/)

## 📌 Project Overview

Duplicate or semantically similar questions are common on platforms such as Quora. This project uses Natural Language Processing (NLP) and Machine Learning techniques to analyze two questions and predict whether they are duplicates.

The application provides an interactive Streamlit interface where users can enter two questions and receive a prediction.

## ✨ Features

* Compare two questions for semantic similarity
* Detect duplicate questions using Machine Learning
* NLP-based text preprocessing and feature engineering
* Interactive Streamlit web interface
* Real-time prediction
* Pre-trained Machine Learning model
* TF-IDF/Count Vectorizer-based text representation

## 🛠️ Technologies Used

* **Python**
* **Streamlit**
* **Scikit-learn**
* **NLP**
* **FuzzyWuzzy**
* **BeautifulSoup**
* **Distance**
* **Python-Levenshtein**

## 🧠 Machine Learning Approach

The application processes the two input questions and extracts textual similarity features.

The general workflow is:

```text
Two Input Questions
        ↓
Text Preprocessing
        ↓
Feature Extraction
        ↓
Similarity Feature Generation
        ↓
Trained ML Model
        ↓
Duplicate / Not Duplicate
```

## 📂 Project Structure

```text
quora-question-pairs/
│
├── app.py                 # Streamlit application
├── helper.py              # NLP preprocessing and feature extraction
├── cv.pkl                 # Saved vectorizer
├── model.pkl              # Trained machine learning model
├── requirements.txt       # Python dependencies
├── setup.sh               # Setup configuration
├── Procfile.txt           # Deployment configuration
└── .gitignore             # Git ignored files
```

## 💻 Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/Jyothinaradam08/quora-question-pairs.git
```

### 2. Navigate to the project

```bash
cd quora-question-pairs
```

### 3. Create a virtual environment

```bash
python -m venv .venv
```

### 4. Activate the virtual environment

**Windows:**

```bash
.venv\Scripts\activate
```

### 5. Install dependencies

```bash
pip install -r requirements.txt
```

### 6. Run the Streamlit application

```bash
streamlit run app.py
```

The application will open in your browser at:

```text
http://localhost:8501
```

## 🎯 Example

**Question 1:**

> What is the best way to learn Python?

**Question 2:**

> How can I learn Python effectively?

The application analyzes the two questions and predicts whether they are duplicates based on the learned similarity patterns.

## 📊 Model Files

The project uses pre-trained model files stored in the repository:

* `cv.pkl` – saved text vectorizer
* `model.pkl` – trained machine learning model

These files allow the application to perform predictions without retraining the model every time the application starts.

## 🌐 Deployment

The application is deployed using **Streamlit Community Cloud** and connected to the GitHub repository.

**Live Application:**
👉 [Open Quora Question Pairs App](https://quora-question-pairs-tjwoushtvmxvgh5q2qgbe4.streamlit.app/)

## 👨‍💻 Author

**Jyothinaradam08**

GitHub:
https://github.com/Jyothinaradam08

## 📄 License

This project is intended for educational and portfolio purposes.
