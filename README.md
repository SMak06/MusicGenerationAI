# MusicGenerationAI
Create sequences of pop music as midi files using Tensorflow RNN

## Overview
Use TensorFlow to generate short sequences of music with a [Restricted Boltzmann Machine](http://deeplearning4j.org/restrictedboltzmannmachine.html). 
Original code comes from YouTube, see here: (https://youtu.be/ZE7qWXX05T0)

## Dependencies

  * [Tensorflow](https://www.tensorflow.org/install)
  * pandas
  * numpy
  * msgpack-python
  * glob2
  * tqdm 
  * python-midi
  
Use [pip](https://pypi.python.org/pypi/pip) to install any missing dependencies (pip install --upgrade ... ) 

### Dependencies on Windows with python3
```
    pip3 install pandas
    pip3 install msgpack-python
    pip3 install numpy
    pip3 install glob2
    pip3 install tqdm
    pip3 install py-midi
```

## Basic Usage
To train the model and create music, simply clone this directory and run
```
python rbm_chords.py
```

The training data goes in the pop_music_midi folder. You have to use MIDI files. You can find some [here](http://www.midiworld.com/files/).
I have already added pop songs.
The output will be a collection of midi files.

