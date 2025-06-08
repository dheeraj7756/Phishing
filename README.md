# Phishing URL Detection

A web application that detects phishing URLs using machine learning. The project leverages feature engineering and a trained model to classify URLs as safe or phishing.

---

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Directory Tree](#directory-tree)
- [Technologies Used](#technologies-used)
- [Usage](#usage)
- [Result](#result)
- [Conclusion](#conclusion)

---

## Introduction

Phishing is a major threat on the Internet, where attackers attempt to steal sensitive information by tricking users with fake websites. This project uses machine learning to identify phishing URLs based on their characteristics, helping users avoid malicious sites.

---

## Installation

1. **Clone the repository:**
   ```sh
   git clone <repository-url>
   cd Phishing-URL-Detection-master
   ```

2. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

3. **(Optional) Download Python 3.6.10:**  
   [Download Python](https://www.python.org/downloads/)

---

## Directory Tree

```
├── pickle/
│   └── model.pkl
├── static/
│   └── styles.css
├── templates/
│   └── index.html
├── Phishing URL Detection.ipynb
├── Procfile
├── README.md
├── app.py
├── feature.py
├── phishing.csv
├── requirements.txt
```

---

## Technologies Used

- [Python](https://www.python.org/)
- [NumPy](https://numpy.org/doc/)
- [Pandas](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.html)
- [Matplotlib](https://matplotlib.org/)
- [scikit-learn](https://scikit-learn.org/stable/)
- [Flask](https://flask.palletsprojects.com/en/2.0.x/)
- [CatBoost](https://catboost.ai/)

---

## Usage

1. **Start the Flask app:**
   ```sh
   python app.py
   ```

2. **Open your browser and go to:**  
   `http://localhost:5000`

3. **Enter a URL** to check if it is phishing or safe.

---

## Result

The model achieves high accuracy in classifying URLs. Features such as "HTTPS", "AnchorURL", and "WebsiteTraffic" are significant in determining if a URL is phishing.

---

## Conclusion

- Explores various machine learning models and feature engineering for phishing detection.
- Gradient Boosting Classifier achieves up to 97.4% accuracy.
- Helps reduce the risk of falling victim to phishing attacks.

---

©2025 Dheeraj