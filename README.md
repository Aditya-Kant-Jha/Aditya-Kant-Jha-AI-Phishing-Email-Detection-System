# Aditya-Kant-Jha-AI-Phishing-Email-Detection-System
<div align="center">

# 🛡️ AI-Based Phishing Email Detection System

### Detect Phishing Emails Using Machine Learning & Natural Language Processing (NLP)

<p align="center">

<img src="https://img.shields.io/badge/Python-3.11+-3776AB?style=for-the-badge&logo=python&logoColor=white"/>

<img src="https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white"/>

<img src="https://img.shields.io/badge/NLP-TF--IDF-6A1B9A?style=for-the-badge"/>

<img src="https://img.shields.io/badge/Model-Random%20Forest-2E7D32?style=for-the-badge"/>

</p>

<p align="center">

<img src="https://img.shields.io/badge/Accuracy-98.43%25-success?style=flat-square"/>

<img src="https://img.shields.io/badge/Precision-98.57%25-blue?style=flat-square"/>

<img src="https://img.shields.io/badge/Recall-98.41%25-orange?style=flat-square"/>

<img src="https://img.shields.io/badge/F1--Score-98.49%25-red?style=flat-square"/>

<img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>

</p>

---

### 🔒 Intelligent Email Security Through Artificial Intelligence

*A Machine Learning-powered phishing email detection system that automatically classifies emails as **Phishing** or **Legitimate** using Natural Language Processing (NLP) and multiple supervised learning algorithms.*

---

</div>

## 📌 Project Overview

Phishing attacks are one of the most common cyber threats used to steal sensitive information such as usernames, passwords, banking credentials, and personal data. Traditional rule-based email filters often struggle to detect newly crafted phishing emails.

This project presents an **AI-Based Phishing Email Detection System** that leverages **Natural Language Processing (NLP)** and **Machine Learning** to analyze email content and classify emails as either **Phishing** or **Legitimate**.

The project compares four different machine learning algorithms:

- Logistic Regression
- Naive Bayes
- Random Forest
- Neural Network (MLP Classifier)

After evaluating all models using **Accuracy, Precision, Recall, F1-Score, and Confusion Matrix**, the **Random Forest** model achieved the highest performance with an overall accuracy of **98.43%**, making it the final model for deployment.

---

<p align="center">

<img src="https://img.shields.io/badge/Python-3.11+-3776AB?style=for-the-badge&logo=python&logoColor=white"/>

<img src="https://img.shields.io/badge/Streamlit-Web_App-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white"/>

<img src="https://img.shields.io/badge/Scikit--Learn-Machine_Learning-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white"/>

<img src="https://img.shields.io/badge/NLP-TF--IDF-6A1B9A?style=for-the-badge"/>

<img src="https://img.shields.io/badge/Model-Random_Forest-2E7D32?style=for-the-badge"/>

</p>

<p align="center">

<img src="https://img.shields.io/badge/Accuracy-98.43%25-success?style=flat-square"/>

<img src="https://img.shields.io/badge/Precision-98.57%25-blue?style=flat-square"/>

<img src="https://img.shields.io/badge/Recall-98.41%25-orange?style=flat-square"/>

<img src="https://img.shields.io/badge/F1--Score-98.49%25-red?style=flat-square"/>

<img src="https://img.shields.io/badge/Dataset-82,078_Emails-informational?style=flat-square"/>

<img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>

</p>

<p align="center">

<img src="https://img.shields.io/badge/Cybersecurity-Phishing_Detection-darkred?style=flat-square"/>

<img src="https://img.shields.io/badge/Classification-Binary-success?style=flat-square"/>

<img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=flat-square"/>

<img src="https://img.shields.io/badge/Open--Source-Yes-blueviolet?style=flat-square"/>

<img src="https://img.shields.io/badge/Made%20with-Python%20%26%20Machine%20Learning-yellow?style=flat-square"/>

</p>
# 📖 Project Overview

