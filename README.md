# ATS Tracking System

This is a Streamlit web application designed to track and analyze resumes using Google's Generative AI.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/<usuario>/<nombre-del-repositorio>.git
cd <nombre-del-repositorio>

```
2. Install the required dependencies:
```bash
pip install -r requirements.txt
```
3. Set up environment variables:

Create a .env file in the root directory of the project.
Add your Google API key to the .env file:

```bash
GOOGLE_API_KEY=<your_google_api_key>
```

## Usage
4. Run the Streamlit app:
```bash
streamlit run app.py
```
5. Access the application via the provided URL.

## Application Features

-Upload Resume: Users can upload their resumes in PDF format.

-Job Description Input: Users can input the job description.

-Resume Analysis: The app provides analysis of the resume based on the job description.

-Percentage Match: Users can assess the percentage match of the resume with the job description.

## Dependencies

Streamlit

PIL

pdf2image

Google Generative AI

## Acknowledgements
This application utilizes Google's Generative AI for content generation and follows the recommendations of @krishnaik06.