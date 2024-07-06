# ChatBot-using-Gemini-Api

Tele Health with GeminiChat
============================

This Streamlit application integrates a chatbot powered by Gemini-1.5-flash from Google's Generative AI API. The chatbot is designed to assist users with telehealth inquiries.

Prerequisites
-------------

Before running the application, ensure you have the following set up:
- Python Environment: Python 3.x installed on your system.
- Streamlit: Install Streamlit using `pip install streamlit`.
- Google Generative AI API: Obtain an API key from Google and configure it in the application (`genai.configure(api_key="Your-Api_Key")`).

How to Run
----------

1. Clone this repository to your local machine:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   
2.Install dependencies:
  pip install -r requirements.txt

3.Configure API Key:
  Replace "Your-Api_Key" in genai.configure(api_key="Your-Api_Key") with your actual API key.

4.Run the Streamlit application:
  streamlit run main.py

# Interact with the chatbot:

Type your messages in the input box provided.
To end the chat, type 'exit' or 'quit'.

Application Structure :
main.py: Contains the Streamlit application code.

-Initializes the chatbot model and sets up the chat interface.
-Sends user inputs to the chatbot and displays responses.
-Allows termination of the chat session upon user request.
-requirements.txt: Lists the Python dependencies required to run the application.

# Configuration
Google Generative AI API:
Ensure your API key is securely stored and replaced appropriately in the code.

# Notes
This application demonstrates a basic chat interface using Streamlit and Google's Generative AI API.
Customize the generation_config and initial chat history (start_chat() function) based on your specific requirements.