Phishing emails remain one of the most common and dangerous cyber threats faced by individuals, businesses, and organizations worldwide. These fraudulent emails are carefully designed to imitate legitimate communications and trick users into revealing sensitive information such as usernames, passwords, banking credentials, credit card details, or other confidential data. As phishing attacks continue to become more sophisticated, traditional rule-based email filters often struggle to detect newly crafted or previously unseen phishing attempts.

This project presents an **AI-Based Phishing Email Detection System** that leverages **Machine Learning** and **Natural Language Processing (NLP)** to automatically identify whether an email is **Phishing** or **Legitimate**. Instead of relying on manually created rules, the system learns from previously labeled email data, enabling it to recognize hidden linguistic patterns and characteristics commonly found in phishing emails.

The complete machine learning pipeline begins with **data preprocessing**, where the raw email text is cleaned by converting it to lowercase, removing punctuation, special characters, numbers, URLs, extra spaces, and common stopwords. Lemmatization is then applied to transform words into their base forms, improving the overall quality of the textual data.

After preprocessing, the cleaned email content is transformed into numerical representations using the **TF-IDF (Term Frequency–Inverse Document Frequency)** feature extraction technique. This approach assigns greater importance to meaningful words while reducing the influence of frequently occurring but less informative words, allowing machine learning models to better understand the textual content.

To determine the most effective classification model, four supervised machine learning algorithms were implemented, trained, and evaluated:

- Logistic Regression
- Naive Bayes
- Random Forest
- Neural Network (MLP Classifier)

Each model was evaluated using standard performance metrics including **Accuracy, Precision, Recall, F1-Score, and Confusion Matrix**. After extensive comparison, the **Random Forest** classifier achieved the best overall performance with an **accuracy of 98.43%**, demonstrating excellent predictive capability and the lowest number of classification errors among all the implemented models.

The trained model was then integrated into an interactive **Streamlit web application**, allowing users to paste any email content and instantly receive a prediction indicating whether the email is **Phishing** or **Legitimate**, along with the confidence score and prediction probability.

This project demonstrates the practical application of Artificial Intelligence in cybersecurity by providing an intelligent, reliable, and scalable solution for phishing email detection. It also highlights the importance of combining NLP techniques with machine learning algorithms to enhance email security and reduce the risk of phishing attacks in real-world environments.
# ✨ Features

This project provides an intelligent and efficient solution for detecting phishing emails using **Machine Learning** and **Natural Language Processing (NLP)**. The system is designed to accurately classify emails as **Phishing** or **Legitimate** while providing fast predictions through an interactive web application.

---

## 🛡️ AI-Powered Email Classification

- Automatically classifies emails as **Phishing** or **Legitimate**
- Uses supervised Machine Learning for accurate predictions
- Learns hidden phishing patterns from historical email data
- Eliminates the need for manually written detection rules

---

## 📝 Advanced Text Preprocessing

The email content is cleaned before model training using multiple NLP techniques.

✔ Convert text to lowercase

✔ Remove punctuation and special characters

✔ Remove numbers

✔ Remove URLs

✔ Remove extra white spaces

✔ Remove English stopwords

✔ Lemmatization for better word normalization

---

## 🧠 Natural Language Processing (NLP)

The project uses NLP techniques to transform raw email text into meaningful information that machine learning models can understand.

- Text Cleaning
- Tokenization
- Stopword Removal
- Lemmatization
- TF-IDF Feature Extraction

---

## 📊 TF-IDF Feature Engineering

- Converts textual emails into numerical feature vectors
- Captures the importance of meaningful words
- Reduces the influence of commonly occurring words
- Improves machine learning performance

---

## 🤖 Multiple Machine Learning Models

Four different machine learning algorithms were implemented and compared.

- Logistic Regression
- Naive Bayes
- Random Forest
- Neural Network (MLP Classifier)

The best-performing model was selected based on evaluation metrics.

---

## 🏆 High Prediction Accuracy

| Model | Accuracy |
|--------|----------|
| Logistic Regression | **97.99%** |
| Naive Bayes | **96.04%** |
| Random Forest | **98.43%** ⭐ |
| Neural Network (MLP) | **97.70%** |

