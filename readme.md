# Naive Bayes Classifier

This repository provides an intuitive explanation and implementation of the **Naive Bayes Classifier**, one of the most widely used probabilistic machine learning algorithms for classification tasks.

The goal of this project is to help understand the mathematical intuition behind Naive Bayes and how it can be implemented in Python.

---

## What is Naive Bayes?

Naive Bayes is a **probabilistic classification algorithm** based on **Bayes' Theorem**.  
It assumes that features are **independent of each other given the class label** (this is called the *naive assumption*).

Despite this strong assumption, Naive Bayes performs very well in many real-world problems.

It is commonly used in:

- Spam detection
- Text classification
- Sentiment analysis
- Document categorization
- Medical diagnosis

---

## Bayes Theorem

Naive Bayes is based on Bayes' theorem:

P(C|X) = P(X|C) * P(C) / P(X)

Where:

- **P(C|X)** → Posterior probability (probability of class given features)
- **P(X|C)** → Likelihood
- **P(C)** → Prior probability of class
- **P(X)** → Evidence

The classifier predicts the class with the **maximum posterior probability**.

---

## Types of Naive Bayes

There are several variants of Naive Bayes:

1. **Gaussian Naive Bayes**
   - Used for continuous data
   - Assumes data follows a normal distribution

2. **Multinomial Naive Bayes**
   - Used for text classification
   - Works with word frequencies

3. **Bernoulli Naive Bayes**
   - Works with binary features

---

## Project Structure

naive-bayes-from-scratch
│
├── Datasets/
├── Notebooks
├── Notes/
├── README.md


---

## Implementation

This repository includes:

- Step-by-step explanation of Naive Bayes
- Probability calculations
- Python implementation
- Example dataset
- Model prediction

Libraries used:

- NumPy
- Pandas
- Scikit-learn (for comparison)

---

## Example Workflow

1. Load dataset
2. Preprocess the data
3. Train Naive Bayes model
4. Make predictions
5. Evaluate model performance

---

## 👨‍💻 Author  
**Mohd Uzaif**  
🎓 *M.Tech (AI & ML), Jamia Millia Islamia University*   
---

⭐ *If you find these notebooks useful, consider giving this repo a star — it helps and motivates continuous learning!*  
EOF