# ConsensusTranscription
Use GPT4 to review and correct speech-to-text outputs from multiple transcription models. Costs 1 cent per minute of audio.

You need Deepgram and OpenAI API keys.

## Colab is the easiest way to test ConsensusTranscription for yourself.
https://github.com/andrewgcodes/ConsensusTranscription/blob/b8cc869375d7b30e8db604a72f36c3d6df187b1e/ConsensusTranscriptionV1.ipynb

Alternatively:
## To run from command line using v1.py:

Install the required packages. You need to have Python installed on your system and the required packages. The required packages are openai, requests, pydub, and rapidfuzz. Install them by running:

pip install openai requests pydub rapidfuzz
Note: You might need to use pip3 instead of pip depending on your Python configuration.

Install ffmpeg. You also need to have ffmpeg installed for handling audio files:


brew install ffmpeg
Note: If you haven't installed Homebrew yet, you can do so by following the instructions here: https://brew.sh/

Create the Python script. Copy the code I provided into a new file, and save it with a .py extension, for example, transcription.py.

Replace the placeholders. Make sure to replace "YOUR_OPENAI_API_KEY" and "YOUR_DEEPGRAM_API_KEY" with your actual OpenAI and Deepgram API keys.

Run the script. You can run the Python script from the terminal with:

python3 transcription.py /path/to/audio/file gpt-model-name
Replace "/path/to/audio/file" with the path to the audio file to transcribe, and "gpt-model-name" with the name of the GPT model to use (for example, "gpt-3.5-turbo").

You can also just edit the script directly to customize however you want.
