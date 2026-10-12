# School FAQ Chatbot

## Overview
A chatbot that answers frequently asked questions about my school.

## Features
- Answers questions about admissions, programs, schedules and procedures
- Finds the most relevant answer to the user's question
- Fallback message when the question is not understood

## How it works
1. FAQ content is collected and stored as question-answer pairs
2. User input is cleaned (lowercasing, punctuation and stop words removal)
3. Questions are vectorized with TF-IDF
4. Cosine similarity finds the closest FAQ question
5. The matching answer is returned

## Tech stack
Python, scikit-learn, NLTK

## How to run
1. Clone the repository
2. Install dependencies: pip install -r requirements.txt
3. Run: python app.py

## Possible improvements
- Add more FAQ entries
- Support French, English and Arabic
- Add a web interface
- Use a language model for more natural answers

## Author
Ayate Ndiaye - AI student
