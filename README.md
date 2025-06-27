 Spam Classifier Project

A simple machine learning project that classifies SMS messages as **Spam** or **Ham (Not Spam)** using natural language processing and a Naive Bayes model.

---

## 🚀 What This Project Do

- Loads a dataset of SMS messages
- Cleans and preprocesses text using NLTK
- Converts text to numerical features (Bag-of-Words)
- Trains a Multinomial Naive Bayes classifier
- Evaluates accuracy and classification metrics

---

##  Dataset

-  [SMS Spam Collection Dataset](https://raw.githubusercontent.com/justmarkham/pycon-2016-tutorial/master/data/sms.tsv)
- Format: `.tsv` (Tab-Separated Values)
- 2 columns: `label` (spam or ham), `text` (SMS message)

---

##  How to Run

###  In Google Colab

1. Open the notebook: [`spam_classifier.ipynb`](./spam_classifier.ipynb)
2. Run all cells (Shift + Enter)

###  Locally (Optional)

1. Clone the repo:

```bash
git clone https://github.com/yourusername/SpamClassifier.git
cd SpamClassifier
Install required packages:

bash
Copy
Edit
pip install -r requirements.txt
Run the code (if converted to .py):

bash
Copy
Edit
python spam_classifier.py
 Requirements
Install the following Python libraries:

txt
Copy
Edit
pandas
scikit-learn
nltk
 Sample Output
text
Copy
Edit
Accuracy: 0.98

Classification Report:
              precision    recall  f1-score   support
         ham       0.99      0.99      0.99       965
        spam       0.95      0.94      0.94       150
 Project Structure
bash
Copy
Edit
 SpamClassifier/
├── spam_classifier.ipynb    # Main notebook (Colab)
├── requirements.txt         # Python dependencies
└── README.md                # Project overview and instructions


 Contact: abdurasulov0904@mail.ru
 Related Skills Demonstrated
Natural Language Processing (NLP)

Data Preprocessing

Feature Engineering

Supervised Machine Learning (Naive Bayes)

yaml
Copy
Edit

---

###  What to Do With It

1. Go to your GitHub repo
2. Click **"Add file" → "Create new file"**
3. Name it exactly:

README.md

yaml
Copy
Edit

4. Paste the content above
5. Click **"Commit changes"**
