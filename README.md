# Deep Learning Text Classification – Sentiment Analysis

##Project Overview

This project was developed as **Task 2** for the **Alfido Tech AI & Machine Learning Internship**. The objective is to build a deep learning model that classifies movie reviews as **Positive** or **Negative** using Natural Language Processing (NLP) techniques.

The project demonstrates an end-to-end deep learning workflow, including text preprocessing, tokenization, sequence padding, model training, evaluation, visualization, and model saving.

---

## objective

* Build a deep learning model for text classification.
* Perform text preprocessing and tokenization.
* Train an LSTM-based neural network using TensorFlow/Keras.
* Evaluate model performance using standard classification metrics.
* Save the trained model for future inference.

---

## Dataset

**Dataset:** IMDB Movie Reviews Dataset

**Source:** TensorFlow/Keras Datasets

**Dataset Features:**

* 50,000 movie reviews
* Binary sentiment labels (Positive / Negative)
* Balanced dataset
* Top 10,000 most frequent words used for training

---

## technologies Used

* Python 3
* Google Colab
* TensorFlow
* Keras
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

---

##Project Workflow

### 1. Data Preprocessing

* Loaded the IMDB dataset
* Applied tokenization
* Converted reviews into integer sequences
* Applied sequence padding

### 2. Deep Learning Model

* Embedding Layer
* LSTM Layer
* Dropout Layer
* Dense Hidden Layer
* Sigmoid Output Layer

### 3. Model Training

* Adam Optimizer
* Binary Cross-Entropy Loss
* Early Stopping

### 4. Model Evaluation

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* Training & Validation Accuracy Curves
* Training & Validation Loss Curves

### 5. Model Saving

* Saved the trained model in `.h5` format for future inference.

---

##Project Structure

```text id="v1p4zw"
Deep-Learning-Text-Classification/
│── Deep_Learning_Text_Classification.ipynb
│── sentiment_analysis_model.h5
│── Task_2_Deep_Learning_Text_Project_Final_Report.pdf
│── README.md
```

---

##Results

The LSTM model successfully learned sentiment patterns from movie reviews and achieved strong classification performance.

### Model Highlights

* Efficient text preprocessing using tokenization
* Deep learning-based sentiment classification
* Stable training with Early Stopping
* Effective evaluation using multiple performance metrics
* Ready for deployment and inference

---

##Learning Outcomes

* Understood the Natural Language Processing (NLP) pipeline
* Applied tokenization and sequence padding
* Built an LSTM-based deep learning model
* Evaluated model performance using multiple metrics
* Visualized training and validation performance
* Saved the trained model for deployment

---

## Internship Requirements Covered

* ✔ Deep Learning Model
* ✔ Text Classification
* ✔ Tokenization
* ✔ LSTM Network
* ✔ Training Curves
* ✔ Accuracy
* ✔ Precision
* ✔ Recall
* ✔ F1-Score
* ✔ Confusion Matrix
* ✔ Saved Model
* ✔ Inference

---

## Future Improvements

* Fine-tune pretrained transformer models such as BERT or DistilBERT
* Use pretrained word embeddings like GloVe or FastText
* Perform hyperparameter tuning
* Deploy the model using Flask, FastAPI, or Streamlit
* Extend the model to support multi-class sentiment analysis

---

## Author

**JEEVITH HM**

AI & Machine Learning Intern

Alfido Tech Internship
