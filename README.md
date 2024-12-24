# CloudyAI: Interactive AI-Powered Chatbot

CloudyAI is an AI-powered chatbot application designed to deliver an interactive user experience by integrating voice recognition, real-time image processing, and generative AI. Built with scalability and user-friendliness in mind, the application leverages the power of modern cloud technologies to handle diverse queries efficiently.

## Features

- **Interactive Chat Interface**: A real-time, responsive chat interface that supports voice and text interactions.
- **Generative AI Integration**: Powered by the Gemini API for intelligent and context-aware responses.
- **Voice Recognition**: Enables hands-free interaction using Google Speech Recognition.
- **Text-to-Speech (TTS)**: Responds audibly using a TTS engine for better accessibility.
- **Image Processing**: Analyzes and identifies objects or celebrities in user-uploaded images using AWS Rekognition.
- **Scalable Architecture**: Designed to handle multiple simultaneous users.
- **User-Friendly Design**: Built with HTML5, CSS3, and JavaScript for an intuitive UI.

## Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript
- **Backend**: Flask (Python)
- **Generative AI**: Gemini API for dynamic content generation
- **Image Processing**: AWS Rekognition for image recognition tasks
- **Voice Services**: pyttsx3 for TTS and Google Speech Recognition
- **Deployment**: Hosted on AWS EC2 running Ubuntu Linux
- **Optional**: MongoDB for storing chat logs and user interactions

## Prerequisites

Before running the application, ensure the following dependencies and prerequisites are in place:

- **Python 3.8 or above**
- **Node.js v12+ and NPM** (optional for frontend enhancements)
- **Gemini API Key** for generative AI integration
- **AWS Credentials** for Rekognition service access
- **Ubuntu Linux** with required packages installed

## Installation and Setup

Follow these steps to set up and run CloudyAI:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/cloudyai.git
   cd cloudyai
