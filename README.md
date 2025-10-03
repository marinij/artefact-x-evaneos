# Artefact x Evaneos - GPT-4o Audio Transcription

This project tests OpenAI's GPT-4o audio transcription capabilities.

## 📋 Overview

The project includes a Jupyter notebook that demonstrates how to transcribe multiple audio files using GPT-4o's transcription model.

## 🚀 Quick Start

### 1. Install Dependencies

```bash
uv sync
```

### 2. Set OpenAI API Key

Create a `.env` file based on `env.dist`:

```bash
cp env.dist .env
```

Then edit `.env` and add your actual OpenAI API key:

```
OPENAI_API_KEY=your-actual-api-key-here
```

## 📝 Requirements

- Python 3.12+
- OpenAI API key with access to GPT-4o models
- Audio files (max 25 MB per file)

## 📚 Documentation

For more details, see:
- [OpenAI Audio API Documentation](https://platform.openai.com/docs/models/gpt-4o-transcribe)

