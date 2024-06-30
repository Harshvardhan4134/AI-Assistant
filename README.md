

# Voice Assistant

This project is a simple voice assistant that can listen to user commands, respond using text-to-speech, and perform certain actions like opening websites and telling the current time. It also integrates with OpenAI's GPT-3 to generate responses to user queries.

## Features

- **Speech Recognition:** Listens to user commands using the microphone and recognizes speech using Google's speech recognition API.
- **Text-to-Speech:** Responds with text-to-speech using `pyttsx3`.
- **Time Announcements:** Tells the current time.
- **Open Websites:** Opens specified websites.
- **AI Responses:** Generates responses using OpenAI's GPT-3.

## Requirements

- Python 3.x
- `speech_recognition` library
- `pyttsx3` library
- `openai` library
- `numpy` library
- `wikipedia` library
- `webbrowser` library
- A valid OpenAI API key

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/voice-assistant.git
    cd voice-assistant
    ```

2. **Install the required Python packages:**

    ```bash
    pip install -r requirements.txt
    ```

3. **Create a `config.py` file in the project directory and add your OpenAI API key:**

    ```python
    apikey = 'your_openai_api_key'
    ```

## Usage

1. **Run the script:**

    ```bash
    python voice_assistant.py
    ```

2. **The assistant will greet you based on the time of day and start listening for your commands.**

## Commands

- **Time:** Ask for the current time by saying "time".
- **Open Websites:** Open specific websites by saying "open [website name]". Supported websites are Instagram, YouTube, Wikipedia, and Google.
- **Exit:** Stop the assistant by saying "cut it", "bye", or "EXIT".

## Example

```plaintext
User: What is the time?
Assistant: The current time is 15:45:30.
User: Open YouTube
Assistant: Here you go buddy... opening YouTube.
User: Goodbye
Assistant: Goodbye, catch you later.
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgements

- [SpeechRecognition](https://pypi.org/project/SpeechRecognition/)
- [pyttsx3](https://pypi.org/project/pyttsx3/)
- [OpenAI](https://www.openai.com/)
- [Wikipedia](https://wikipedia.readthedocs.io/en/latest/code.html)

## `requirements.txt`

```plaintext
speechrecognition
pyttsx3
openai
numpy
wikipedia
```

## `LICENSE`

```plaintext
MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```
