# Google Play Medium Reviews Dataset Classification with BERT Tokenizer
This project uses the BERT tokenizer to classify the category of user reviews from the Google Play Medium Reviews dataset. The dataset contains reviews from various categories, such as books, business, education, entertainment, and more.

BERT is an open source machine learning framework for natural language processing (NLP). BERT is designed to help computers understand the meaning of ambiguous language in text by using surrounding text to establish context.

Installation
To use this project, you will need to install the following dependencies:

Python 3.x
PyTorch
Transformers
You can install the dependencies by running the following command:
!pip install torch transformers

# Usage
To use the project, you can follow these steps:

1.  Clone the repository:
    git clone https://github.com/and.lauwira/BERT-text-tokenizer-for-NLP-Natural-Language-Preprocess.git

2.  Download the Google Play Medium Reviews dataset:
    https://www.kaggle.com/datasets/raqhea/medium-app-reviews-from-google-play-store

# Contributing
If you would like to contribute to the project, you can follow these steps:
1.  Fork the repository.
2.  Create a new branch for your feature or bug fix.
3.  Make your changes.
4.  Submit a pull request.

# Result
In this case i will use BERT to do a prediction from a user review and predict which category of content is the review is. im using pretrained BERT model (bert-base-cased). this model have is evaluated using several evaluation matrix:
Precision:  0.825
Recall:  0.747
F1-Score:  0.769
Accuracy:  0.841
