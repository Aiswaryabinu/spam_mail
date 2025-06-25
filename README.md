# Email Spam Classifier

A machine learning project to detect and filter spam emails using data-driven techniques.

## 🚀 Overview

**Email Spam Classifier** is an application that uses machine learning algorithms to classify emails as spam or not spam (ham). It leverages natural language processing (NLP) and popular machine learning libraries to build and evaluate a robust spam detection model.

## 🛠️ Features

- Preprocesses email text using NLP techniques
- Trains a classifier (e.g., Naive Bayes, SVM, or Logistic Regression)
- Evaluates model performance with metrics like accuracy, precision, and recall
- Predicts whether new emails are spam or not
- Easy-to-understand code and modular structure

## 📂 Project Structure

```
email_spam/
├── data/                # Sample datasets
├── notebooks/           # Jupyter notebooks for EDA and prototyping
├── src/                 # Source code (preprocessing, training, prediction)
├── requirements.txt     # Python dependencies
├── README.md            # Project documentation
└── ...                  # Other files (e.g., LICENSE, .gitignore)
```

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Aiswaryabinu/email_spam.git
   cd email_spam
   ```
2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## 🏃‍♂️ Usage

Run the main script to train and test the classifier:

```bash
python src/train_and_predict.py
```

Or explore the Jupyter notebooks in the `notebooks/` directory for step-by-step analysis and model building.

## 🧪 Example

```python
from src.predict import predict_email

email = "Congratulations! You've won a $1,000 gift card. Click here to claim now!"
print(predict_email(email))  # Output: 'spam'
```

## 🧰 Technologies Used

- Python 3.x
- scikit-learn
- pandas, numpy
- NLTK or spaCy (for NLP)
- Jupyter Notebook

## 📊 Dataset

Uses popular spam datasets like the [UCI SMS Spam Collection](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection) or [Enron Email Dataset](https://www.cs.cmu.edu/~enron/).

## 🤝 Contributing

Contributions are welcome! Please open issues or submit pull requests for improvements or bug fixes.

## 📬 Contact

Created by [Aiswaryabinu](https://github.com/Aiswaryabinu).  
Feel free to reach out via GitHub issues for questions or suggestions.

## 📄 License

This project is licensed under the MIT License.
