# Detecting AI-Generated Text in Political Articles Using NLP and Pretrained Models
This project explores automated methods to distinguish between human-written and AI-generated political articles, with a focus on Wikipedia-style content. Two classification workflows are implemented and compared:

TF-IDF + Logistic Regression: Utilizes classic lexical feature extraction for high-accuracy, dataset-specific detection.

Sentence Transformers + Logistic Regression: Applies pretrained semantic embeddings for more robust, generalizable AI-text detection.

The project includes a balanced dataset of human- and AI-authored political articles, comprehensive preprocessing, and both traditional and transformer-based machine learning pipelines. Performance evaluation demonstrates the strengths and trade-offs between surface-level (TF-IDF) and contextual (Sentence Transformers) approaches, highlighting practical challenges such as overfitting and generalizability.

Key Features:

1. End-to-end code for data processing, feature extraction, modeling, and evaluation

2. Analysis and visualizations of model performance, error cases, and robustness considerations

3. Recommendations for future development in AI-text detection tasks

Author: Sutharshan Shanmugarajah
