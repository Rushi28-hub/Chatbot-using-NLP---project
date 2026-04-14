Project Title: Food Order Tracking Chatbot

Author: Rushikesh Gokul Tikhe

Description:
This project is an NLP-based chatbot that allows users to track their food orders using natural language.

Technologies Used:

* Python (FastAPI)
* MySQL
* Dialogflow (NLP)
* HTML/CSS
* ngrok

How to Run:

1. Install dependencies:
   pip install fastapi uvicorn mysql-connector-python

2. Run backend:
   uvicorn backend.main:app --reload

3. Start ngrok:
   ngrok http 8000

4. Configure Dialogflow webhook using ngrok URL

5. Open frontend/home.html

Features:

* Real-time order tracking
* NLP-based query handling
* Database integration