Random Forest achieved the highest accuracy and was selected as the final deployment model.

---

## 📈 Comprehensive Model Evaluation

Each model was evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

This enables a fair comparison between all implemented algorithms.

---

## 📧 Real-Time Email Prediction

The deployed application allows users to:

- Paste any email content
- Analyze it instantly
- View the prediction result
- Display prediction confidence
- Identify whether the email is phishing or legitimate

---

## 🌐 Interactive Streamlit Web Application

The project includes a user-friendly Streamlit interface featuring:

- Clean and responsive UI
- Large email input area
- One-click prediction
- Instant classification result
- Confidence score
- Easy-to-understand output

---

## 💾 Model Persistence

The trained machine learning model and TF-IDF vectorizer are saved using Pickle, allowing predictions without retraining the model every time.

---

## 📂 Modular Project Structure

The repository is organized into separate folders for:

- Dataset
- Jupyter Notebook
- Trained Models
- Streamlit Application
- Project Report
- Screenshots
- Documentation

This makes the project easy to understand and maintain.

---

## 🚀 Deployment Ready

The project is fully prepared for deployment using:

- Streamlit Community Cloud
- Local Machine
- GitHub Repository

---

## 🔐 Cybersecurity Application

This project demonstrates a practical use case of Artificial Intelligence in cybersecurity by helping users detect phishing emails and reduce the risk of:

- Credential Theft
- Identity Theft
- Financial Fraud
- Malicious Email Attacks
- Social Engineering Attacks

---
# 📊 Dataset Details

The performance of any machine learning model depends heavily on the quality of the dataset used for training. For this project, a phishing email dataset containing both **phishing** and **legitimate** emails was used to train and evaluate the machine learning models.

The dataset was carefully preprocessed to remove unnecessary information and prepare the email text for Natural Language Processing (NLP). After preprocessing, the cleaned email content was transformed into numerical features using the **TF-IDF (Term Frequency–Inverse Document Frequency)** technique.

---

## 📌 Dataset Information

| Attribute | Details |
|------------|---------|
| **Dataset Name** | Phishing Email Dataset |
| **File Format** | CSV |
| **Filename** | `phishing_email.csv` |
| **Total Samples** | **82,078 Emails** |
| **Problem Type** | Binary Classification |
| **Language** | English |
| **Feature Used** | Email Text (`text_combined`) |
| **Target Variable** | `label` |

---

## 🏷️ Class Labels

The dataset contains two categories of emails.

| Label | Email Type |
|--------|------------|
| **0** | Legitimate Email |
| **1** | Phishing Email |

The objective of the model is to correctly classify an unseen email into one of these two categories.

---

## 📄 Dataset Features

The dataset contains two primary columns that are used throughout the project.

| Feature | Description |
|----------|-------------|
| **text_combined** | Complete email content used for training and prediction. |
| **label** | Target column indicating whether an email is Legitimate (0) or Phishing (1). |

---

## 🧹 Data Preprocessing

Before training the machine learning models, several preprocessing steps were applied to improve the quality of the dataset.

- Converted all text to lowercase
- Removed punctuation marks
- Removed special characters
- Removed numbers
- Removed URLs
- Removed extra white spaces
- Removed English stopwords
- Applied lemmatization
- Generated cleaned email text for model training

These preprocessing techniques reduce noise in the dataset and help the models focus on meaningful words.

---

## 📈 Feature Engineering

After preprocessing, the cleaned email text was converted into numerical vectors using the **TF-IDF (Term Frequency–Inverse Document Frequency)** technique.

### Why TF-IDF?

- Converts textual emails into machine-readable numerical features
- Gives higher importance to meaningful words
- Reduces the influence of frequently occurring words
- Improves the performance of machine learning algorithms

The top **5,000 TF-IDF features** were selected for training the models.

---

## 🎯 Train-Test Split

The dataset was divided into two parts before model training.

| Dataset | Percentage |
|----------|-----------:|
| **Training Set** | **80%** |
| **Testing Set** | **20%** |

The training data was used to train the machine learning models, while the testing data was used to evaluate their performance on unseen emails.

