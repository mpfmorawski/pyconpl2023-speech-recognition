# speech-recognition-with-python

Materials for "Speech Recognition with Python" lecture at PyConPL 2023 conference.

Materials include application examples of the following tools:

- [SpeechRecognition](https://github.com/Uberi/speech_recognition) (Python module supporting several speech-to-text engines and APIs)
- [AssemblyAI](https://www.assemblyai.com/) (API)
- [OpenAI's Whisper](https://github.com/openai/whisper) (speech-to-text model)
- [Transformers](https://github.com/huggingface/transformers) (pretrained speech-to-text models)

## Instructions for running a workshop using Google Colab

1. Go to [speech_recognition_with_python.ipynb](https://github.com/mpfmorawski/speech-recognition-with-python/blob/main/speech_recognition_with_python.ipynb) and click on `Open in Colab` button on top of the notebook.
2. Copy `.wav` files from [audio_files](https://github.com/mpfmorawski/speech-recognition-with-python/tree/main/audio_files)directory or [Google Drive folder](https://drive.google.com/drive/folders/1i-F-dVNvvMBG2TJEO2boT-3ihXnIRT4l?usp=sharing) into your personal Google Drive. Suggested path of the directory with the audio files is: `Colab Notebooks/speech_recognition_with_python`. **Note:** If you will be storing these files in a different location, be sure to change the `PATH` constant in the notebook.
3. Mount your Google Drive to your Google Colab notebook.
4. And... that's all! :partying_face:  Have a great learning experience!

**Please note**: To use AssemblyAI you need to create your own account on [https://www.assemblyai.com/](https://www.assemblyai.com/). After creating your account, you will receive an AssemblyAI API Key, which you need to copy into notebook (change the value of `ASSEMBLY_AI_API_KEY` constant in the notebook).
