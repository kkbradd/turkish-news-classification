# turkish-news-classification

## Project Overview
This project focuses on classifying Turkish news articles into categories such as Siyaset (Politics) and Çevre (Environment) using machine learning models.

## Main Steps

Data Loading: Load the dataset containing Turkish news articles and their respective categories.

Preprocessing: Apply text preprocessing such as tokenization, stemming, and cleaning of punctuation and special characters.

Modeling: Train models including Logistic Regression and Random Forest on the cleaned data.

Evaluation: Evaluate the models using accuracy, precision, recall, F1-score, and confusion matrix.

## Dataset
The dataset consists of:

Text: The news article content.
Category: The corresponding label (e.g., Siyaset, Çevre).
Sample data:

ID	Text	Category
133	"avrupa alışık olmadığını belirtti..."	Siyaset

125	"vicdanlarda kabul görmeyecek siyaseten sor..."	Siyaset

141	"chp kızan hdp ilde aday çıkaracak..."	Siyaset

## Conclusion
This project demonstrates how to classify Turkish news articles using traditional machine learning models. Future work can involve testing advanced models like LSTM or BERT for potentially better performance.
