# Phishing Email Detection (Machine Learning & Deep Learning)

## Overview
This project explores and compares multiple machine learning and deep learning approaches for detecting phishing emails. It was developed as part of a final-year Computer Science dissertation.

The project builds a full NLP pipeline including data preprocessing, feature extraction, model training, evaluation, and comparison of classical machine learning models against deep learning and transformer-based approaches.

---

## Objective
To evaluate and compare the performance of different models in classifying phishing vs legitimate emails, and analyse trade-offs between traditional ML and modern deep learning techniques.

---

## Models Implemented
The following models were trained and evaluated:

- Logistic Regression  
- Naive Bayes  
- Support Vector Machine (SVM)  
- Convolutional Neural Network (CNN)  
- Long Short-Term Memory (LSTM)  
- DistilBERT Transformer  

---

## Results Summary
- **SVM achieved 97.2% accuracy**
- **CNN achieved 99.0% recall**
- Transformer model (DistilBERT) was evaluated and compared against classical ML and deep learning models
- Analysis highlights trade-offs between model complexity, performance, and dataset size

---

## Dataset
A publicly available phishing email dataset from Hugging Face was used for training and evaluation.

---

## Technologies Used
- Python  
- PyTorch  
- Scikit-learn  
- Pandas  
- NumPy  
- Hugging Face Transformers  

---

## Pipeline Steps
1. Data collection and preprocessing  
2. Text cleaning and feature extraction  
3. Train-test split  
4. Model training (ML + DL models)  
5. Hyperparameter tuning  
6. Model evaluation using:
   - Accuracy  
   - Precision  
   - Recall  
   - F1-score  
   - Confusion Matrix  
7. Performance comparison and analysis  

---

## Key Skills Demonstrated
- Natural Language Processing (NLP)  
- Machine Learning model development  
- Deep learning with PyTorch  
- Transformer-based models  
- Data preprocessing and feature engineering  
- Model evaluation and comparison  
- Research and analytical thinking  

---

## How to Run the Project
1. Clone this repository:
   ```
   git clone https://github.com/AbdulHNawaz/phishing-email-detection.git
   ```

2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Open the Jupyter Notebook:
   ```
   jupyter notebook
   ```

4. Run all cells in the notebook

---

## Project Structure
```
phishing-email-detection/
│
├── phishing_detection.ipynb
├── presentation.pptx
├── README.md
└── requirements.txt (optional)
```

---

## Author
Abdul-Hannaan Nawaz  
BSc Computer Science (First Class Honours, 2026)
