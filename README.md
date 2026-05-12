# Phishing URL Detection

## Overview
This project is a Machine Learning based web application that detects whether a URL is legitimate or phishing using an SVM model and URL feature extraction techniques.

---

## Features
- Detects phishing and legitimate URLs
- Machine Learning based prediction
- URL feature extraction
- Simple web interface using Flask
- Fast prediction system

---

## Tech Stack
- Python
- Flask
- HTML
- CSS
- Scikit-learn
- Joblib

---

## Machine Learning Model
- Support Vector Machine (SVM)

---

## Project Structure

```bash
phishing-url-detection/
│
├── dataset/
├── static/
├── templates/
├── model/
├── driver.py
├── extractor.py
├── svm.joblib
├── README.md
└── requirements.txt
```

---

## Installation

Run this command in CMD:

```bash
pip install urllib3 requests beautifulsoup4 flask pandas joblib
```

---

## Running the Project

Open command prompt in the project directory and run:

```bash
python driver.py
```

Open in browser:

```txt
http://127.0.0.1:5000/
```

---

## Future Improvements
- Browser extension integration
- Deep learning implementation
- Real-time URL scanning
- API deployment

---

## Author
Muskan Patni
