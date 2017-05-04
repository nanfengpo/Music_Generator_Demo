# Music Generator Demo

##Overview
Use TensorFlow to generate short sequences of music with a [Restricted Boltzmann Machine](http://deeplearning4j.org/restrictedboltzmannmachine.html). This is the code for [Generate Music in TensorFlow]() on YouTube. 

##Dependencies

* python2.7.12
* [Tensorflow](https://www.tensorflow.org/versions/r0.10/get_started/os_setup.html)
* pandas
* numpy
* msgpack (pip2 install msgpack-python)
* glob (pip2 install glob2)
* tqdm (pip2 install tqdm)
* midi (pip2 install python-midi)（midi暂时只支持pyhton2）

Use [pip](https://pypi.python.org/pypi/pip) to install any missing dependencies.

##Basic Usage
To train the model and create music, simply clone this directory and run
```
python rbm_chords.py
```

The training data goes in the pop_music_midi folder. You have to use MIDI files. You can find some [here](http://www.midiworld.com/files/). Training will take 5-10 minutes on a modern laptop. The output will be a collection of midi files. You can combine them together with a script if you'd like. 

##Challenge

The challenge for this video is to create a happy/upbeat MIDI file using this script. You could play with the hyperparameters if you'd like to see what works, choose a happy/upbeat MIDI dataset, or do both. When you're done, upload your clone of this repository whether or not the code is modified with your generated MIDI files included in the repo. Post a link to your code in the comments of the video. I'll mention the winner (the most upbeat sounding MIDI, any of the snippets is fine or if you want you can combine them) in my next video. Good luck!!

##Credits

The credit for this code goes to [dshieble](https://github.com/dshieble) i've merely created a wrapper around his code to make it easier to get started. 
