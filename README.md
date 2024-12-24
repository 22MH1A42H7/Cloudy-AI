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
2. **Set Up a Python Virtual Environment**
   - Create and activate a virtual environment:
     ```bash
     python3 -m venv venv
     source venv/bin/activate
     ```
   - Install the required Python packages:
     ```bash
     pip install -r requirements.txt
     ```

3. **Install Node.js (Optional for Frontend)**
   - Install Node.js and NPM if needed for additional frontend enhancements:
     ```bash
     sudo apt update
     sudo apt install nodejs npm
     ```

4. **Configure Environment Variables**
   - Replace placeholders in `app.py` with your credentials:
     - **Gemini API Key**: Replace `HERE` in the `genai.configure(api_key="HERE")` line with your actual API key.
     - **AWS Credentials**: Replace `aws_access_key_id` and `aws_secret_access_key` placeholders with your AWS access credentials.

5. **Run the Flask Application**
   - Start the server:
     ```bash
     flask run --host=0.0.0.0 --port=5000
     ```

6. **Access the Application**
   - Open your browser and navigate to:
     ```
     http://<EC2-public-IP>:5000
     ```

## Future Enhancements

- **Database Integration**: Integrate MongoDB for logging user interactions and chat history.
- **Advanced User Authentication**: Add secure user authentication and role-based access control.
- **Image Features Expansion**: Incorporate additional image recognition features such as object tracking or facial emotion analysis.
- **Containerization**: Dockerize the application for improved portability and easier deployment.
- **CI/CD Pipeline**: Implement continuous integration and deployment using GitHub Actions or AWS CodePipeline.
- **Multi-Language Support**: Extend chatbot capabilities to support multiple languages.

## Author

**[Your Name]**  
Cloud and AI Enthusiast | Software Developer  
- **LinkedIn**: [https://www.linkedin.com/in/Satya Praveen M](https://www.linkedin.com/in/satya-praveen-m-36442725b/)  
- **GitHub**: [https://github.com/Satya Praveen M](https://github.com/22MH1A42H7)  

---

Thank you for exploring **CloudyAI**! If you have suggestions or would like to contribute, feel free to create an issue or submit a pull request.
