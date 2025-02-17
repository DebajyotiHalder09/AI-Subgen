# AI Subgen

## Description
AI Subgen allows you to generate subtitles effortlessly using OpenAI Whisper. This is version 1.0, requiring installation to use. Future versions may include a standalone application.

Currently, the program runs via the terminal.

## Installation

### Download Python
```sh
# For Windows (Download from official site)
https://www.python.org/downloads/

# For Linux (Using apt)
sudo apt update && sudo apt install python3
```

### Download OpenAI Whisper
```sh
pip install openai-whisper
```

### Download PyTorch
```sh
# For CUDA (NVIDIA GPU acceleration)
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118

# For CPU-only installation
pip install torch torchvision torchaudio
```

### Download Flask
```sh
pip install flask
```

### Download Flask-CORS
```sh
pip install flask-cors
```

## Usage
1. Clone the repository.
2. Open a code editor and navigate to the cloned folder.
3. Run `main.py`.
4. An IP address will appear in the terminal.
5. Ctrl + Click on the displayed IP address to open the program in your browser.
6. Upload an audio file and an optional JSON file (if available), then play to enjoy.
7. If you don't have a JSON file, click on "Transcribe," wait for processing, and download the generated file.
8. Enjoy seamless subtitle generation!

## Features
- Utilizes a basic HTML audio player for playback.
- Uses the OpenAI Whisper tiny model for transcription.
- Accuracy may vary based on the model size—larger models offer better accuracy but require more processing power.
- Easy-to-use interface with transcription and playback functionality.

## Future Improvements
- Standalone application version.
- Enhanced UI for better user experience.
- Support for multiple models with configurable accuracy and speed settings.

## License
(Include your license details here.)

