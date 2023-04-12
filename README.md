# Alexa_Clone
This is a simple voice assistant program that allows you to interact with your computer using voice commands. The voice assistant can perform tasks such as playing YouTube videos, fetching information from Wikipedia, providing jokes, and more.

# Prerequisites
To run the voice assistant, you will need the following:

Python 3.x installed on your computer
Required Python modules: speech_recognition, pyttsx3, pywhatkit, datetime, wikipedia, and pyjokes. You can install them using pip or any other Python package manager.

# Getting Started
1.Clone this repository or download the source code as a zip file and extract it to a directory of your choice.
2.Install the required Python modules using pip or any other Python package manager. 
For example:
    pip install speech_recognition pyttsx3 pywhatkit wikipedia pyjokes
3. Run the voice_assistant.py script using Python.
For example:
     python voice_assistant.py
4.The voice assistant will start listening for voice commands. Say "Alexa" to activate the voice assistant and then give your command. The voice assistant will respond accordingly based on the implemented commands.

# Commands
The voice assistant currently supports the following commands:

Play: You can say "play" followed by the name of a song or video, and the voice assistant will play it on YouTube using the 'pywhatkit' module.

Time: You can ask for the current time, and the voice assistant will provide the current time using the 'datetime' module.

Who the heck is: You can say "who the heck is" followed by the name of a person, and the voice assistant will fetch a summary of that person from Wikipedia using the 'wikipedia' module.

Date: You can ask for a date, and the voice assistant will respond with a funny comment.

Are you single: You can ask if the voice assistant is single, and it will respond with a funny comment.

Joke: You can ask for a joke, and the voice assistant will provide a random joke using the 'pyjokes' module

