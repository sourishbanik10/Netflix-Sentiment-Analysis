# 🎬 Netflix Sentiment Analysis

## 📌 Project Overview

This project performs Sentiment Analysis on Netflix user reviews using Machine Learning.

The goal is to classify reviews as:

- Positive
- Negative

The model was trained on more than 130,000 Netflix reviews and achieved 88% accuracy.

---

## 🧠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📊 Dataset

Source: Kaggle – Netflix Reviews Dataset

Dataset contains:
- Review text (content)
- Review rating (score)

Ratings were converted into:
- Positive (4–5 stars)
- Negative (1–2 stars)
- Neutral reviews were removed

---

## ⚙️ Project Workflow

1. Data Cleaning
   - Removed special characters
   - Converted to lowercase
   - Removed stopwords
   - Applied stemming

2. Feature Extraction
   - Used TF-IDF Vectorizer (5000 features)

3. Model Training
   - Logistic Regression
   - Train-test split (80-20)

4. Evaluation
   - Accuracy Score
   - Classification Report
   - Confusion Matrix

---

## 📈 Model Performance

Accuracy: 88%

The confusion matrix and classification report show strong performance for both Positive and Negative classes.

---

## 🧪 Example Prediction

predict_review("This show was amazing and very interesting")

Output:

Positive










---

## 🚀 How To Run This Project

1. Clone this repository
2. Install required libraries:

3. Open Jupyter Notebook:


4. Run the notebook step-by-step

---

## 🔮 Future Improvements

- Compare multiple ML models
- Use Deep Learning (LSTM / BERT)
- Deploy as a Web App using Streamlit
- Add real-time sentiment prediction

---

## 👨‍💻 Author

Your Name  
B.Tech CSE (AIML)

