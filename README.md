# Smart Assistant

A voice-enabled AI assistant that integrates with ChatGPT and provides text-to-speech capabilities using Lovo.

## Features

- Speech Recognition: Convert your voice to text
- Text-to-Speech: Get natural-sounding voice responses using Lovo
- ChatGPT Integration: Access the power of ChatGPT through voice or text
- Customizable Settings: Personalize your experience with adjustable voice settings

## Prerequisites

- Python 3.8 or higher
- Lovo API key
- OpenAI API key
- Microphone for speech recognition

## Installation

1. Clone the repository:
```
git clone https://github.com/yourusername/smart-assistant.git
cd smart-assistant
```

2. Create a virtual environment and activate it:
```
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install the required packages:
```
pip install -r requirements.txt
```

4. Set up environment variables:
   - Copy the `.env.example` file to `.env`
   - Fill in your API keys and credentials

## Configuration

1. Set up your Lovo API key:
   - Create an account at [Lovo](https://lovo.ai/)
   - Get your API key from the dashboard
   - Add it to the `.env` file

2. Set up your OpenAI API key:
   - Get an API key from [OpenAI](https://platform.openai.com/)
   - Add it to the `.env` file

## Usage

1. Start the application:
```
python run.py
```

2. Open your browser and navigate to `http://localhost:5001`

3. Register a new account or log in with existing credentials

4. Use the dashboard to interact with the assistant:
   - Click the microphone button to start speech recognition
   - Type messages in the text input field
   - Adjust voice settings in the settings panel

## Troubleshooting

- If you encounter issues with speech recognition, make sure your microphone is properly connected and configured
- For text-to-speech issues, verify your Lovo API key
- If ChatGPT integration is not working, check your OpenAI API key
- If port 5001 is already in use, you can modify the port in run.py

## License

This project is licensed under the MIT License - see the LICENSE file for details. 
