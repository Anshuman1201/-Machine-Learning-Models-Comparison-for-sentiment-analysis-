# Machine Learning Models Comparison for Sentiment Analysis

## Project Overview
This project focuses on comparing three machine learning models—**LSTM, SVM, and Naive Bayes**—for sentiment analysis across three diverse datasets:

1. **Twitter Sentiment Dataset** - Contains sentiment-labeled tweets representing positive, negative, and neutral opinions.
2. **Amazon Reviews Dataset** - Includes customer reviews from Amazon, reflecting user opinions on product quality and experiences.
3. **IMDB Movie Review Dataset** (Keras) - Consists of movie reviews labeled as positive or negative.

The objective is to evaluate which model performs best on different datasets using accuracy, confusion matrices, and visual analysis.

---

## Datasets
| Dataset               | Source              | Description                                | Size       |
|-----------------------|---------------------|------------------------------------------|------------|
| Twitter Sentiment    | Kaggle              | Tweets with sentiment labels               | 162,980    |
| Amazon Reviews       | Kaggle              | Product reviews with user sentiments      | 10,000     |
| IMDB Movie Reviews   | Keras (Built-in)   | Movie reviews labeled positive or negative| 50,000     |


---

## Models Used
1. **LSTM (Long Short-Term Memory)**
   - Suitable for sequential data and context understanding.

2. **SVM (Support Vector Machine)**
   - Effective for high-dimensional spaces and text classification.

3. **Naive Bayes**
   - Probabilistic model, efficient for text classification tasks.

---

## Project Structure
```
├── LSTM_IMDB.ipynb
├── Naive_bayes_imdb.ipynb
├── Naive_bayes_twitter.ipynb
├── README.md
├── SVM_IMDB.ipynb
├── SVM_Twitter.ipynb
├── SVM_amazon.ipynb
├── Twitter_Data.csv
├── amazonreviews1.csv
├── lstm_amazonreview.ipynb
├── lstm_twitter.ipynb
├── naive_bayes_amazon.ipynb
```

---

## Evaluation Metrics
- **Accuracy Score**
- **Confusion Matrix**
- **Precision, Recall, F1-Score**
- **Visualization (Matplotlib)**

We used Matplotlib for plotting the results and confusion matrices to evaluate model performance.

---

## Results
The evaluation showed the following accuracies across datasets:

| Model        | Twitter Dataset | Amazon Dataset | IMDB Dataset |
|---------------|----------------|---------------|--------------|
| LSTM         | TBD            | TBD           | TBD          |
| SVM          | TBD            | TBD           | TBD          |
| Naive Bayes  | TBD            | TBD           | TBD          |

> *Results will be updated after final evaluation.*

---

## Team Members
1. **Anshuman Tamrakar**
2. **Anuj Tripathi**
3. **Abhinav Bhargav**

---

## Project Guide
**Mr. Mukesh Sakle**  
Assistant Professor, IT Department, SGSITS Indore

---

## License
This project is licensed under the MIT License.
