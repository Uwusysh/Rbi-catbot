# Rbi-catbot
A chatbot that gives answer from master circular, web and Guidance Note on Audit of Banks  (2025 Edition). This project sets up a FastAPI backend that allows you to ask questions related to RBI banking policies, pulls relevant web links using Google Search and guidelines. It uses vector database Chroma DB and LLM model Llama-3 through groq to generate  relevant answers.

This is a full-stack chatbot project.

The backend is in the backend folder (app.py, requirements.txt)

The frontend is in the frontend folder (React app)

To run the project:

Go to the backend folder

Set up a virtual environment

Install packages using requirements.txt

Run app.py

Go to the frontend folder

Run npm install

Then npm start

If your chatbot needs custom data, make sure to place your files in a /data folder and update the code to load from it.
