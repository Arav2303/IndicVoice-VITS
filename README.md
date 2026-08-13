# IndicVoice-VITS

## Multilingual Text-to-Speech Pipeline

IndicVoice-VITS is a multilingual text processing and speech synthesis pipeline.

The system accepts text input in different languages and can translate the input into a selected output language. The current speech synthesis stage uses a custom-trained Hindi female VITS model.

## Current Capabilities

- Multilingual text input
- English translation
- Hindi translation
- Marathi translation
- Kannada translation
- Custom-trained Hindi female voice
- VITS-based Text-to-Speech
- Gradio-based interface

## Current Speech Output

The current version generates speech using a custom-trained **Hindi female VITS model**.

Translation supports multiple languages, while native speech synthesis for additional languages is planned for future development.

## Pipeline

Input Text
↓
Language Processing / Translation
↓
Selected Output Language
↓
Hindi Text Processing
↓
Custom Hindi Female VITS
↓
Speech Output

## Notebooks

### Inference

`notebooks/IndicVoice_V2_Inference.ipynb`

Contains the inference pipeline and application interface.

### Training

`notebooks/Hindi_VITS_Training.ipynb`

Contains the training workflow for the custom Hindi VITS model.

# Important 

Translation: Multilingual input/output

Speech synthesis: Hindi female VITS

## Technologies

- Python
- PyTorch
- VITS
- Gradio
- Speech Processing
- Machine Translation
- Google Colab

## Future Work

- Marathi TTS
- Kannada TTS
- English TTS
- Multilingual TTS models
- Multiple speaker/voice support
