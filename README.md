# Sentiment Analysis Using Bidirectional LSTM (BiLSTM)

## Project Overview

This project implements **Sentiment Analysis** on IMDb movie reviews using a **Bidirectional Long Short-Term Memory (BiLSTM)** neural network. The model classifies movie reviews as **Positive** or **Negative** using deep learning techniques implemented in **TensorFlow/Keras**.

The project was developed and executed in **Google Colab** and demonstrates the complete Natural Language Processing (NLP) workflow, including data preprocessing, model training, evaluation, visualization, and prediction.

---

## Features

- IMDb Movie Reviews dataset
- Text preprocessing and sequence padding
- Tokenization using Keras Tokenizer
- Word Embedding layer
- Bidirectional LSTM architecture
- EarlyStopping and ReduceLROnPlateau callbacks
- Model evaluation using:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - Confusion Matrix
- Training & Validation Accuracy/Loss visualization
- Predict sentiment for custom user reviews
- Save and load trained model

---

## Dataset

**Dataset:** IMDb Movie Reviews Dataset

- Binary Sentiment Classification
- Positive Reviews
- Negative Reviews

The dataset is available through TensorFlow/Keras and is automatically downloaded during execution.

---

## Technologies Used

- Python
- Google Colab
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- NLTK
- WordCloud

---

## Model Architecture

```
Input Text
      │
      ▼
Text Preprocessing
      │
      ▼
Tokenization
      │
      ▼
Padding
      │
      ▼
Embedding Layer
      │
      ▼
Bidirectional LSTM
      │
      ▼
Dense Layer
      │
      ▼
Sigmoid Output
      │
      ▼
Positive / Negative
```

---

## Project Workflow

1. Import libraries
2. Load IMDb dataset
3. Preprocess text data
4. Tokenize reviews
5. Pad sequences
6. Build Bidirectional LSTM model
7. Train the model
8. Evaluate performance
9. Plot accuracy and loss curves
10. Generate confusion matrix
11. Predict sentiment for custom reviews

---

## Results

The model demonstrates strong performance on the IMDb sentiment classification task.

Evaluation includes:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- Classification Report

---

## Installation

Clone this repository:

```bash
git clone https://github.com/Shakti0812/Sentiment-Analysis-Using-BiLSTM.git
```

Move into the project directory:

```bash
cd Sentiment-Analysis-Using-BiLSTM
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Running the Project

Open the notebook:

```
Sentiment_Analysis_Using_BiLSTM.ipynb
```

Run all cells sequentially in:

- Google Colab
- Jupyter Notebook

---

## Repository Structure

```
Sentiment-Analysis-Using-BiLSTM/
│
├── Sentiment_Analysis_Using_BiLSTM.ipynb
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore
```

---

## Future Improvements

- GRU implementation
- Transformer-based models (BERT)
- Hyperparameter tuning
- Attention Mechanism
- Multi-class sentiment analysis
- Deployment using Streamlit or Flask

---

## Acknowledgements

- TensorFlow
- Keras
- IMDb Movie Review Dataset
- Google Colab

---

## Author

**SHAKTI AKASH K**

Machine Learning & Deep Learning Enthusiast

---

## License

This project is licensed under the MIT License.
