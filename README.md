# Railway Chat Bot App

Welcome to the Railway Chat Bot App, a powerful tool for audio-based railway inquiries and information retrieval. This application is designed to seamlessly interact with users through audio input, extracting their questions, providing text-based responses, and even generating text-to-speech audio files in the user's preferred language.

## Overview

This project leverages cutting-edge technologies to deliver a comprehensive railway chatbot experience:

- **Query Handling**: We utilize the OpenAI langchain for intelligent query handling, ensuring accurate understanding of user questions.

- **Audio Transcription**: Whisper AI powers our audio transcription, converting spoken words into text for processing.

- **Text Translation**: M2M100 facilitates text translation, allowing us to respond to queries in multiple languages.

## Architecture

Here's a simplified flowchart diagram to illustrate the inner workings of our Railway Chat Bot App:

![Flowchart Diagram](webappp/static/WhatsApp%20Image%202023-09-26%20at%2012.03.24%20AM.jpeg)

## Components

### Frontend

Our frontend is built using a React app, providing an intuitive and user-friendly interface for interacting with the chatbot.

### Backend

The backend of this application is implemented as a Flask API, responsible for handling user queries, processing audio, and generating responses. Please note the following changes required to set up the backend:

1. **Database**: This repository does not contain the JSON database file. You will need to download it separately and store it in the `static` folder. Ensure that the database is configured correctly.

2. **Backend Customization**: Since our code has been removed from the Flask backend (`main.py`), you have the flexibility to tailor it to your specific requirements. Customize the backend logic to align with your desired functionality.

## About the Developers
Hi, I am Rupesh. I have developed this project along with my friend Suvam Kumar Verma. We both are students pursuing education in Artificial Intelligence and Data Science. 

---

Feel free to explore and don't hesitate to contact Rupesh Suryawanshi for any inquiries or collaboration opportunities.

