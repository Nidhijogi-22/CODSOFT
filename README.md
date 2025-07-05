Projects made for the CODSOFT internship tasks

**Task 1: 💳 Credit Card Fraud Detection**
A machine learning project that identifies fraudulent credit card transactions using Logistic Regression on a real-world imbalanced dataset.

📦 Dataset
Used a credit card fraud dataset (Kaggle), with anonymized features for thousands of transactions, including both fraudulent and legitimate cases.

🔧 Preprocessing
Checked and dropped missing/null values
Standardized features using StandardScaler
Ensured balanced processing of skewed target class
Visualized class imbalance using bar charts

🧠 Model
Used Logistic Regression to classify transactions as fraud or not. Trained on a train-test split with balanced class weights to address data imbalance.

📊 Evaluation
Accuracy score
Confusion matrix (with seaborn heatmap)
Visual insights into correct/incorrect classifications

🚀 Future Work
Deploy model with a real-time fraud detection dashboard

**Task 2: 📱 Spam SMS Detection**
A text classification project that detects spam messages using NLP techniques and the Naive Bayes algorithm.

📁 Dataset
Used the SMS Spam Collection Dataset from UCI/Kaggle — labeled SMS messages categorized as “spam” or “ham”.

🧹 Preprocessing
Converted all messages to lowercase
Tokenized and joined back the cleaned words
Vectorized text using TF-IDF (Term Frequency–Inverse Document Frequency)

🧠 Model
Used Multinomial Naive Bayes, ideal for text classification due to its efficiency and strong performance on bag-of-words features.

📊 Evaluation
Accuracy and confusion matrix
Classification report
Class distribution chart for spam vs ham

🚀 Future Enhancements
Integrate a simple web UI for live message classification

**Task 3: 📉 Customer Churn Prediction**
Predicts whether a telecom customer is likely to churn using machine learning on structured customer data.

📁 Dataset
Used a churn dataset containing customer service usage, account data, and churn labels (binary: Yes/No).

🔧 Preprocessing
Scaled numerical features with StandardScaler
Checked for class balance and cleaned any missing values

🧠 Model
Implemented Random Forest Classifier for its robustness and feature importance capabilities. Trained on a hold-out validation set split.

📊 Evaluation
Accuracy and confusion matrix
Classification report
Plots showing feature distributions and churn ratios

🚀 Future Plans
Tune hyperparameters with GridSearchCV
Build a churn prediction dashboard for business users
