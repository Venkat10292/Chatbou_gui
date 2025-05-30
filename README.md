# AI Chatbot with GUI

This project is an AI-powered chatbot built using Python that uses Natural Language Processing (NLP) to interact with users through a graphical user interface (GUI). It was developed as my final year undergraduate project.

## Project Overview

The aim of this project is to create a simple, rule-based chatbot capable of responding to user queries based on predefined intents. It is implemented using Python, NLTK for natural language processing, TensorFlow/Keras for training a neural network model, and Tkinter for building the GUI.

The chatbot can understand basic conversational language and provide responses from a structured dataset (`intents.json`). It showcases how NLP and deep learning models can be integrated into a user-friendly desktop application.

## Technologies Used

- Python 3
- TensorFlow & Keras
- NLTK (Natural Language Toolkit)
- Tkinter (for GUI)
- JSON (for intent mapping)
- Pickle (for storing processed data)

## Features

- Intent-based classification using deep learning
- Real-time response generation from a trained model
- Simple and interactive desktop GUI
- Preprocessing pipeline with tokenization, stemming, and bag-of-words model

## How to Run

 1. Install required libraries:
   ```bash
   pip install nltk tensorflow

 2. Download NLTK data (run once):

  import nltk
  nltk.download('punkt')
  
 3. Train the model (if not already trained):

  python train_chatbot.py

  4. Launch the GUI:
 
  python chatgui.py
