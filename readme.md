# Verta AI
Verta is a chatbot using ***Google's Vertex AI*** connected to ***PaLM 2***.

This chatbot is not connected to the internet, so it might generate some hallucinated answers. It is the user's role to verify that the answer provided is correct.

## Features
- Displays side-by-side columns with an image on the left and the chat on the right.
- Begins the conversation with a prompt for the user to ask a question.
- Responds to user input using Judini's AI model.
- Simulates typing by incrementally displaying the assistant’s response text.
- Environment Variables
- The .env file needs to have the following environment variables:

    - 'JUDINI_API_KEY'
    - 'JUDINI_AGENT_ID'

## Installation & Running
- Make sure Python 3.8+ is installed.
- Clone the repo.
- Inside the repo, install the requirements using pip: `pip install -r requirements.txt`
- Run this command to start the Streamlit app `streamlit run app.py`

## Dependencies
- Streamlit
- Requests
- Dotenv
- PIL

## Contributions
Feel free to submit issues or PRs if you find any problems or improvements. 