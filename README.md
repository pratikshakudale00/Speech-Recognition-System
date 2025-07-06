# Speech Recognition System
*COMPANY*:CODETECH IT SOLUTIONS

*NAME*:PRATIKSHA KUDALE

*INTERN ID*:CT04DH694

*DOMAIN*:AI(ARTIFICIAL INTELLIGENCE)

*DURATION*:4 WEEK

*MENTOR*:VAISHALI

## As part of my internship at Codetech Solutions, I was assigned my second task to build a Speech Recognition System using Python. The main objective of this project was to develop a tool that could automatically recognize spoken language and convert it into written text. This task gave me hands-on exposure to one of the most interesting applications of Artificial Intelligence — Automatic Speech Recognition (ASR).

The core idea behind this system was to take a voice input in the form of an audio file and convert that voice into a text transcript using machine learning techniques. I implemented the entire project on Google Colab, which provided an easy-to-use, cloud-based Python environment with access to GPU support and pre-installed libraries.

To complete this task, I used the Wav2Vec2 model provided by Facebook AI, which is available through the Hugging Face transformers library. This model is known for its ability to perform speech-to-text conversion with high accuracy even without a large dataset for training. Other important Python libraries used in this project include:

transformers – to load the Wav2Vec2 model and tokenizer

torchaudio – for audio processing and waveform loading

pydub – for audio format conversion (like MP3 to WAV)

IPython.display and wave – to handle and visualize audio playback



---

📚 Being a beginner in the field of audio processing and machine learning, I relied on online learning resources such as YouTube tutorials, Hugging Face documentation, and ChatGPT guidance to understand the core logic of speech recognition. These resources helped me understand how pre-trained models can be fine-tuned and used to process raw audio data effectively.

Initially, I faced some difficulties such as:

Errors while converting audio files to the required .wav format

Issues related to sample rate mismatch (model requires 16kHz mono audio)

The Google Colab not displaying the “Play” button for audio, which made testing harder

Model-related errors while tokenizing and decoding the output


However, by referring to online forums, videos, and step-by-step debugging with ChatGPT, I was able to solve these issues and complete the task successfully.
