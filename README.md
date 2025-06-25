# Capstone

Research Question:
How can a machine learning algorithm be effectively utilized to classify and filter spam emails from legitimate messages, and what features contribute most significantly to accurate classification?

The focus of the project will be on evaluating the model’s ability to correctly classify emails into “spam” or “not spam”. These results will be measured using the performance metrics previously mentioned.

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
The one I selected was Logistic Regression, but there are other ones that could probably be used such as Naive Bayes, Support Vector Machine (SVM), Random Forest / Decision Trees, Gradient Boosting.
Logistic Regression seems to handle sparse feature vectors efficiently, doesn’t require heavy resources or deep architectures for solid performance. It is fast to Train and Predict and it is lightweight and computationally efficient.


### 4. Model Evaluation: 
Assessing performance through Confusion Matrix, Precision, Recall, F1-Score, we can tell that the model is performing very well, with an overall accuracy of 97%, which means that 97% of emails were correctly classified as either class 0 or 1. Also, it performs equally well for both classes, which is especially important in spam detection, where false positives (good emails marked as spam) can be disruptive.
Nearly identical precision and recall demonstrates that there is no significant bias toward either class.


## Why this question is important

Having a working model that accurately classifies emails into spam and not spam is important for several reasons:

User Experience will be improved by reducing inbox clutter and helping the users focus on important and legitimate emails without distractions.
Enhanced security, since many spam emails contain phishing, links, malware or scams. By correctly identifying and blocking spam emails data breaches, identity theft and financial losses can be prevented.
It promotes business efficiency and boosts productivity when employees can waste less time sorting through spam.
