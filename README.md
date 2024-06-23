# AvatarSpeak-AI-Driven-Text-to-Avatar-Speech-Generator
Project Overview:
This project is a comprehensive application that takes user input text, generates a response using a language model, converts the generated text to speech, and creates a lipsync video of an avatar speaking the response.

Features
1. Text Generation: Uses the Qwen language model to generate a response based on user input.
2. Text-to-Speech: Converts the generated text to speech using the SpeechT5 model from Microsoft.
3. Lipsync Video Generation: Creates a video of an avatar speaking the generated text by synchronizing mouth movements with the speech.
Main Functions:
1. generate_response:
    . Generates a response from the language model.
    . Converts the response text to speech.
    . Generates a lipsync video of the avatar speaking the response.
2. text_to_speech:
    . Converts text to speech using gTTS.
3. avtar:
    . Creates a lipsync video of an avatar based on the provided audio.
Gradio Interface:
The project uses Gradio to provide a user-friendly web interface where users can enter text and receive a spoken response from the avatar.
Dependencies
You need to install the following dependencies:
You can install all dependencies using the following combined command:
pip install accelerate aspose-words transformers --upgrade einops torch soundfile
