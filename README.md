# Career Navigator: AI-Driven Job Application Assistant

The Career Navigator is an AI-driven system developed to optimize the job application process by automating resume screening and providing intelligent job recommendations. This project leverages advanced machine learning models and natural language processing (NLP) techniques to streamline the matching of candidates to suitable job positions.

## Project Overview

The Career Navigator uses two distinct datasets to train and evaluate its algorithms, enhancing the precision of job categorization and recommendation based on resumes.

### Key Features

- **Automated Resume Screening**: Implements NLP techniques to process and analyze resumes, facilitating quick categorization.
- **Job Recommendation System**: Utilizes cosine similarity to suggest the top five most suitable job categories for applicants.
- **Resume & Job Description Match**: Shows how well the resume is matching with the job description.

## Technologies Used

- Python
- TensorFlow
- Keras
- Scikit-learn
- NLTK
- Pandas
- NumPy
- TfidfVectorizer
- Pickle

## Project Workflow

### 1. Data Collection and Preparation

- **Dataset Assembly**: Two datasets used; a smaller set with 962 entries and a larger one with 29,003 entries.
- **Data Cleaning**: Extensive text cleaning and preprocessing using NLP techniques such as tokenization, stopwords removal, and lemmatization.

### 2. Feature Engineering

- **Vectorization (TF-IDF)**: Converts text data into numerical values using TfidfVectorizer, highlighting the significance of words within documents.

### 3. Model Development and Training

- **Model Selection**: Utilizes a Recurrent Neural Network (RNN) and Multinomial Naive Bayes (MNB) for text classification.
- **Model Training**: Both models are trained on the TF-IDF transformed data, optimizing parameters for best performance.

### 4. Model Evaluation

- **Testing**: Rigorous testing is conducted to ensure accurate job categorization.
- **Accuracy Measurement**: Models are evaluated based on their accuracy, with a focus on scalability.

### 5. Application Development

- **Job Recommendation System**: Features a cosine similarity-based engine to align candidates with relevant jobs.

### 6. Deployment and Maintenance

- **Model Saving**: Utilizes Pickle for serialization and loading of trained models.
- **Continuous Improvement in Future**: Updates to models and methodologies to adapt to job market changes.

### 7. Documentation and Presentation

- Comprehensive documentation and final presentation detailing the project's methodologies, results, and impacts.
