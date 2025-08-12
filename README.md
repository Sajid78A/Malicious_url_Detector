# 🚨 Malicious URL Detector  

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-Gradient%20Boosting-green)
![ML](https://img.shields.io/badge/Machine%20Learning-Multi--Class-orange)
![Contributions](https://img.shields.io/badge/Contributors-3-brightgreen)

> **A Machine Learning-powered Web Security Tool** for classifying URLs as **Safe, Phishing, Malware, Defacement, or Other**.  
> Built with **LightGBM** and **Python**, optimized for **speed, accuracy, and real-world deployment**.

---

## 📌 Overview  
Cybersecurity threats often start with malicious URLs — phishing scams, malware downloads, or defaced websites.  
The **Malicious URL Detector** helps security teams and individuals **automatically detect and classify URLs** into five categories:  

| Category       | Icon  | Description |
|---------------|-------|-------------|
| **Safe**       | ✅ | Legitimate and non-malicious URLs |
| **Phishing**   | ⚠️ | Attempts to steal sensitive information |
| **Malware**    | 🐛 | Hosts malicious software or exploits |
| **Defacement** | 🪪 | Websites that are vandalized or tampered |
| **Other**      | ❓ | Suspicious but uncategorized URLs |

---

## 🛠 Tech Stack  
- **Language:** Python 3.8+ 🐍  
- **ML Framework:** [LightGBM](https://lightgbm.readthedocs.io/)  
- **Data Processing:** Pandas, NumPy, Scikit-learn   
- **Environment:** Jupyter Notebook / Python Scripts  

---

##   📊 How It Works
Data Collection – A labeled dataset of URLs with associated categories.

Feature Engineering – Extract lexical, host-based, and content-based features from URLs.

Model Training – Use LightGBM for efficient gradient boosting classification.

Prediction – Classifies new URLs into one of the five categories.

Evaluation – Confusion matrix & classification report for performance insights.

---

## ⚡ Features  
✅ **High Accuracy & Speed** – Uses LightGBM for efficient gradient boosting.  
✅ **Multi-class Classification** – Detects multiple threat types.  
✅ **Customizable** – Easy to retrain with your own dataset.  
✅ **Scalable** – Suitable for batch processing or real-time monitoring.  

---

## 📂 Project Structure  
```plaintext
Malicious-URL-Detector/
│-- data/               # Dataset files
│-- src/                # Feature extraction & model training scripts
│-- notebooks/          # Jupyter notebooks for EDA & experimentation
│-- models/             # Trained ML models
│-- README.md           # Project documentation
│-- requirements.txt    # Dependencies
```

## 💻 Example Usage
```
Python
from malicious_url_detector import predict_url

url = "http://example-malware.com"
category = predict_url(url)
print(f"URL Category: {category}")
```
## Output:
```
yaml
URL Category: Malware 🐛
```

## 📈 Model Performance

| Metric    | Score |
| --------- | ----- |
| Accuracy  | 96%   |
| Precision | 95%   |
| Recall    | 94%   |
| F1-score  | 94%   |

(_Performance Varies depending on dataset_)

---

## 👨‍💻 Contributors
- Md Nousad

- Md Sajid Alam

- Amarjeet Kumar Singh











