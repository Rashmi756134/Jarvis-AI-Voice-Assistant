# Jarvis - Personal Assistant

This project is a Python-based personal assistant (Jarvis) that allows you to perform various tasks through voice commands. The assistant uses the `speech_recognition` library to recognize commands, `pygame` for music playback, `win32com` for text-to-speech functionality, and opens websites and applications based on voice input.

## Features

- **Voice Interaction**: Interact with the assistant using voice commands.
- **Open Websites**: Open websites like YouTube, Wikipedia, LinkedIn, and Google through voice commands.
- **Play Music**: Play music from your local files.
- **Show Time**: Get the current time.
- **Open Applications**: Launch applications like Replit, Firefox, GitHub Desktop, and VS Code using voice commands.
- **Web Search**: Search the web using voice commands.

## Installation

To get started with this project, you need to have Python installed on your system along with the required libraries.

### 1. Install required libraries

Run the following command to install the required libraries:


```bash
  pip install -r requirements.txt
```

If you don't have a requirements.txt file, manually install the required libraries:
```bash
pip install pygame speechrecognition pyttsx3 pywin32
```

### 2. Set up dependencies

    pygame: Handles music playback.
    speech_recognition: Used to recognize speech commands.
    pyttsx3 (or win32com.client): Converts text to speech for interacting with the user.
    os: Used to open applications or files.
    webbrowser: Opens websites based on commands.

Make sure you have the necessary paths set up for applications you want to open using the assistant (e.g., Firefox, VS Code, etc.).
Usage

Once you have installed the required libraries, run the script:

python jarvis.py

The assistant will start listening for commands. You can give it commands like:

    "Open YouTube": Opens YouTube in your default web browser.
    "Open Wikipedia": Opens Wikipedia.
    "Open Google": Opens Google.
    "Open music": Plays a local MP3 file.
    "Stop music": Stops the currently playing music.
    "The time": Tells the current time.
    "Search for [query]": Searches the web for the given query.
    "Open [application]": Opens specified applications (e.g., Replit, Firefox, VS Code).

## Code Structure

    jarvis.py: Main script to run the assistant.
    requirements.txt: A list of dependencies required for the project.
    app_paths.py (optional): File to store application paths.

## Notes

    Ensure that your microphone and speakers are working correctly.
    This project is designed for Windows as it uses win32com.client for text-to-speech.
    You can modify the file paths for applications or music files based on your system.



### Explanation of the Sections:
- **Features**: Lists the capabilities of the voice assistant.
- **Installation**: Details how to set up the project, including cloning the repository and installing dependencies.
- **Usage**: Describes how to interact with the assistant after it's up and running.
- **Code Structure**: Provides a brief overview of the project structure and the main file involved.


