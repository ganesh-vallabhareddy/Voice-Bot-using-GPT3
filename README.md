# Conversational AI

# Voice Bot using GPT-3 API

This project is a voice bot that utilizes the GPT-3 API by OpenAI to provide conversational responses. The bot listens to user input through a microphone, converts speech to text using the Google Speech Recognition API, generates a response using GPT-3, and converts the response back to speech using the pyttsx3 library.

## Prerequisites

Before running the voice bot, make sure you have the following installed:

- Python 3
- openai (Install using `pip install openai`)
- pyttsx3 (Install using `pip install pyttsx3`)
- speech_recognition (Install using `pip install SpeechRecognition`)

## Getting Started

1. Clone the repository or download the project files from [GitHub](https://github.com/your-username/voice-bot).

2. Obtain an API key for GPT-3 from OpenAI. If you don't have an API key, you can sign up for access on the OpenAI website.

3. Create a new file called `api_secrets.py` in the project directory.

4. In the `api_secrets.py` file, add the following line and replace `'YOUR_API_KEY'` with your actual GPT-3 API key:

 'API_KEY = "YOUR_API_KEY"'


5. Run the `voicebot.py` script using the following command:

 'python voicebot.py'


6. The voice bot will start listening for your voice input. Start speaking, and the bot will respond accordingly.

## Customization

- You can modify the `user_name` and `bot_name` variables in `voicebot.py` to change the names used in the conversation.

- Adjust the `engine` variable in `voicebot.py` to customize the text-to-speech engine settings.

- Experiment with different GPT-3 models by changing the `engine` parameter in the `openai.Completion.create` method.

## Acknowledgments

- The GPT-3 API by OpenAI
- pyttsx3 library for text-to-speech conversion
- speech_recognition library for speech recognition


