# Developing-Generative-AI-Applications-with-Python

## 1] Image Captioning With Generative AI

  This application is used for describing the images using text.

  - Implemented an image captioning tool using the BLIP model from Hugging Face's Transformers.
  - Used Gradio to provide a user-friendly interface for this image captioning application.

‣ I have used the BLIP image captioning

>#### Processor    
    
    Salesforce/blip-image-captioning-base

>#### Model

    Salesforce/blip-image-captioning-large

but, you can also use the BLIP-2 models

>#### Processor

    Salesforce/blip2-flan-t5-xxl

>#### Model

    Salesforce/blip2-opt-6.7b

## Speech To Text
>### Hugging Face Transformers:
Used Hugging Face's transformers library to implement the Whisper model for speech-to-text conversion.
Specifically utilized openai/whisper-tiny.en, a state-of-the-art model for automatic speech recognition (ASR).
>### Gradio:
Designed a user-friendly interface for uploading and transcribing audio files using Gradio.
Enabled interactive audio file uploads and displayed transcription results in real-time.
>### Python Libraries:
Utilized essential libraries like requests for downloading the audio file and torch for running the deep learning model.
Applied ffmpeg for audio file handling and processing, ensuring compatibility with Whisper model input.
