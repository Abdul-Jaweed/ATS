# Resume Matcher

![Project Logo](logo.png)

## Overview

The Resume Matcher is a Python-based project designed to match job descriptions with candidate resumes using natural language processing techniques. This tool aids in identifying the most suitable candidates for specific job roles by calculating the similarity between job descriptions and candidate resumes.

The project is divided into four main steps:

1. **Data Collection:**
   - Extract resume keywords using PyPDF2 and SpaCy libraries.
   - Fetch job description data from HuggingFace dataset library.

2. **Text Preprocessing and Tokenization:**
   - Preprocess and tokenize both resumes and job descriptions.
   - Ensure consistent text formatting and language handling.

3. **Word Embedding Extraction:**
   - Generate word embeddings for both resumes and job descriptions.
   - Utilize advanced models like DistilBERT for embeddings.

4. **Resume Matching:**
   - Calculate cosine similarity between job descriptions and resumes.
   - Rank CVs based on similarity scores and list the top candidates.

## Getting Started

Follow these steps to get started with the Resume Matcher:

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/Abdul-Jaweed/Resume-Matcher.git
   cd resume-matcher