---

## 📊 Dataset Workflow

```text
Raw Email Dataset
        │
        ▼
Load CSV File
        │
        ▼
Data Cleaning
        │
        ▼
Text Preprocessing
        │
        ▼
Stopword Removal
        │
        ▼
Lemmatization
        │
        ▼
TF-IDF Feature Extraction
        │
        ▼
Train-Test Split
        │
        ▼
Machine Learning Models
        │
        ▼
Phishing Email Prediction
```

---

## 📌 Purpose of the Dataset

The primary objective of this dataset is to train machine learning models capable of automatically detecting phishing emails based on their textual content. It enables the system to learn common linguistic patterns, suspicious phrases, and writing styles typically found in phishing attacks while distinguishing them from legitimate emails.

This dataset forms the foundation of the AI-Based Phishing Email Detection System and plays a crucial role in achieving reliable and accurate email classification.

---
# ⚙️ Methodology

The development of the **AI-Based Phishing Email Detection System** follows a structured Machine Learning pipeline that transforms raw email text into meaningful numerical features and trains multiple classification models to accurately detect phishing emails.

The workflow consists of six major stages, starting from data collection and ending with real-time email prediction through a Streamlit web application.

---

## 🔄 Project Workflow

```text
                📧 Raw Email Dataset
                        │
                        ▼
                📂 Data Collection
                        │
                        ▼
              🧹 Data Preprocessing
                        │
                        ▼
        📝 Natural Language Processing
                        │
                        ▼
         🔢 TF-IDF Feature Extraction
                        │
                        ▼
           ✂️ Train-Test Split (80:20)
                        │
                        ▼
        🤖 Machine Learning Model Training
                        │
                        ▼
          📊 Model Performance Evaluation
                        │
                        ▼
          🏆 Best Model Selection
                        │
                        ▼
         💾 Model Serialization (.pkl)
                        │
                        ▼
       🌐 Streamlit Web Application
                        │
                        ▼
          📧 Real-Time Email Prediction
```

---

# 1️⃣ Data Collection

The project begins by loading the **phishing_email.csv** dataset using the **Pandas** library.

The dataset contains thousands of phishing and legitimate emails that are used to train the machine learning models.

**Dataset Summary**

- Dataset Type : CSV
- Total Emails : **82,078**
- Language : English
- Problem Type : Binary Classification
- Labels:
  - **0 → Legitimate Email**
  - **1 → Phishing Email**

---

# 2️⃣ Data Preprocessing

Raw email text usually contains unwanted information that can negatively affect model performance.

To improve data quality, several preprocessing steps were performed.

### ✔ Text Cleaning

- Convert all text to lowercase
- Remove punctuation
- Remove special characters
- Remove numbers
- Remove URLs
- Remove extra white spaces

### ✔ NLP Preprocessing

- Tokenization
- Stopword Removal
- Lemmatization

These preprocessing techniques reduce noise and improve the overall quality of the input data.

---

# 3️⃣ Feature Extraction

Machine Learning models cannot directly understand textual data.

Therefore, the cleaned email text was converted into numerical feature vectors using the **TF-IDF (Term Frequency–Inverse Document Frequency)** technique.

### Why TF-IDF?

- Converts text into numerical values
- Highlights important words
- Reduces the effect of common words
- Improves classification performance

The project uses the **top 5,000 TF-IDF features** for training.

---

# 4️⃣ Data Splitting

After feature extraction, the dataset was divided into:

| Dataset | Percentage |
|----------|-----------:|
| Training Data | 80% |
| Testing Data | 20% |

The training data was used to train the models, while the testing data was used to evaluate their performance on unseen emails.

---

# 5️⃣ Machine Learning Model Training

Four different Machine Learning algorithms were implemented and compared.

### 🔹 Logistic Regression

A simple yet highly effective linear classification algorithm widely used for text classification.

---

### 🔹 Naive Bayes

A probabilistic classifier that predicts email categories based on word probabilities.

---

### 🔹 Random Forest

An ensemble learning algorithm that combines multiple decision trees to produce highly accurate predictions.

