# Streamlit OpenAi Voice AI ChatBot

## Introduction

This bot is a versatile, interactive personal assistant leveraging advanced AI capabilities to enhance your communication experience. This Python-based bot integrates seamlessly with various interfaces, offering functionalities like voice chat, web browsing, and customizable AI interactions. Whether you're looking for a robust chatbot interface or an AI-powered assistant for your projects, this bot has you covered.

## Features

- **Voice Chat**: Continuous voice input and output for hands-free interaction.
- **Internet Access**: Real-time web searches for the latest news, current events, weather forecasts, and more.
- **Web Browser UI**: A user-friendly interface for both voice and text chat.
- **Terminal Chat**: For those who prefer a more traditional command-line interface.
- **Fully Configurable**: Customize languages, LLMs, TTS, and STT engines, and AI parameters.
- **Chat Context Handling**: Efficient management of conversation context using embeddings.
- **API Usage Tracking**: Estimate token usage and costs.
- **Secure**: API keys are never stored on disk.

## Video Preview

[![Video Preview](https://github.com/paulovcmedeiros/pyRobBot/blob/main/pyrobbot/app/data/assistant_avatar.png?raw=true)](https://pyrobbot.streamlit.app)

## System Architecture

`pyRobBot` is designed with a modular architecture, integrating various components to provide a seamless user experience:

- **OpenAI API**: Powers the language model for intelligent responses and interactions.
- **Secure Environment Management**: Uses environment variables to manage sensitive information securely.
- **Python Backend**: Leveraging Python's extensive library ecosystem for HTTP requests, database connections, and more.

## Installation and Setup

### Prerequisites

- Python >= 3.9
- A valid [OpenAI API key](https://platform.openai.com/account/api-keys)
- Additional libraries for voice chat:
  - [PortAudio](https://www.portaudio.com/docs/v19-doxydocs/index.html)
  - [ffmpeg](https://ffmpeg.org/download.html)

### Step-by-Step Installation

1. **Clone the Repository**
    ```shell
    git clone https://github.com/lightningcraft-0201/Streamlit-OpenAi-VoiceBot
    cd pyRobBot
    ```

2. **Install Requirements**
    ```shell
    pip install -r requirements.txt
    ```

3. **Configure Environment Variables**
    Rename `example.env` to `.env` and add your OpenAI API key:
    ```env
    OPENAI_API_KEY=your_openai_api_key
    ```

4. **Run the Bot**
    ```shell
    python main.py
    ```

## Usage

### Web Interface
Launch the web UI for an interactive experience with voice and text chat:
```shell
rob
```

### Voice Chat Only
For a purely voice-based interaction:
```shell
rob voice
```

### Terminal Interface
Run the bot in the terminal:
```shell
rob .
```

## Future Enhancements

- Integrate more functionalities and improve existing ones.
- Enhance AI capabilities for better interaction.
- Improve user data security with advanced encryption techniques.

## Contributing

We welcome contributions from the community to make `pyRobBot` more robust and feature-rich. Please refer to the contributing guidelines in the repository for more information.

## Support and Feedback

For support, feature requests, or to report bugs, please open an issue in the project repository or contact the maintainers directly.