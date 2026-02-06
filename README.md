# Document Classification System Using Bag-of-Words
[📄 View Source on GitHub](https://github.com/Awinmaw/Document_Classification/blob/main/DC.ipynb) | [💻 Run on Colab](https://colab.research.google.com/github/Awinmaw/Document_Classification/blob/main/DC.ipynb)

## Abstract
Document classification is an important task in Natural Language Processing (NLP) that involves automatically assigning categories to text documents. With the rapid growth of digital text data, manual document organization has become inefficient and time-consuming. This project proposes a machine learning–based document classification system that automatically categorizes text documents using supervised learning techniques.

The system applies text preprocessing and feature extraction using the Bag-of-Words (BoW) model and employs a Multinomial Naive Bayes classifier to predict document categories. A user-friendly interface is developed using Gradio to allow real-time document classification and result visualization.

---

## Objectives
- To design and implement an automatic document classification system
- To apply NLP preprocessing techniques to textual data
- To use supervised machine learning for text categorization
- To provide an interactive interface for testing document classification
- To demonstrate practical application of NLP concepts for academic purposes

---

## System Overview
The document classification system takes a text document as input and predicts its category based on learned patterns from labeled training data. The system also displays prediction confidence and important keywords to improve interpretability.

---

## Methodology

### 1. Text Preprocessing
- Conversion of text to lowercase
- Removal of punctuation and special characters
- Tokenization
- Stop-word removal

### 2. Feature Extraction
- Bag-of-Words (BoW) model is used to convert text into numerical feature vectors

### 3. Classification Model
- Multinomial Naive Bayes
- Supervised learning approach

### 4. User Interface
- Built using Gradio
- Allows users to input text and view classification results instantly

---

## Dataset Description

The dataset used in this project consists of labeled text documents categorized into predefined classes such as **Technology**, **Business**, **Health**, **Education**, **Sports**, and others.

Each data sample contains:
- **Text:** The content of the document
- **Label:** The category assigned to the document

### Dataset Characteristics
- Type: Text-based dataset
- Labels: Multiple predefined categories
- Format: CSV / text format
- Usage:
  - Training the classification model
  - Testing and evaluating model performance

The dataset is split into training and testing sets to evaluate the effectiveness of the classification model.

---

## Model Details
- **Feature Extraction:** Bag-of-Words
- **Classifier:** Multinomial Naive Bayes
- **Learning Type:** Supervised Machine Learning
- **Interface:** Gradio

---

## Features
- Automatic document categorization
- Confidence score for predictions
- Important keyword extraction
- Simple and interactive user interface
- Real-time classification results

---

## Applications
- News and article classification
- Academic document organization
- Text analysis systems
- Content management systems

---

## Conclusion
This project successfully demonstrates the implementation of a document classification system using NLP and machine learning techniques. The results show that the Multinomial Naive Bayes classifier performs effectively for text categorization tasks. The project provides a strong foundation for further research and improvements using advanced models such as deep learning.

---

## Future Work
- Integration of TF-IDF and word embeddings
- Use of deep learning models such as LSTM or BERT
- Expansion of dataset size and categories
- Deployment as a web or mobile application


## Screenshot
### Sample technology document
![home page](doc_classification.png)
