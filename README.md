#  Resume Matcher AI

This is a Streamlit app that matches candidate resumes to a job description using AI-powered semantic search.

## What it does

- Takes a job description as input
- Compares it to candidate resumes
- Ranks candidates by similarity score
- Lets you filter and view top matches


cd resume-matcher-app
Install requirements

pip install -r requirements.txt


streamlit run app.py

# Built With
Streamlit
Pandas
NumPy

Sentence Transformers (all-MiniLM-L6-v2)

# Requirements
Create a requirements.txt file with:

streamlit
pandas
numpy
sentence-transformers
