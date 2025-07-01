

---

```markdown
# 📧 SMS Spam Detection using Logistic Regression

This project builds a machine learning model to classify SMS messages as **spam** or **ham** using **Logistic Regression**. It leverages natural language processing (NLP) techniques to process and vectorize the text and train a classifier using the SMS Spam Collection Dataset.

---

## 📂 Dataset

- **Name**: SMS Spam Collection Dataset  
- **Source**: [Kaggle](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)  
- **Size**: ~5,500 messages  
- **Columns**:
  - `label`: `ham` or `spam`
  - `text`: message content

---

## 🔧 Tools & Libraries

- Python
- pandas
- scikit-learn
- matplotlib / seaborn
- CountVectorizer (Bag-of-Words)

---

## 🧠 Workflow

1. **Load Dataset**: Read and clean the CSV file
2. **Preprocessing**:
   - Remove null/empty values
   - Map labels: `ham` → 0, `spam` → 1
3. **Feature Extraction**:
   - Use `CountVectorizer` to convert text to numeric vectors
4. **Model Training**:
   - Train a Logistic Regression model
5. **Evaluation**:
   - Accuracy, classification report, confusion matrix
6. **Prediction**:
   - Classify new SMS messages as spam or ham

---

## 📈 Results

- Achieved over **95% accuracy**
- High precision and recall for spam classification
- Visualized confusion matrix for performance insight

---

## 💡 Future Improvements

- Use **TF-IDF** vectorization
- Try other models (Naive Bayes, SVM)
- Add stemming/lemmatization
- Deploy with **Streamlit** or **Flask**
- Visualize spam vs. ham with **WordCloud**

---

## 📌 Sample Prediction

```

Message: "Free entry in a prize draw!" → Spam
Message: "Let's catch up tomorrow." → Ham

```

---

## 🏁 Conclusion

This project shows that Logistic Regression, combined with text vectorization, can effectively classify spam messages. It serves as a strong baseline for more advanced NLP tasks.


