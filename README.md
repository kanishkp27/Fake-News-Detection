# 📰 Fake News Detection using NLP and Logistic Regression

This project uses Natural Language Processing (NLP) techniques and a Logistic Regression model to classify news articles as **real** or **fake**, based on their author and title.

---

## 📚 Dataset

The dataset used is a CSV file named `train.csv`, which contains:

- `id`: Unique identifier for each article
- `title`: Title of the news article
- `author`: Author of the news article
- `text`: Full text (not used in this version)
- `label`: `0` for Fake News, `1` for Real News

---

## 🛠️ Technologies Used

- Python
- Numpy
- Pandas
- NLTK (for text preprocessing)
- Scikit-learn (for model building and evaluation)

---

## ⚙️ Installation

Clone the repository and install the required libraries:

```bash
git clone https://github.com/yourusername/fake-news-detector.git
cd fake-news-detector
pip install -r requirements.txt
