# 🗣️ English–Hindi Neural Machine Translation

This project demonstrates an end-to-end English-to-Hindi translation system using neural networks. It compares two popular sequence-to-sequence (seq2seq) architectures: LSTM and CNN-based models.

## 💡 Project Overview

- **Goal:** Translate English sentences to Hindi automatically
- **Dataset:** 83,000+ pairs of English and Hindi sentences
- **Models:** LSTM and CNN-based encoder–decoder networks
- **Result:** The CNN-based model achieved better translation accuracy than LSTM on our data

---

## 🗂️ Dataset

The dataset used is a parallel corpus where each line contains an English sentence and its Hindi translation, separated by a tab (`\t`).


---

## ⚙️ How it Works

1. **Preprocessing & Tokenization**
   - Sentences are cleaned, lowercased, and tokenized
   - Special start (`\t`) and end (`\n`) tokens are added to help the decoder know when to start and stop

2. **Model Architectures**
   - **LSTM-based Model:** Uses traditional RNN-based sequence learning with memory cells
   - **CNN-based Model:** Uses convolutional layers to extract sentence-level features and generate translations

3. **Training**
   - Trained on over 83,000 English–Hindi sentence pairs
   - Compared model performance on sample test translations

4. **Evaluation**
   - CNN model produced more accurate and fluent Hindi sentences in our tests

---

## 📈 Results

| Model | Performance                          |
|---------|--------------------------------------|
| LSTM    | Good, but less fluent translations |
| CNN     | Better sentence-level accuracy and smoother outputs |

---

## 💬 Example Translations

| English | Hindi  |
|-----------|--------|
| Jump.    | उछलो. |
| Help!    | बचाओ! |

---


