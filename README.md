# Resume Analysis and Credibility Evaluation Using NLP

## Project Description

This project aims to develop a Python-based tool for processing and analyzing resumes to extract and evaluate key information using Natural Language Processing (NLP). The tool utilizes libraries such as PyMuPDF for PDF processing and python-docx for Word document processing. The core functionalities of the tool include named entity extraction, credibility evaluation based on the extracted entities, and providing a comprehensive analysis of the resume content.

## Features

### 1. Installation of Necessary Libraries

- Install the required libraries:
  - `PyMuPDF` for PDF text extraction.
  - `python-docx` for Word document text extraction.

### 2. File Reading and Text Extraction

- **Excel Files**: Read Excel files containing lists of universities and companies.
- **PDF Resumes**: Extract text from resumes provided in PDF format using `PyMuPDF`.
- **Word Resumes**: Extract text from resumes provided in Word (.docx) format using `python-docx`.

### 3. Named Entity Extraction

- Identify and extract named entities such as universities and companies from the resume text.

### 4. Resume Credibility Evaluation

- Implement a scoring system to assess the credibility of the resume based on the identified universities and companies.
  - **University Rankings**:
    - Top-ranked university (1-10): +3 points
    - Medium-ranked university (11-30): +2 points
    - Lower-ranked university (31+): +1 point
  - **Company Status**:
    - Fortune 500 company: +2 points
    - Recognized company (not Fortune 500): +1 point
- Limit the total credibility score to a maximum of 10 points.

### 5. Output the Results

- Display the extracted universities and companies from the resume.
- Print the credibility score along with an explanation of the rating scale.
