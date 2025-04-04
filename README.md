# Toxic-Classification-and-explanation
Our pipeline incorporates a blend of models and techniques to achieve accurate classification and explainability. For classification, we employed Logistic Regression using a OneVsRestClassifier for multi-label classification, which enabled us to handle the six toxicity categories effectively. Logistic Regression was chosen for its simplicity and interpretability, making it an excellent baseline model for the task. For explanation, we used LIME (Local Interpretable Model-Agnostic Explanations) to compute the importance of individual toxic words or phrases that contributed to the model's predictions. To generate human-readable explanations for the flagged toxic content, we leveraged BERT Summarization, which processed the extracted keywords to produce concise and meaningful summaries.

## Dataset - Jigsaw toxic comment classification
The dataset consists of large number of Wikipedia comments which have been labeled by human raters for toxic behavior. The types of toxicity are:
toxic, severe_toxic, obscene, threat, insult, identity_hate

## Model
Logistic Regression, Naive Bayes, LIME, BART

## Metrics
ROC_AUC: 0.9794  Accuracy: 0.9187



