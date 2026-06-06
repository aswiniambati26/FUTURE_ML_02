# FUTURE_ML_02
Support Ticket Classification
# Support Ticket Classification and prioritization Using Machine Learning

## About the Project

Customer support teams receive a large number of tickets every day, making it difficult to manually sort and assign them to the appropriate departments. This project aims to automate that process by using Machine Learning and Natural Language Processing (NLP) techniques to classify support tickets into predefined categories.

By automatically identifying the category of a ticket, organizations can improve response times, reduce manual effort, and enhance overall customer service efficiency.

---

## Problem Statement

Manually categorizing customer support tickets is a time-consuming process and can lead to delays or incorrect routing. The objective of this project is to build a machine learning model that can accurately predict the category of a support ticket based on its text description.

---

## Dataset

The project uses a support ticket dataset containing ticket descriptions along with their corresponding categories.

The dataset includes:
- Ticket descriptions
- Customer issue details
- Ticket categories (target variable)

The dataset file used in this project is:

`all_tickets_processed_improved_v3.csv`

https://www.kaggle.com/datasets/adisongoh/it-service-ticket-classification-dataset

---

## Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Workflow

### 1. Data Loading
The dataset is imported and inspected for missing values and inconsistencies.

### 2. Text Preprocessing
The ticket descriptions are cleaned using NLP techniques such as:
- Converting text to lowercase
- Removing punctuation
- Removing stop words
- Tokenization

### 3. Feature Extraction
Text data is transformed into numerical features using machine learning text vectorization techniques.

### 4. Model Training
The processed data is used to train classification models capable of predicting ticket categories.

### 5. Model Evaluation
The model performance is evaluated using standard classification metrics.

---

## Evaluation Metrics

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## Results

The trained model successfully classifies support tickets into their respective categories, demonstrating the effectiveness of machine learning and NLP techniques in automating customer support workflows.

---

---

## How to Run

1. Download or clone the repository.
2. Extract the dataset that is provided in ZIP format.
3. Open the Jupyter Notebook.
4. Run all cells sequentially.
5. View the classification results and performance metrics.

---


## Conclusion

This project demonstrates how Machine Learning and Natural Language Processing can be applied to automate support ticket classification. Such systems can significantly reduce manual effort and improve the efficiency of customer support operations.

---
