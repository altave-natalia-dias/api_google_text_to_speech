Google Text-to-Speech API for Python

This Python script utilizes the Google Text-to-Speech (gTTS) API to convert text into speech. It's a simple and powerful tool that allows you to incorporate text-to-speech functionality into your Python projects.
Prerequisites

Before using this script, make sure to install the required gTTS library by running the following command:

bash

pip install gTTS

Getting Started

    Clone the repository:

bash

git clone https://github.com/your_username/API_Google_Text_to_Speech.git
cd API_Google_Text_to_Speech

    Run the script with Python:

bash

python text_to_speech.py

Usage

The script currently converts a predefined text to speech in English. To customize the text or use a different language, modify the mytext and language variables in the script.

python

# The text that you want to convert to audio
mytext = 'Welcome to geeksforgeeks!'

# Language in which you want to convert
language = 'en'

Advanced Usage
Feature 1: Convert Custom Text to Speech

To convert a custom text to speech, use the convert_text_to_speech function in the script. Example:

python

custom_text = 'Hello, this is a custom text!'
convert_text_to_speech(custom_text)

Feature 2: Convert Text to Speech in a Different Language

To convert text to speech in a different language, modify the language variable or use the convert_text_to_speech function with a specified language. Example:

python

spanish_text = '¡Hola, este es un texto personalizado!'
convert_text_to_speech(spanish_text, language='es')

Feature 3: Play a Specific Audio File

To play a specific audio file, use the play_converted_audio function in the script. Example:

python

play_converted_audio("custom_output.mp3")

License

This project is licensed under the MIT License - see the LICENSE file for details.
Acknowledgments

    Thanks to the Google Text-to-Speech API for providing powerful text-to-speech capabilities.
    Inspiration for this project comes from the desire to make text-to-speech functionality accessible in Python projects.
