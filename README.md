## version
- nodejs : 18.18.0
- npm :- 10.2.5

# ChatGPT Web Application
A web application that allows users to interact with OpenAI's GPT-3 language model through a simple and user-friendly interface.
This app is for demo purpose to test OpenAI API and may contain issues/bugs.

## Features
- User-friendly interface for making requests to the OpenAI API
- Responses are displayed in a chat-like format
- Select Models (Davinci, Codex, Create Image) based on your needs
- Highlight code syntax

## Technologies Used
- For client, I used React.js.
- For server, I used express.

## Setup Introduction
This guide will help you set up the repository on your local machine. Please follow these steps carefully to ensure a smooth setup process.
```

### Backend Setup
 
- Navigate to server directory
```sh
cd server # Navigate to the server directory:
```
- Install dependencies
```sh
npm install #install the backend dependencies
```
- Set the OPENAI_API_KEY in the .env file:
```sh
OPENAI_API_KEY=YOUR_OPENAI_API_KEY
```

- Start the backend server by running the following command:
```sh
node indx.js
```
