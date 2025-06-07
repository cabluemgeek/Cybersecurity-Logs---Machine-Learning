# ***Cybersecurity Log Analysis with Machine Learning*** 
This project leverages machine learning techniques to detect anomalies and potential threats in cybersecurity log data. It focuses on processing and modeling various types of log files (e.g., authentication, firewall, network traffic) to identify suspicious activities such as brute-force attacks, port scans, and unusual traffic patterns.
---

## ***📁 Project Structure:***   
📂 cybersecurity-log-ml  
├── 📂 data — Sample or real log files  
├── 📂 notebooks — Jupyter notebooks  
├── 📂 src — Source scripts  
│   ├── 📄 preprocessing.py  
│   ├── 📄 feature_engineering.py  
│   └── 📄 model.py  
├── 📂 outputs — Saved models and plots  
├── 📄 requirements.txt  
├── 📄 main.py  
└── 📄 README.md  

--- 
## 🚀 Features
- **Log Preprocessing**: timestamp parsing, IP cleanup, encoding
- **Feature Engineering**: login attempt patterns, IP frequencies, protocol types
- **Anomaly Detection**: Isolation Forest, One-Class SVM, Autoencoders
- **Supervised Classification**: RandomForest, LogisticRegression, XGBoost
- **Evaluation**: precision, recall, F1-score, confusion matrix
- **Visualization**: time-based attack tracking, heatmaps

---

## 📊 Sample Output

| Model            | Precision | Recall | F1-Score |
|------------------|-----------|--------|----------|
| Isolation Forest | 0.91      | 0.85   | 0.88     |
| Random Forest    | 0.95      | 0.94   | 0.94     |

---

## 📚 Datasets Used

- [UNSW-NB15](https://research.unsw.edu.au/projects/unsw-nb15-dataset)
- [CICIDS2017](https://www.unb.ca/cic/datasets/ids-2017.html)
- Custom `auth.log`, `firewall.log` samples

---

## ⚙️ Installation

```bash
# Clone the repo
git clone https://github.com/your-username/cybersecurity-log-ml.git
cd cybersecurity-log-ml

# Install Python dependencies
pip install -r requirements.txt
```
---


## ✍️ Author
**Kamelia Zenati**

Data Scientist & AI Engineer
