# Tone Analysis and Message Refinement

This Streamlit app analyzes the tone of an uploaded or recorded audio file and helps you refine your intended message to match the acoustic characteristics of your voice.

## Features

- Upload or record a `.wav` audio file
- Analyze audio for MFCCs, duration, pitch arc, and intensity
- Enter your intended message
- Get a refined message that matches your tone using OpenAI's GPT model

## Installation

1. **Clone the repository** (or copy the files to your project directory):

   ```bash
   git clone <your-repo-url>
   cd <project-directory>
   ```

2. **Install dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

3. **Set up your OpenAI API key**:

   Create a `.env` file in the project directory and add:

   ```
   OPENAI_API_KEY=your_openai_api_key_here
   ```

## Usage

Run the Streamlit app:

```bash
streamlit run streamlit.py
```

Follow the on-screen instructions to upload or record audio, analyze your tone, and refine your message.

## Files

- `streamlit.py` — Main Streamlit app
- `agents.py` — Agent and Runner classes for OpenAI API interaction
- `requirements.txt` — Python dependencies

## License

MIT License