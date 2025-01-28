Voice-Assisted AI Keylogger with Speech Recognition
A Python-based program that integrates a voice assistant, keylogger, and AI-powered natural language processing. This project listens for keyboard patterns, responds to voice commands, and generates intelligent responses using the AI21 Labs API.

🚀 Features
1.Keylogger: Captures keyboard input to trigger specific actions.
2.Voice Assistant: Uses speech recognition and text-to-speech for interaction.
3.AI Text Generation: Generates context-aware responses using AI21 Labs API.
4.Real-time Speech Recognition: Converts spoken words into text.
5.Audible Responses: Speaks responses for a seamless user experience.

🛠️ Installation
Clone this repository:
git clone  https://github.com/loga077/voice-ai-keylogger.git
cd voice-ai-keylogger
 
Install the dependencies:
pip install pynput pyttsx3 SpeechRecognition ai21

Replace the placeholder API key with your own from AI21 Labs:
client = AI21Client(api_key="your_api_key_here")+2

📋 Usage
1.Run the script:
python script_name.py
2.Trigger the assistant by pressing the space bar 10 times consecutively.
3.Speak your query into the microphone when prompted.
4.The assistant will:
  # Recognize your voice input.
  # Generate a response using the AI21 Labs API.
  # Speak the response audibly and repeat it for clarity.

  ⚙️ Requirements
1.Python 3.8 or later
2.Internet connection
3.Microphone (for speech recognition)

Python Libraries:
1.pynput: For capturing keyboard input.
2.pyttsx3: For converting text to speech.
3.SpeechRecognition: For converting speech to text.
4.ai21: For AI-powered text generation.

Install these using:
pip install pynput pyttsx3 SpeechRecognition ai21

🔧 Key Components
1.Keylogger: Listens for key presses and detects specific patterns.
2.Speech Recognition: Listens to your voice and converts it to text.
3.AI21 Integration: Processes your query and generates an intelligent response.
4.Text-to-Speech: Reads out the responses audibly.

🌟 Features to Improve
1.Custom Triggers: Add new trigger phrases for activating the assistant.
2.Enhanced Speech Models: Use advanced APIs for better accuracy.
3.Additional AI APIs: Expand response generation capabilities.

📝 License
This project is licensed under the MIT License. See the LICENSE file for details.

📧 Contact
Have questions or suggestions? Reach out at:
Your Name: [loganathanmurugan055@gamil.com]
GitHub: github.com/loga077

