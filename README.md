# Capstone

Research Question:
How can a machine learning algorithm be effectively utilized to classify and filter spam emails from legitimate messages, and what features contribute most significantly to accurate classification?

Data Source:
https://www.kaggle.com/datasets/purusinghvi/email-spam-classification-dataset

# Techniques to be used:
### 1. Data Preprocessing: 
Preparation of the raw text for modeling:
 - Lowercasing
 - Removing punctuation and numbers
 - Removing stopwords 
 - Stemming 
 - Tokenization
 - HTML tag removal 
 - Links removal

### 2. Feature Engineering: 
Transforms text into numeric features.
 - Bag of Words (BoW): Count of each word in the email
 - TF-IDF (Term Frequency-Inverse Document Frequency): Highlights important words
 - Length of email
 - Whether certain keywords exist (e.g.“free”, “win”, "prize")

### 3. Model Selection: 
The one I selected was Logistic Regression, but there are other ones that will probably be used such as Naive Bayes, Support Vector Machine (SVM), Random Forest / Decision Trees, Gradient Boosting.

### 4. Model Evaluation: 
Assessing performance through Confusion Matrix, Precision, Recall, F1-Score

The focus of the project will be on evaluating the model’s ability to correctly classify emails into “spam” or “not spam”. These results will be measured using the performance metrics previously mentioned.


## Why this question is important

Having a working model that accurately classifies emails into spam and not spam is important for several reasons:

User Experience will be improved by reducing inbox clutter and helping the users focus on important and legitimate emails without distractions.
Enhanced security, since many spam emails contain phishing, links, malware or scams. By correctly identifying and blocking spam emails data breaches, identity theft and financial losses can be prevented.
It promotes business efficiency and boosts productivity when employees can waste less time sorting through spam.
