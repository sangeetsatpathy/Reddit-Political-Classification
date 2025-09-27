# Reddit Political Classification  

Automated political stance classification of Reddit posts/comments using natural language processing (NLP) and machine learning. This project builds a pipeline that ingests raw Reddit text, transforms it via feature engineering, trains classification models, and evaluates performance — with a strong focus on interpretability and real-world application.

---

## 🚀 Project Overview

This project addresses the challenging task of **classifying political orientation** (e.g. liberal vs conservative, or multiple classes) from Reddit content. 

Specifically, I trained a classification model to classify a statement as liberal or conservative, based on Reddit posts (accessed using the Python Reddit API Wrapper). 

---

## 📘 Notebook / Module Highlights & Skills Illustrated

Here’s a deeper dive into what each major part accomplishes and which skills it showcases:

### **Data Preprocessing & Cleaning**

- **Text cleaning**: lowercasing, punctuation removal, stopword filtering, tokenization, stemming/lemmatization  
- **Handling noise & edge cases**: removing URLs, user mentions, emojis, slang, and other Reddit artifacts  
- **Balancing the dataset**: dealing with class imbalance via undersampling, oversampling, or synthetic methods  
- **Train / test splits**: ensuring no data leakage between splits  

**Skills**: Text preprocessing, data cleaning, balancing techniques, robust data handling.

### **Feature Engineering & Representations**

- **Bag-of-Words / TF-IDF features**: constructing term frequency or inverse document frequency vectors  
- **n-grams, part-of-speech tags, sentiment scores**: generating richer features from text  
- **Dimensionality reduction**: Systematically removed words that added unnecessary noise to reduce feature space  

**Skills**: Feature engineering in NLP, vectorization, dimensionality reduction.

### **Model Training & Hyperparameter Tuning**

- Training classification models over several models: logistic regression, Naive Bayes, SVM, Decision Tree classifiers, and Multilayer Perceptron.
- Using **cross-validation**, grid search to tune hyperparameters  

**Skills**: Model selection, hyperparameter optimization, evaluation rigor.

### **Model Evaluation & Interpretation**

- Compared different classifiers for the task and used the one with the largest test accuracy
- Interpretted possible reasons for overfitting
- Analyzed individual model performance before data cleaning versus after data cleaning.

---

## 🧠 Core Skills Demonstrated

- **NLP & Text Analytics**: working end-to-end with textual data  
- **Machine Learning / Classification**: tuning models for real-world tasks  
- **Feature engineering & interpretability**: not just black-box models  
- **Experiment design / validation**: avoiding overfitting, robust evaluations  
- **Critical thinking in error analysis & bias**: understanding model weaknesses

--
## Effect of Data Cleaning on Train & Test Accuracies (for various models)

<img width="678" height="492" alt="Screenshot 2025-09-26 at 9 51 15 AM" src="https://github.com/user-attachments/assets/e0b4dbbe-3b97-4d2f-a4d5-ff6b8cacdadb" />

<img width="678" height="492" alt="Screenshot 2025-09-26 at 9 51 06 AM" src="https://github.com/user-attachments/assets/6735c996-aff3-4ac7-a0e7-4b55667b4fd1" />
<img width="875" height="492" alt="Screenshot 2025-09-26 at 9 50 53 AM" src="https://github.com/user-attachments/assets/0053b0bb-14c5-49c2-9023-2e0d895c2ffb" />
