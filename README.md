1. Project Title and Description:
Title: VoiceLLAVA - Voice and Image Interactive Language Model Assistant
Description:
"VoiceLLAVA is a multimodal assistant that utilizes an advanced large language model to interact with users through voice and image inputs. It features real-time voice recognition, image processing, and text-to-speech capabilities, all powered by the LLava model and Gradio's web interface."
2. Installation Instructions:
Prerequisites: Ensure you have the following installed:
Python 3.8+
PyTorch (with CUDA for GPU acceleration)
transformers library
Gradio for the web interface
gTTS for text-to-speech conversion
ffmpeg for handling audio inputs/outputs
Installation Steps:
bash
Copy code
git clone https://github.com/Arashomranpour/VoiceLLAVA.git
cd VoiceLLAVA
pip install -r requirements.txt
Additional Setup: Make sure to install the correct LLava model:
bash
Copy code
transformers-cli download llava-hf/llava-1.5-7b-hf
3. Usage Guide:
Basic Usage: To run the interface, execute:
bash
Copy code
python Voice_Assistant.ipynb
Interacting with the Assistant:
Audio Input: Speak through your microphone to interact with the assistant.
Image Input: Upload an image to get a contextual response.
Output: You'll receive a text response along with audio playback of the model's response.
4. Modules & Workflow:
Main Components:
Audio Input & Speech-to-Text: Uses Whisper for transcription.
Text and Image Processing: Combines image-to-text and speech-to-text for interaction using the LLava model.
Text-to-Speech: Converts model-generated text back into audio using gTTS.
Gradio Interface:
The interface allows users to input audio and image files, interact with the model, and receive responses in both text and audio formats.
