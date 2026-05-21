# Smart Glasses Image Captioning with Text-to-Speech

This project presents an NLP and Computer Vision prototype for a smart-glasses assistive system. The system uses an image captioning model to generate a natural language description of an uploaded image, then converts the generated caption into speech. The project used a pre-trained ViT-GPT2 image captioning model from Hugging Face, trained/tested with the Flickr8k dataset, and built a simple Gradio interface where the user can upload an image and receive both text and audio output.

## Key Details

- **Course:** CS4083 / NLP
- **Tools:** Python, PyTorch, Hugging Face Transformers, Gradio, gTTS, Google Colab
- **Dataset:** Flickr8k
- **Model:** `nlpconnect/vit-gpt2-image-captioning`
- **Task:** Image caption generation
- **Output:** Text caption + speech/audio file
- **Training Setup:** Fine-tuning experiment using a subset of 1000 samples and 80 training steps
- **Main Goal:** Support smart-glasses users by converting visual scenes into spoken descriptions

## Workflow

1. Upload an image.
2. Process the image using the ViT-GPT2 image captioning model.
3. Generate a short natural language caption.
4. Convert the caption into speech using gTTS.
5. Display both the generated text and audio output in the Gradio interface.


## Files

- `ModelTraining_NLP_Proj.ipynb` — Google Colab notebook for model training, caption generation, text-to-speech, and Gradio demo.
- `Nlp_Ai.pdf` — Project report explaining the background, methodology, implementation, results, and future work.

## Project Scope

This project is a proof-of-concept software prototype. It does not run on physical smart-glasses hardware yet, but it demonstrates the core image-to-speech pipeline that can support future smart-glasses visual assistance systems.

## Demo Video

A demo video for the Smart Glasses Image Captioning with Text-to-Speech project is available through the link below.

The video demonstrates the image captioning and text-to-speech workflow, where an uploaded image is processed by the ViT-GPT2 image captioning model, a caption is generated, and the result is converted into speech.

[Watch the Demo Video](https://drive.google.com/drive/folders/1JG2zNumNc1UxpsNOPC4H1V4SA3UaPcp9?usp=sharing)
