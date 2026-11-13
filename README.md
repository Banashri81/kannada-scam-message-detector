# Kannada Scam and Fake Message Detector

An NLP-based project to identify fraudulent and legitimate messages written in Kannada, Kanglish and English.

## 1. About the Project

Digital communication through SMS, WhatsApp and online payment applications has increased exposure to fraudulent messages.

Many scam messages use regional languages and mixed-language text. This project aims to identify such messages using Natural Language Processing (NLP) and Machine Learning.

The system will classify messages into five categories and provide users with a predicted category and an explanation of suspicious patterns.

## 2. Project Objectives

- Collect Kannada, Kanglish and English message samples.
- Prepare and label a text classification dataset.
- Apply text preprocessing techniques.
- Train traditional machine learning models.
- Fine-tune multilingual transformer models.
- Compare model performance.
- Develop a web application for scam detection.

## 3. Classification Categories

| Category | Description |
|---|---|
| Legit | Normal and genuine messages |
| UPI_FRAUD | UPI and payment fraud messages |
| LOTTERY_SCAM | Fake lottery and prize messages |
| FAKE_JOB | Fraudulent job offers |
| PHISHING_KYC | Fake KYC and phishing messages |

## 4. Languages Supported

- Kannada script
- Kanglish (Kannada written using English letters)
- English

## 5. Technology Stack

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Pandas | Data handling |
| NumPy | Numerical operations |
| Scikit-learn | Machine learning |
| Hugging Face Transformers | Multilingual NLP |
| MuRIL / XLM-R | Transformer models |
| Google Colab | Model development |
| Streamlit | Web application |
| GitHub | Version control |

## 6. Project Workflow

1. Data collection
2. Data cleaning and preprocessing
3. Dataset labeling
4. Exploratory data analysis
5. Machine learning model training
6. Transformer fine-tuning
7. Model evaluation
8. Explainability
9. Application development
10. Testing and deployment

## 7. Repository Structure

```text
kannada-scam-message-detector/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
├── src/
├── app/
├── models/
├── README.md
└── .gitignore
```

## 8. Evaluation Metrics

- Accuracy
- Precision
- Recall
- Macro F1-score
- Confusion Matrix

Special attention will be given to scam detection recall and false-positive predictions.

## 9. Current Project Status

Project setup and initial planning.

## 10. Future Improvements

- Support additional Indian languages.
- Improve detection of new scam patterns.
- Add suspicious URL analysis.
- Improve explanations for predictions.
- Deploy the application online.

## 11. Privacy

Personal information such as phone numbers, OTPs, account numbers and names will be removed from collected messages. Private datasets will not be uploaded to the public repository.

## 12. Project Goal

Develop a multilingual NLP-based application to help users recognize potentially fraudulent messages before interacting with them.
