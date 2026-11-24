Network Intrusion Detection System

Overview

A machine learning project that uses the CICIDS2017 dataset to detect and classify network traffic into benign and malicious categories.

The project applies a Random Forest Classifier to identify different types of network attacks based on network traffic features.

Technologies

- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn
- Jupyter Notebook

Model Performance

Metric| Score
Accuracy| 99.82%
Macro F1-score| 0.86

Key Features

- Network traffic data exploration and cleaning
- Multiclass intrusion classification
- Model evaluation
- Feature importance analysis
- Trained model saved for future use

Project Structure

Network-Intrusion-Detection-System/
├── data/
├── notebooks/
├── models/
│   ├── ids.pkl
│   └── label_encoder.pkl
├── requirements.txt
├── .gitignore
└── README.md

Getting Started

Clone the repository:

git clone https://github.com/clemsjr/Network-Intrusion-Detection-System.git

Install dependencies:

pip install -r requirements.txt

Open the notebook:

jupyter notebook

Limitations

The dataset is imbalanced, and the model performs less effectively on some attack categories with very few samples. Real-time deployment has not yet been implemented.

Author

Tondo Clement

Machine Learning Engineer | Data Analyst | Cybersecurity

"GitHub" (https://github.com/clemsjr)
