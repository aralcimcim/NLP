# Natural Language Processing

Group coursework exploring text representations and document classification, from bag-of-words features to pretrained embeddings and BERT.

The notebooks combine implementations, experiments, and written analysis using a course-provided subset of the HumSet humanitarian text dataset.

## Contents

| Notebook | Focus |
|---|---|
| [Assignment 1](Assignment1.ipynb) | Bag-of-words document representations, dimensionality reduction, and classification |
| [Assignment 2](Assignment2.ipynb) | Pretrained word embeddings, cosine and dot-product similarity, and nearest-neighbor retrieval |
| [Assignment 3](Assignment3.ipynb) | Document classification with PyTorch, GloVe embeddings, and a pretrained BERT model |

## Topics

- Text preprocessing and vocabulary construction.
- Comparing document and word representations.
- Vectorized similarity calculations and nearest-neighbor search.
- Neural classification with averaged word embeddings.
- BERT-based document classification.
- Training, validation, early stopping, and test evaluation.
- Experiment logging with TensorBoard.

Assignment 2 includes implemented word-similarity and nearest-neighbor exercises. Its document-classification and optional sent2vec sections remain as task descriptions.

## Dataset

The classification assignments use a subset of **HumSet**, containing text excerpts from humanitarian news and reports. Labels represent humanitarian sectors such as agriculture, health, and protection.

Pretrained embeddings and model downloads are also required for the relevant experiments.

## Tools

Python, Jupyter, NumPy, pandas, scikit-learn, Gensim, PyTorch, Hugging Face Transformers, Matplotlib, and TensorBoard.

Before execution:

1. Obtain the required dataset and pretrained embeddings.
2. Update local file paths in the notebook.
3. Check package compatibility with the original notebook environment.

## Authors

- Aral Cimcim
- Stefanie Alice Hofer
