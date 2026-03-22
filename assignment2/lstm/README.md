# LSTM for IMDB Sentiment Classification

## Model architecture
- Input: tokenized and padded review sequences
- Embedding layer (trainable)
- LSTM layer with 64 units
- Dense layer with ReLU activation
- Dropout regularization
- Output sigmoid layer

## Techniques applied
- text cleaning
- tokenization and padding
- recurrent neural network (LSTM)
- dropout regularization
- early stopping
- evaluation with accuracy, precision, recall, F1, and ROC-AUC
