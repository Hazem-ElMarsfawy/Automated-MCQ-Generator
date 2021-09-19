# Automated-MCQ-Generator

Natural language Processing System, that takes a document as an input then applies NLP Techniques to generate a list of possible Questions and related possible distractors (choices).
Implemented as a Web Application in Flask Python.

NLP libraries like Spacy and NLTK are used for implementing Tokenization, Stemming, TF-IDF, Keywords Extractions.
Simple Sentence Patterns are implementing to generate WH Questions, Yes or No Questions, and Filling the space Questions.
Distractors are produced and chosen according to Similarity Functions using generic online ontology "WordNet".