This model achieved the **highest performance** and was selected as the final model.

---

### 🔹 Neural Network (MLP Classifier)

A feed-forward Artificial Neural Network capable of learning complex textual patterns.

---

# 6️⃣ Model Evaluation

Each model was evaluated using standard classification metrics.

### Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

These metrics provide a complete understanding of each model's prediction performance.

---

# 📊 Model Performance

| Machine Learning Model | Accuracy |
|-------------------------|----------|
| Logistic Regression | **97.99%** |
| Naive Bayes | **96.04%** |
| Random Forest | **98.43%** ⭐ |
| Neural Network (MLP) | **97.70%** |

---

# 🏆 Best Performing Model

After comparing all four machine learning models, **Random Forest** delivered the best overall performance.

### Final Results

- **Accuracy:** 98.43%
- **Precision:** 98.57%
- **Recall:** 98.41%
- **F1-Score:** 98.49%

Its ensemble learning approach successfully captured complex phishing patterns while maintaining a very low number of classification errors.

Therefore, **Random Forest** was selected as the final model for deployment.

---

# 💾 Model Deployment

The trained Random Forest model and TF-IDF vectorizer were saved using **Pickle (.pkl)** files.

These saved models are loaded into a **Streamlit Web Application**, allowing users to paste any email and instantly receive:

- 📧 Email Classification
- 📊 Confidence Score
- 🟢 Legitimate or 🔴 Phishing Prediction
- ⚠️ Risk Assessment

This makes the system fast, reusable, and suitable for real-world phishing email detection.

---

# 🤖 Machine Learning Model Comparison

To identify the most effective algorithm for phishing email detection, four different supervised machine learning models were implemented, trained, and evaluated using the same preprocessed dataset and TF-IDF feature representation.

Each model was assessed using standard classification metrics, including **Accuracy, Precision, Recall, F1-Score, and Confusion Matrix**. This comparative analysis helped determine which algorithm provides the best balance between prediction accuracy and generalization performance.

---

# 📊 Performance Comparison

| Model | Accuracy | Precision | Recall | F1-Score | Status |
|-------|:--------:|:---------:|:------:|:--------:|:------:|
| 🟦 Logistic Regression | **97.99%** | **97.86%** | **98.30%** | **98.08%** | Excellent |
| 🟨 Naive Bayes | **96.04%** | **97.45%** | **94.90%** | **96.16%** | Good |
| 🟩 Random Forest | **98.43%** | **98.57%** | **98.41%** | **98.49%** | ⭐ Best Model |
| 🟪 Neural Network (MLP) | **97.70%** | **97.76%** | **97.84%** | **97.80%** | Excellent |

---

# 📈 Model Ranking

| Rank | Model | Accuracy |
|------|--------|----------|
| 🥇 1 | **Random Forest** | **98.43%** |
| 🥈 2 | **Logistic Regression** | **97.99%** |
| 🥉 3 | **Neural Network (MLP)** | **97.70%** |
| 4️⃣ | **Naive Bayes** | **96.04%** |

---

# 🔍 Individual Model Analysis

## 🟦 Logistic Regression

Logistic Regression delivered excellent classification performance with an **accuracy of 97.99%**. The model achieved high Precision and Recall while producing very few classification errors, making it a strong baseline model for phishing email detection.

### Advantages

- Fast training and prediction
- Performs well on text classification problems
- Low computational cost
- Easy to interpret

---

## 🟨 Naive Bayes

Naive Bayes achieved an **accuracy of 96.04%**. It provided fast predictions and performed well for email classification. However, compared to the other models, it produced a higher number of false negatives, which slightly reduced its overall performance.

### Advantages

- Very fast training
- Efficient for text data
- Low memory usage
- Suitable for large datasets

---

## 🟩 Random Forest ⭐

Random Forest achieved the **highest accuracy of 98.43%**, making it the best-performing model in this project.

By combining multiple decision trees, Random Forest successfully learned complex phishing patterns and significantly reduced classification errors.

### Advantages

