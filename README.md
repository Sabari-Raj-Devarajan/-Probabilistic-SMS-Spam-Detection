# Probabilistic SMS Spam Detection

A Python-based machine learning project that classifies SMS messages as **Spam** or **Ham (Genuine)** using probability, Bayes' theorem, and Multinomial Naive Bayes.

## Technologies
- Python
- Pandas, NumPy, Matplotlib
- Scikit-learn
- Google Colab

## Dataset
- Source: [UCI SMS Spam Collection](https://archive.ics.uci.edu/dataset/228/sms+spam+collection)
- Original messages: 5,572
- Cleaned messages: 5,169

## Methodology
1. Load and clean the dataset.
2. Calculate prior and conditional probabilities.
3. Apply Bayes' theorem and analyse expectation and variance.
4. Convert text into word counts using `CountVectorizer`.
5. Train a Multinomial Naive Bayes classifier.
6. Evaluate performance and predict new SMS messages.

## Model Performance
- Accuracy: **98.16%**
- Spam Precision: **95.90%**
- Spam Recall: **89.31%**
- Spam F1-score: **92.49%**

## How to Run
1. Open the notebook in Google Colab.
2. Upload the dataset ZIP file if required.
3. Run all cells sequentially.
4. Enter an SMS to test the prediction.

## Author
**Sabari Raj Devarajan**  
B.Tech AI & ML, VIT Vellore  
Course: BAMAT207 – Probability and Statistics
