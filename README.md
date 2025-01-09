Text Recognition and Translation System
A Flask-based web application that extracts text from images using Tesseract OCR and translates it into a target language using Google Translate API. This project supports multiple languages and offers a clean, dynamic interface for selecting the image's language and the target translation language.

Features
Extracts text from uploaded images using Tesseract OCR.
Translates the extracted text into a user-selected target language.
Supports a wide range of languages, dynamically generated for easy selection.
Simple and responsive web interface for user interactions.
Handles both printed and handwritten text (accuracy depends on Tesseract's configuration and input quality).
Technologies Used
Python: Core programming language for the backend.
Flask: Web framework to handle routing and serve the HTML interface.
Pillow: Library for image processing.
pytesseract: Wrapper for Tesseract OCR to extract text from images.
deep-translator: Library to translate text via Google Translate API.
HTML/CSS: For the frontend interface.