- Highest prediction accuracy
- Excellent Precision and Recall
- Robust against overfitting
- Handles high-dimensional data efficiently
- Reliable on unseen emails

---

## 🟪 Neural Network (MLP)

The Neural Network achieved an **accuracy of 97.70%** and successfully captured complex relationships within the email text.

Although it performed better than Naive Bayes, it was slightly less accurate than Logistic Regression and Random Forest.

### Advantages

- Learns complex text patterns
- Good generalization ability
- Effective for nonlinear classification

---

# 🏆 Best Performing Model

After comparing all four machine learning algorithms, **Random Forest** was selected as the final model for deployment.

### Final Performance

- ✅ Accuracy : **98.43%**
- ✅ Precision : **98.57%**
- ✅ Recall : **98.41%**
- ✅ F1-Score : **98.49%**

### Why Random Forest?

- Highest overall accuracy
- Lowest number of misclassifications
- Balanced Precision and Recall
- Excellent generalization on unseen emails
- Robust ensemble learning technique
- Most reliable model for phishing email detection

---

# 📌 Conclusion

The comparative study demonstrates that all four machine learning algorithms are capable of detecting phishing emails with high accuracy. However, **Random Forest consistently outperformed the other models across all evaluation metrics**, making it the most suitable choice for this project.

Its ability to accurately classify phishing and legitimate emails while minimizing false predictions makes it a reliable solution for real-world email security applications.

---
# 📈 Results

The performance of the proposed **AI-Based Phishing Email Detection System** was evaluated using four different supervised machine learning algorithms. All models were trained on the same preprocessed dataset using **TF-IDF feature extraction** and tested on unseen email data to ensure a fair comparison.

Each model was evaluated using five standard classification metrics:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

The experimental results demonstrate that all models achieved excellent classification performance. However, **Random Forest consistently outperformed the other algorithms**, achieving the highest overall accuracy and the lowest number of classification errors.

---

# 🏆 Overall Performance

| Machine Learning Model | Accuracy | Precision | Recall | F1-Score |
|-------------------------|:--------:|:---------:|:------:|:--------:|
| Logistic Regression | **97.99%** | **97.86%** | **98.30%** | **98.08%** |
| Naive Bayes | **96.04%** | **97.45%** | **94.90%** | **96.16%** |
| Random Forest ⭐ | **98.43%** | **98.57%** | **98.41%** | **98.49%** |
| Neural Network (MLP) | **97.70%** | **97.76%** | **97.84%** | **97.80%** |

---

# 🥇 Best Performing Model

After comparing all four algorithms, **Random Forest** achieved the best overall performance.

### Final Evaluation Metrics

| Metric | Value |
|---------|-------|
| Accuracy | **98.43%** |
| Precision | **98.57%** |
| Recall | **98.41%** |
| F1-Score | **98.49%** |

---

# 📊 Random Forest Confusion Matrix

| Prediction | Count |
|------------|------:|
| True Negative (TN) | **7,725** |
| False Positive (FP) | **122** |
| False Negative (FN) | **136** |
| True Positive (TP) | **8,433** |

The confusion matrix shows that the model correctly classified the vast majority of emails while producing very few false predictions.

---

# 📌 Key Findings

- Successfully classified **phishing** and **legitimate** emails with high accuracy.
- Random Forest achieved the **highest overall performance** among all evaluated models.
- Logistic Regression also delivered strong and consistent results.
- Neural Network (MLP) effectively learned complex email patterns and achieved competitive performance.
- Naive Bayes provided fast predictions with good accuracy but produced comparatively more false negatives.
- TF-IDF feature extraction significantly improved the quality of textual representations for machine learning.
- The combination of NLP preprocessing and supervised learning proved highly effective for phishing email detection.

---

# 📉 Performance Ranking

| Rank | Model | Accuracy |
|------|--------|----------|
| 🥇 1 | **Random Forest** | **98.43%** |
| 🥈 2 | **Logistic Regression** | **97.99%** |
| 🥉 3 | **Neural Network (MLP)** | **97.70%** |
| 4️⃣ | **Naive Bayes** | **96.04%** |

