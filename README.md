# Hiring Chatbot

This project is a hiring assistant chatbot built using **Streamlit** and **Transformers**. The chatbot asks users a series of questions and validates their responses. Once the form is completed, the data is saved to a **Google Sheet**.

## Features

- **Interactive Chatbot**: The user interacts with the chatbot to answer a set of questions related to their personal and professional information.
- **Answer Validation**: The answers are validated based on predefined criteria for each question (e.g., age, gender, CGPA, skills, etc.).
- **Google Sheets Integration**: Once the form is completed, the user's answers are saved to a Google Sheets document for easy access and storage.
- **Text Classification**: The chatbot uses a pre-trained model (`dianapps-vaibhav/distilbert-hiring-intent`) to classify the validity of certain responses.
- **Retake Form**: Users can retake the form after completion if needed.

## Requirements

- Python 3.x
- Streamlit
- Huggingface `transformers` library
- Google Sheets API (`gspread`)
- OAuth2 credentials for Google Sheets

## Setup

1. **Install Required Libraries**:

   You can install all the required libraries using the following pip command:

   ```bash
   pip install streamlit transformers gspread oauth2client
