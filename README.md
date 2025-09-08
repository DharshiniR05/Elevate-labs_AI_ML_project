# Elevate-labs_AI_ML_project
# News Article Classification(Fake/Real)

## 📌 Overview  
The **Fake News Detection System** is a machine learning project developed as part of the Elevate Internship (AI & ML).  
It uses **Natural Language Processing (NLP)** techniques and **Logistic Regression** to classify news articles as either **Real** or **Fake**.  
The system is deployed as an interactive **Streamlit web application**, allowing users to paste article text and instantly check its credibility.  

## 🎯 Objectives  
- Preprocess and clean raw text data.  
- Convert cleaned text into numerical features using **TF-IDF**.  
- Train and evaluate a robust machine learning classifier.  
- Deploy the model into a user-friendly web app.  

## 🛠️ Tools & Technologies  
- **Python** (Core Language)  
- **Pandas / NumPy** (Data Handling)  
- **NLTK / re** (Text Preprocessing)  
- **Scikit-learn** (ML Algorithms, TF-IDF, Model Training)  
- **Joblib** (Model Serialization)  
- **Streamlit** (Web Application Deployment)  

## 🔄 Workflow  
1. **Data Collection** – Used the Kaggle Fake & Real News Dataset (~44,000 articles).  
2. **Data Preprocessing** – Removal of URLs, punctuation, numbers, stopwords, and lemmatization.  
3. **Feature Extraction** – Applied **TF-IDF vectorization** for numerical representation.  
4. **Model Training** – Trained a **Logistic Regression** classifier with 80/20 train-test split.  
5. **Evaluation** – Achieved **98.8% accuracy**, with precision, recall, and F1-score at 0.99.  
6. **Deployment** – Built a **Streamlit app** for real-time predictions.  

## 📊 Results  
- **Accuracy:** 98.8%  
- **Precision & Recall:** 0.99 each  
- **F1-Score:** 0.99  
- Very few misclassifications as confirmed by the confusion matrix.  


## 🚀 How to Run the Project  

### 1. Clone the Repository  

git clone https://github.com/your-username/fake-news-detection.git
cd fake-news-detection
