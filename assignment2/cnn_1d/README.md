# 1D CNN for IMDB Sentiment Classification

## Model architecture
- Input: tokenized and padded review sequences
- Embedding layer (trainable)
- Conv1D with 128 filters and kernel size 5
- GlobalMaxPooling1D
- Dense layer with ReLU
- Dropout
- Output sigmoid layer

## Techniques applied
- text cleaning
- tokenization and padding
- 1D convolution for local phrase patterns
- dropout regularization
- early stopping
- evaluation with accuracy, precision, recall, F1, and ROC-AUC
