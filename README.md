# 🌾 Kisan Awaaz — ਕਿਸਾਨ ਆਵਾਜ਼

Voice assistant for Indian farmers in Punjabi and Hindi.

## What it does
- 🎙️ Farmer speaks in Punjabi or Hindi
- 🧠 Fine-tuned Whisper-small transcribes speech
- 🎯 Intent detected: crop disease / mandi price / weather
- 🌐 Live APIs: Agmarknet mandi prices + Open-Meteo weather
- 🔊 Speaks the answer back in farmer's language (gTTS)

## Live Demo
👉 [Try it on HuggingFace Spaces](https://huggingface.co/spaces/Vaanianand/kisan-awaaz)

## Model
👉 [Fine-tuned Whisper on HuggingFace](https://huggingface.co/Vaanianand/kisan-awaaz-whisper)

## Architecture
Farmer speaks → Whisper ASR → Intent Classifier → Live APIs → gTTS → Farmer hears answer

## Tech Stack
- OpenAI Whisper-small (fine-tuned on Punjabi + Hindi)
- Google FLEURS dataset (11,595 training samples)
- HuggingFace Transformers + Gradio
- Agmarknet API (live mandi prices)
- Open-Meteo API (live weather)
- gTTS (Punjabi + Hindi voice)

## Languages
Punjabi (pa) · Hindi (hi)

## Live Demo
👉 [Try Kisan Awaaz on Hugging Face Spaces](https://huggingface.co/spaces/Vaanianand/kisan-awaaz)
