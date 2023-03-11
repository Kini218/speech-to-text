# Speech-to-Text Transcription Script

This is a Python script that transcribes audio files to text using Google's speech recognition API. The script can handle audio files in WAV, MP3, M4A, OGG, or FLAC format.

## Dependencies

The following libraries are required to run this script:

- SpeechRecognition
- Pydub

You can install these libraries using pip:

```pip
pip install SpeechRecognition pydub
```

## Usage

To use the script, simply run `speech_to_text.py` and follow the prompts:

```python
python speech_to_text.py
```

The script will ask you to enter the path to the input audio file, the path to the output file, and the language code for the audio file.

## How It Works

The script first converts the input audio file to WAV format if necessary using the Pydub library. It then transcribes the audio data to text using the SpeechRecognition library and the Google speech recognition API. Finally, it writes the transcribed text to the output file.

## Why Use This Script?

This script can be useful for anyone who needs to transcribe audio files to text, such as researchers, journalists, and content creators. It provides a simple and efficient way to transcribe audio data, with support for multiple audio formats and languages.

## Supported Languages

Language | Code 
---------|------
English (US) | en-US 
English (UK) | en-GB 
French | fr-FR 
German | de-DE 
Spanish | es-ES 
Italian | it-IT 
Japanese | ja-JP 
Korean | ko-KR 
Mandarin Chinese | zh-CN 
Russian | ru-RU 

Note that this is not an exhaustive list of supported languages. For a full list of supported languages and their corresponding codes, see the [SpeechRecognition documentation](https://cloud.google.com/speech-to-text/docs/speech-to-text-supported-languages).

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
