# Fraud News Detection System

This project focuses on detecting fake news articles using deep learning and natural language processing techniques. The goal is to classify a given news article as either **Real** or **Fake** based on its textual content.

---

## Project Overview
Fake news has become a serious issue with the growth of online media. Manual verification is slow and unreliable, so this project explores how deep learning models can help automate fake news detection.

The system takes news text as input, processes it using NLP techniques, and predicts whether the news is genuine or fraudulent.

---

## Methodology
- Cleaned and preprocessed raw news text  
- Removed stopwords and special characters  
- Converted text into numerical sequences using tokenization  
- Applied padding to maintain uniform input length  
- Trained deep learning models for binary classification  

Two models were implemented:
- LSTM
- Bidirectional LSTM (BiLSTM)

BiLSTM performed better due to its ability to capture context from both past and future words.

---

## Results
- Achieved around **95–96% accuracy**
- Balanced precision and recall for both fake and real news classes
- BiLSTM showed slightly better performance compared to LSTM

---

## Tech Stack
- Python  
- TensorFlow / Keras  
- NLTK  
- NumPy, Pandas  
- Scikit-learn  
- Google Colab  

---

## How to Run
1. Open the notebook in Google Colab  
2. Upload or mount the dataset  
3. Run all cells in sequence  
4. Use the prediction function to test custom news input  

---

## Future Scope
- Experiment with transformer-based models like BERT  
- Deploy the model using Flask or Streamlit  
- Integrate real-time news data sources  

---

## Author
Mohit Saini  
B.Tech Textile Engineering, IIT Delhi
