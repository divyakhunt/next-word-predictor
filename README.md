# Next Word Predictor
This project contains a Google Colab notebook that implements a **Bidirectional LSTM** model using TensorFlow/Keras to predict the next word in a sentence. The model is trained on natural language data from **The Adventures of Sherlock Holmes**, obtained from Kaggle.

## Contents
- `next_word_pridictor.ipynb`: Colab notebook containing preprocessing, model building, training, and prediction code.

## How to Use
1. Open the notebook in Google Colab or Jupyter Notebook.
2. Upload the dataset (Sherlock Holmes text file) as instructed in the notebook.
3. Run all the cells to train the model and test predictions.

## Dataset
- **Source**: [Kaggle - The Adventures of Sherlock Holmes](https://www.kaggle.com/datasets)
- The dataset includes regular English sentences suitable for language modeling tasks.

## Model Details
- **Bidirectional LSTM** layers for sequential prediction
- **Tokenizer** used for vocabulary generation and text-to-sequence conversion
- Categorical crossentropy loss and Adam optimizer

## Future Improvements
- Add beam search or top-k sampling for better predictions
- Train on larger and more diverse corpora
