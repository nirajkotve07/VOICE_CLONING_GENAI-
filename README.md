# Voice Cloning with Tacotron2 and Vosk

This project implements voice cloning using Tacotron2 for text-to-speech synthesis and Vosk for speech recognition. It allows you to clone a voice by providing an audio sample and generating a new audio with the same voice characteristics speaking a different text.

## Features

* Clone a voice by transcribing an audio sample and generating a new audio with the same voice speaking a different text.
* Leverages Tacotron2, a state-of-the-art deep learning model for text-to-speech synthesis.
* Utilizes Vosk, a lightweight and efficient speech recognition toolkit.

## Requirements

* Python 3.6 or later
* Libraries:
    * TTS
    * matplotlib
    * scipy
    * numpy
    * vosk
    * pydub

You can install the required libraries using the following command:

```bash
pip install TTS matplotlib scipy numpy vosk pydub
