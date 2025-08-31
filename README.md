# Sentiment Analysis on Movie Reviews  

## Overview  
This project focuses on **sentiment analysis** of movie reviews using machine learning models. The goal is to classify reviews as **Positive** or **Negative** and compare the performance of three models:  
- Logistic Regression  
- Random Forest  
- Naive Bayes  

---

##  Model Performance  

| Model                | Accuracy |
|-----------------------|----------|
| Logistic Regression   | **0.8750** |
| Random Forest         | 0.8479   |
| Naive Bayes           | 0.8482   |

Logistic Regression performed the best with the highest accuracy.  

---

##  Findings  
- **Logistic Regression**: Most accurate, balanced in predicting both positive and negative reviews.  
- **Random Forest**: Sometimes misclassified uncertain reviews as positive.  
- **Naive Bayes**: Performed well but slightly behind Logistic Regression.  

### Example Predictions  

| Review                      | Logistic Regression | Random Forest | Naive Bayes |
|-----------------------------|---------------------|---------------|-------------|
| “This movie is just crap”   | Negative (0)        | Negative (0)  | Negative (0) |
| “Could have been better”    | Negative (0)        | Positive (1)  | Negative (0) |

---

##  Visualizations  

### Model Accuracy Comparison  
![Accuracy Comparison](A_bar_chart_in_the_image_compares_the_accuracy_of_.png)  

### Confusion Matrix (Logistic Regression)  
![Confusion Matrix](confusion_matrix_logreg.png)  

---

##  How to Run  

1. Clone the repository  
   ```bash
   git clone https://github.com/yourusername/sentiment-analysis.git
   cd sentiment-analysis
