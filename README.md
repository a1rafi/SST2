## Integrating Encryption with NLP Pipelines

### Overview

The work focuses on integrating encryption techniques with Natural Language Processing (NLP) pipelines to ensure both data privacy and efficient text analysis.

The motivation comes from the growing need to handle sensitive text data (e.g., medical, financial, and personal communication) while still being able to apply NLP tasks such as classification, sentiment analysis, and information retrieval.

Here, we preprocessed and evaluated encrypted texts step by step. We examined encrypted texts in a Word Embeddings (Word2Vec) embedding environment and used the generated embedding data in neural network models.

### Methodology

* Preprocessed and evaluated encrypted text data step by step.

* Applied custom bi-substitution-based encryption to textual data.

* Represented encrypted text using Word2Vec embeddings.

* Trained deep learning models (LSTM and GRU) on the encrypted embeddings for classification.

### Results

LSTM model accuracy: 83.47% (encrypted input).

GRU model accuracy: 86.15% (encrypted input).

Demonstrated that encrypted pipelines can achieve competitive results with modest performance trade-offs.

### Tech Stack

Python

TensorFlow / Keras

Scikit-learn

Gensim (Word2Vec)

NumPy, Pandas, Matplotlib
