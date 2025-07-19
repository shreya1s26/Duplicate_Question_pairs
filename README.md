# Duplicate_Question_Pairs Detection App
- Duplicate Question Pairs detection is a crucial task in various domains, including academia, content creation, and software development. This application leverages natural language processing (NLP) techniques and machine learning to determine whether two input sentences have same meaning or not. 

# Features
- User-Friendly Interface: Simple and intuitive UI built with Streamlit.
- Text Preprocessing: Comprehensive preprocessing including decontraction, punctuation removal, and normalization.
- Feature Engineering: Extracts multiple linguistic and token-based features to enhance model performance.
- Additional Feature: Incorporates custom features derived from dataset observations to improve accuracy.


# Feature Engineering
Extracted a combination of basic and advanced features:

- Basic Features: Length of sentences, number of words, common word count, and total unique words.
- Token Features: Similarity ratios based on common words, stop words, token positions, etc.
- Length Features: Differences in sentence lengths and longest common substring ratios.

# Model Training
- Vectorization: Used a pre-trained vectorizer to convert text data into numerical format.
- Classifier: Employed Random forest classifier trained on the extracted features for Duplicate Question Pairs detection .

# Integration and Deployment
- Streamlit Interface: Developed an interactive web interface for users to input sentences and receive whether two input sentences have same meaning or not.
- The pre-trained model was deployed on Hugging Face's model hub, allowing for easy access and sharing.
