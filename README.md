# VisionWhiz: Talk to Your Image AI
VisionWhiz is a futuristic AI-powered web application that allows users to ask questions about any image using voice or text—and receive intelligent answers, both spoken and displayed. By integrating powerful models from OpenAI, Salesforce, and Google, VisionWhiz delivers real-time, context-aware visual interaction through a sleek Gradio interface.

#  Project Overview
The goal of VisionWhiz is to:

Enable natural, multimodal interaction with images through voice and text.

Seamlessly integrate speech recognition, visual question answering, and text-to-speech features.

Improve accessibility and elevate the human-computer interaction experience.

#  Features
Voice & Text Input
Speech-to-Text: Speak your question naturally (powered by openai/whisper-small).

Text Input: Optionally, type your question into the input box.

#  Visual Intelligence
Image Upload: Upload any image for interactive questioning.

Visual Question Answering: Get accurate, context-aware answers using Salesforce/blip-vqa-base.

#  Smart Audio Output
Text-to-Speech: Listen to the answer read out loud with Google’s gTTS.

# Interactive Interface
Gradio Frontend: Built with Gradio and custom CSS for a clean, modern UI.

Smooth, real-time interaction across all components.

# Tech Stack
Component	Model/Library
Speech-to-Text	openai/whisper-small (HuggingFace)
Image QA	Salesforce/blip-vqa-base
Text-to-Speech	gTTS (Google Text-to-Speech)
UI Framework	Gradio
Audio/Image I/O	torchaudio, soundfile, PIL

# Project Structure
bash
Copy
Edit
VisionWhiz/
├── app.py               # Main app logic and Gradio interface
└── README.md            # Project documentation
#  Use Cases
 Ask what’s happening in any image using natural language.

 Create accessible educational tools with audio support.

 Aid users with visual impairments or reading difficulties.

 Prototype intelligent assistants for vision-language tasks.
# ARCHITECTURE DIAGRAM
![1_FXFCM5IrtGG3xyTr97-ONg](https://github.com/user-attachments/assets/df481120-acf2-41e5-83b9-f10ce6300292)

# Performance Snapshot
<img width="1309" alt="Screenshot 2025-06-25 at 12 39 13 AM" src="https://github.com/user-attachments/assets/fa426525-683d-47fc-b454-b3540f317a13" />
<img width="1330" alt="Screenshot 2025-06-25 at 12 39 27 AM" src="https://github.com/user-attachments/assets/49d204f4-b9b9-43a4-b037-5381ca3e4e3c" />

# Developed by
Absar Raashid
