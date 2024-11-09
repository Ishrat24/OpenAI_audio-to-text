# Project Description

This project is a Flask web application that allows users to upload an audio file for transcription and translation. The app uses OpenAI's Whisper model for transcribing the audio to text, and then GPT-4 is used to translate the transcribed text into the language specified by the user.

## Features:

- **Audio Upload**: Users can upload an audio file in any supported audio format.

- **Transcription**: The app automatically transcribes the audio file into English text using OpenAI's Whisper model.

- **Translation**: After transcription, the app translates the text into the desired language (such as French, Spanish, etc.) using OpenAI's GPT-4 model.

- **User Interface**: A simple and clean web interface for uploading files and specifying the target translation language.

## Tools and Technologies Used

### 🔧 Backend
  
- **Flask**: A lightweight web framework for Python, used to build the web server and handle HTTP requests.

- **OpenAI API**: Used to interact with the Whisper model for audio transcription and the GPT-4 model for text translation.

- **Python**: The primary programming language used for the backend logic.

- **os**: Used to interact with the system’s environment (for accessing the OpenAI API key and file paths).

### 🌐 Frontend

- **HTML/CSS**: Basic web technologies for building the structure and styling of the web page.

- **Responsive Design**: The design adapts to different screen sizes using CSS media queries.

## File Handling:

- **Flask's request.files**: Used for handling file uploads on the server.

- **File Storage**: The uploaded audio file is saved in the static folder on the server.

## Dependencies (to be installed via pip):

    pip install Flask

    pip install openai

`API_KEY`

## API Reference


```http
https://platform.openai.com/docs/overview
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `API_KEY` | `string` | **Required**. Your API key |

