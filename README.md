# Speech-ChatGPT Integration

This project integrates Text-to-Speech (TTS), Speech-to-Text (STT), and OpenAI's ChatGPT into a single Python script.

## Installation



1. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

2. Install PyAudio (if not installed):

    For Windows:
    ```bash
    pip install PyAudio-<version>.whl
    ```

    For Ubuntu:
    ```bash
    sudo apt-get install portaudio19-dev python3-pyaudio
    pip install pyaudio
    ```

3. Run the script:

    ```bash
    python speech_chatgpt.py
    ```

## Usage

- The script listens to your speech, converts it to text, sends the text to ChatGPT, and reads out the response.

## License

This project is licensed under the MIT License.