---

# 🚀 Usage

After successfully installing the project and launching the Streamlit application, you can begin testing email content for phishing detection.

The application uses the trained **Random Forest** machine learning model to analyze the email text and classify it as either **Phishing** or **Legitimate**.

# 📊 Output

The application provides the following information:

- 📧 Email Classification
- 📈 Prediction Confidence
- 🟢 Legitimate or 🔴 Phishing
- ⚠️ Risk Level
- 📊 Prediction Probability

---

# 🧪 Example 1 — Legitimate Email

### Input

```text
Subject: Meeting Reminder

Hello Team,

This is a reminder that our weekly project meeting is scheduled for tomorrow at 10:00 AM in the conference room.

Please review the project documents before attending.

Regards,
Project Manager
```

### Output

```text
Prediction:
🟢 Legitimate Email

Confidence:
99%

Risk Level:
Low
```

---

# 🧪 Example 2 — Phishing Email

### Input

```text
Subject: Urgent Account Verification Required

Dear Customer,

Your account has been temporarily suspended due to unusual activity.

Please verify your account immediately by clicking the secure link below.

https://secure-login-update.com

Failure to verify your account within 24 hours will result in permanent account suspension.

Thank you.

Security Team
```

### Output

```text
Prediction:
🔴 Phishing Email

Confidence:
98%

Risk Level:
High
```

---

# 🔄 Complete Prediction Workflow

```text
User Enters Email
        │
        ▼
Text Preprocessing
        │
        ▼
TF-IDF Vectorization
        │
        ▼
Random Forest Prediction
        │
        ▼
Confidence Calculation
        │
        ▼
Prediction Result
        │
        ▼
Display Output in Streamlit
```

---

# 💡 Tips for Better Predictions

- Paste the complete email content instead of only the subject line.
- Include the email body for more accurate predictions.
- Test multiple emails to compare prediction confidence.
- Avoid using extremely short email snippets.

---

# ⚡ Performance

- **Best Model:** Random Forest
- **Accuracy:** **98.43%**
- **Prediction Time:** Less than 1 second (typical on a standard computer)
- **Supported Input:** English email text
- **Output:** Binary Classification (Legitimate or Phishing)

---

# 🛡️ Practical Applications

This project can be adapted for:

- Email security systems
- Enterprise cybersecurity solutions
- Educational demonstrations
- Machine Learning projects
- NLP-based text classification
- Phishing awareness tools
- Research in cybersecurity

---
# 🚀 Usage

Once the project has been installed successfully, you can launch the Streamlit application and begin testing email content for phishing detection.

The application uses the trained **Random Forest** model to classify emails as **Phishing** or **Legitimate** based on their textual content.

---

## ▶️ Run the Application

Open a terminal inside the project directory and execute:

```bash
streamlit run app.py
```

The application will automatically start and open in your default web browser.

If it does not open automatically, visit:

```text
http://localhost:8501
```

---

# 📧 How It Works

The complete prediction process consists of the following steps:

### Step 1 — Launch the Application

Start the Streamlit application using the command above.

---

### Step 2 — Enter Email Content

Copy and paste the complete email content into the input text area.

---

### Step 3 — Click **Analyze Email**

The system immediately begins processing the email.

---

### Step 4 — Email Preprocessing

Before prediction, the email text is cleaned using several Natural Language Processing (NLP) techniques:

- Convert text to lowercase
- Remove punctuation
- Remove special characters
- Remove numbers
- Remove URLs
- Remove extra spaces
- Remove stopwords
- Apply lemmatization

---

### Step 5 — Feature Extraction

The cleaned text is transformed into numerical vectors using the **TF-IDF (Term Frequency–Inverse Document Frequency)** technique.

---

### Step 6 — Model Prediction

The processed data is passed to the trained **Random Forest** classifier, which predicts whether the email is **Phishing** or **Legitimate**.

---

### Step 7 — View Results

The application displays:

- 📧 Email Classification
- 📊 Prediction Confidence
- 📈 Probability Score
- ⚠️ Risk Level
- 🤖 Model Used (Random Forest)

