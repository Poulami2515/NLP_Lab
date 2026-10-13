
# NLP Lab

A collection of hands-on Jupyter notebooks for learning and experimenting with **Natural Language Processing (NLP)** using Python and transformer-based models.

This repository contains practical demonstrations covering NLP tasks such as Question Answering and Emotion Classification, including data preprocessing, model training, evaluation, and visualization.


## About

This repository contains Jupyter notebooks developed and used as part of the **Natural Language Processing (NLP) lab sessions at [Jio Institute](https://www.jioinstitute.edu.in/), Navi Mumbai, India**.

The notebooks are designed to provide hands-on experience with NLP techniques, transformer-based models, and practical applications such as Question Answering and Emotion Classification. They include exercises on data preprocessing, model fine-tuning, evaluation, and visualization.


## Notebooks

| Notebook | Topic | Description |
|----------|-------|-------------|
| [qa-class-demo 1.ipynb](./qa-class-demo%201.ipynb) | Question Answering | Extractive question answering using information from a given passage using BERT family of models. |
| [emotion.ipynb](./emotion.ipynb) | Emotion Classification | Fine-tuning DistilBERT for multi-class emotion classification using Hugging Face Transformers. |

## 1. Question Answering

**Notebook:** `qa-class-demo 1.ipynb`

This notebook demonstrates extractive Question Answering, where a model identifies an answer to a question from a given context.

### Topics Covered
- Understanding extractive question answering
- Processing questions and context passages 
- Applying NLP models (BERT family) to extract answers
- Examining model predictions

## 2. Emotion Classification

**Notebook:** `emotion.ipynb`

This notebook explores multi-class emotion classification using pretrained transformer models.

The objective is to classify text into six emotion categories:

- Sadness
- Joy
- Love
- Anger
- Fear
- Surprise

### Dataset

**Dataset:** [dair-ai/emotion](https://huggingface.co/datasets/dair-ai/emotion)

The dataset contains text samples annotated with emotion labels and includes training, validation, and test splits.

### Model

**Base Model:** [DistilBERT](https://huggingface.co/distilbert/distilbert-base-uncased)

DistilBERT is a lightweight transformer model used for text classification tasks.

### Topics Covered

1. Loading and exploring the emotion dataset
2. Understanding emotion labels and their distribution
3. Text visualization using word clouds
4. Tokenization with Hugging Face Transformers
5. Fine-tuning DistilBERT for emotion classification
6. Training using the Hugging Face Trainer API
7. Evaluating performance using Accuracy and Macro-F1
8. Visualizing classification results using confusion matrices
9. Analyzing predictions and misclassified examples
10. Experimenting with hyperparameters and alternative models

### Evaluation Metrics

The notebook demonstrates evaluation using:

- **Accuracy:** Percentage of correctly classified samples.
- **Macro-F1:** Average F1-score across all emotion classes.
- **Confusion Matrix:** Visualization of correct and incorrect predictions across emotion categories.

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Poulami2515/NLP_Lab.git
cd NLP_Lab
```

### 2. Install Dependencies

```bash
pip install jupyter torch transformers datasets evaluate accelerate scikit-learn numpy matplotlib wordcloud
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the desired notebook and execute the cells sequentially.

For the emotion classification notebook, a GPU is recommended for faster model fine-tuning.

## Technologies Used

- Python
- Jupyter Notebook
- PyTorch
- Hugging Face Transformers
- Hugging Face Datasets
- Scikit-learn
- NumPy
- Matplotlib
- WordCloud

## Learning Objectives

This repository aims to provide practical experience in:

- Understanding fundamental NLP tasks
- Working with pretrained language models
- Processing and analyzing textual datasets
- Fine-tuning transformer-based architectures
- Evaluating NLP models using standard metrics
- Interpreting classification predictions and errors

## References

- [Hugging Face Transformers](https://huggingface.co/docs/transformers)
- [Hugging Face Datasets](https://huggingface.co/docs/datasets)
- [DistilBERT](https://huggingface.co/distilbert/distilbert-base-uncased)
- [Emotion Dataset](https://huggingface.co/datasets/dair-ai/emotion)

## Note

These notebooks are intended for educational and experimental purposes. Some exercises require completing code sections or experimenting with different configurations.
