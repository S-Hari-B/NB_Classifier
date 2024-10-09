# Naive Bayes Text Classifier

## Project Overview

This project is a basic implementation of a Naive Bayes text classifier using the 20 Newsgroups dataset. The aim is to classify text documents into 20 categories. It serves as an introduction to text classification using Multinomial Naive Bayes, which is efficient for text data.

## Dataset

- 20 Newsgroups Dataset: A collection of 20,000 documents across 20 categories, available via scikit-learn.

## Preprocessing Steps

- TF-IDF Vectorization: Text was transformed into numerical form using TF-IDF with a max of 3,000 features.
- Data Split: Split into training (80%) and testing (20%) sets.

## Model Description

- Model: Multinomial Naive Bayes.
- Training: Trained on the TF-IDF vectorized data.
- Evaluation: Evaluated using accuracy and a classification report (precision, recall, f1-score).

## Results

- Accuracy: 81.1% on the test set.
- Detailed metrics provided in the classification report.

## Tools & Libraries Used

- Python
- Scikit-learn: For data loading, preprocessing, and modeling.
- Jupyter Notebook: For development.

## Future Improvements

- Hyperparameter Tuning: Adjust alpha to improve performance.
- Feature Selection: Experiment with different features or increase TF-IDF features.
- Advanced Models: Try SVM or Logistic Regression for comparison.

## Conclusion

This project demonstrates text classification using Naive Bayes. The Multinomial Naive Bayes model achieved good accuracy and shows how simple models can be effective for text data.
