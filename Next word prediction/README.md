# Next Word Prediction Using Deep Learning

## 🎯 Overview
This project implements a next-word prediction model using deep learning techniques, specifically utilizing Bidirectional Long Short-Term Memory (BiLSTM) networks. The model predicts the most likely next word in a sequence, enhancing applications like text completion and predictive typing.

## 🧠 Objectives
- Build a predictive model that suggests the next word based on a given sequence.
- Utilize BiLSTM to capture context from both past and future words.
- Evaluate model performance using perplexity and accuracy metrics.

## 🛠️ Tools & Technologies
- Python
- TensorFlow/Keras
- NumPy
- Pandas
- Jupyter Notebook

## 📁 Dataset
- **Source:** [Text Corpus from Project Repository](https://github.com/Tejashri-Bhilare/Data-Science-Projects/tree/main/Next%20word%20prediction)
- **Features:** Tokenized text sequences from a large text corpus.

## 🔍 Model Architecture
1. **Data Preprocessing:** Tokenization and padding of text sequences.
2. **Model Design:** BiLSTM layers followed by Dense layers with softmax activation.
3. **Compilation:** Adam optimizer with categorical crossentropy loss function.
4. **Training:** Model trained over multiple epochs with validation.

## 📈 Performance Metrics
- **Perplexity:** Measures the model's uncertainty in predicting the next word.
- **Accuracy:** Percentage of correct predictions over the total predictions.

## 📌 Future Enhancements
- Implement Transformer-based models like GPT for improved performance.
- Fine-tune the model with domain-specific corpora.
- Develop a user interface for real-time word prediction.