---

# 🔄 Prediction Workflow

```text
User Input
     │
     ▼
Email Preprocessing
     │
     ▼
TF-IDF Vectorization
     │
     ▼
Random Forest Prediction
     │
     ▼
Confidence Calculation
     │
     ▼
Prediction Result
```

---

# 🧪 Sample Test Emails

## ✅ Legitimate Email

```text
Subject: Weekly Project Meeting

Hello Team,

This is a reminder that our weekly project meeting is scheduled for tomorrow at 10:00 AM.

Please review the project documents before attending.

Regards,
Project Manager
```

### Expected Output

```text
Prediction      : Legitimate Email

Confidence      : High (≈99%)

Risk Level      : Low
```

---

## ⚠️ Phishing Email

```text
Subject: Urgent Account Verification Required

Dear Customer,

Your account has been temporarily suspended due to suspicious activity.

Please verify your account immediately by clicking the secure link below.

https://secure-login-update.com

Failure to verify your account within 24 hours will permanently disable your account.

Thank you.

Security Team
```

### Expected Output

```text
Prediction      : Phishing Email

Confidence      : High (≈98%)

Risk Level      : High
```

---

# 📊 Prediction Output

The application provides the following information for every prediction:

| Output | Description |
|---------|-------------|
| 📧 Email Classification | Phishing or Legitimate |
| 📊 Confidence Score | Model confidence percentage |
| 📈 Prediction Probability | Probability of each class |
| ⚠️ Risk Level | Low / Medium / High |
| 🤖 Model | Random Forest |

---

# ⚡ Performance

- **Best Model:** Random Forest
- **Accuracy:** **98.43%**
- **Precision:** **98.57%**
- **Recall:** **98.41%**
- **F1-Score:** **98.49%**
- **Prediction Time:** Less than one second
- **Input Type:** English Email Text
- **Output Type:** Binary Classification

---

# 💡 Best Practices

For the most accurate predictions:

- Paste the complete email instead of only the subject.
- Include both the subject and email body whenever possible.
- Avoid testing with very short text snippets.
- Use real-world email content for evaluation.

---

# 🛡️ Applications

This project can be used for:

- Email Security Systems
- Cybersecurity Research
- Machine Learning Demonstrations
- NLP Projects
- Educational Purposes
- Phishing Awareness Training
- AI-Based Email Filtering

---

# 👨‍💻 Author

<div align="center">

## Aditya Kant Jha

**B.Tech Computer Science & Engineering**  
**Government Engineering College, Palamu**  
**Artificial Intelligence | Machine Learning | Cybersecurity | Python Developer**

---

### 📬 Contact Information

📧 **Email:** your-email@example.com

💼 **LinkedIn:** https://www.linkedin.com/in/akj1729

💻 **GitHub:** https://github.com/yourusername

---

### 🚀 About Me

I am a Computer Science undergraduate with a strong interest in **Artificial Intelligence, Machine Learning, Natural Language Processing, and Cybersecurity**. I enjoy building practical AI applications that solve real-world problems through data-driven approaches.

This project demonstrates my understanding of the complete Machine Learning development lifecycle, including data preprocessing, feature engineering, model training, evaluation, and deployment using **Python**, **Scikit-learn**, **NLP**, and **Streamlit**.

I am continuously learning and exploring new technologies while building projects that strengthen my problem-solving skills and software development experience.

---

### 🛠️ Technical Skills

- Python
- Machine Learning
- Natural Language Processing (NLP)
- Scikit-learn
- Streamlit
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Git & GitHub

---

### 📌 Project Developed

🛡️ **AI-Based Phishing Email Detection System**

An intelligent phishing email detection system that uses Machine Learning and Natural Language Processing to classify emails as **Phishing** or **Legitimate** with **98.43% accuracy** using the **Random Forest** algorithm.

---

### ⭐ If you found this project helpful

Please consider giving this repository a **⭐ Star** on GitHub.

Your support motivates me to build more open-source AI and Machine Learning projects.

---

**Thank you for visiting this repository!**

</div>
