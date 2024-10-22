# VoiceLLAVA - Voice Assistant with LLAVA

VoiceLLAVA is a voice assistant application built using the power of natural language processing and voice recognition. This project integrates a Large Language Model with voice commands to provide a hands-free interface for users to interact with and get responses in real-time.

## Features
- **Voice Recognition**: Converts spoken words into text.
- **Natural Language Understanding**: Processes user queries using a language model to generate responses.
- **Real-time Interaction**: Responds instantly to spoken commands, creating an interactive voice-based system.
- **Flexible Usage**: Can be expanded to serve different use cases (e.g., personal assistant, home automation, etc.).

## Project Structure

- `Voice_Assistant.ipynb`: Jupyter notebook implementing the core functionalities of the voice assistant.
- `requirements.txt`: List of Python dependencies required to run the project.
- `README.md`: This file, which provides an overview of the project.

## Installation and Setup

To run this project locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Arashomranpour/VoiceLLAVA.git
    cd VoiceLLAVA
    ```

2. **Install the required dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Jupyter notebook**:
    Open `Voice_Assistant.ipynb` in Jupyter and run the cells sequentially to start the voice assistant.

## Requirements

- Python 3.8 or higher
- `SpeechRecognition`: Used for converting speech to text.
- `gTTS`: Google Text-to-Speech for generating audio responses.
- `transformers`: Hugging Face's transformer library for language modeling.
- Jupyter Notebook (for running the provided `.ipynb` file)

## Usage

Once the environment is set up and the notebook is running, the voice assistant will listen for commands and respond with spoken answers. It uses pre-trained models for natural language understanding and can be customized based on specific needs.

## Future Enhancements

- **Expand Command Set**: Include more predefined commands for diverse use cases.
- **Custom Responses**: Allow users to define personalized responses or actions.
- **Web Integration**: Deploy the assistant as a web app for easier access.

## Contributing

Feel free to fork the repository, submit issues, and create pull requests. Contributions are welcome to improve the assistant’s capabilities and performance.

