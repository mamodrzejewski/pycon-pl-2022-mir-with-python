# PyCon PL 2022 - Music Information Retrieval with Python

The following is a non-exhaustive list of interesting Python
tools useful for a variety music information retrieval (MIR) tasks.
Most of them are easy to use and very well documented, so Pythonistas can
start exploring right away!

## 1. Music and audio processing tools

* [Librosa](https://github.com/librosa) - **the** library for music and audio processing, feature extraction, visualization
* [Pedalboard](https://github.com/spotify/pedalboard) - easy to use audio processing including effects, like reverb, chorus, distortion etc.
* [pyo](https://github.com/belangeo/pyo) - low-level audio synthesis engine with digital signal processing
* [Audiomentations](https://github.com/iver56/audiomentations) - audio effects, very useful for data augmentation
* [PyDub](https://github.com/jiaaro/pydub) - convenient library for music and audio processing
* [SoundFile](https://github.com/bastibe/python-soundfile) - reading and writing audio in different formats
* [pretty-midi](https://github.com/craffel/pretty-midi) - MIDI processing, editing and visualization
* [MusPy](https://github.com/salu133445/muspy) - MIDI processing along with useful tools for symbolic music analysis and computing metrics
* [Partitura](https://github.com/CPJKU/partitura) - MIDI processing

## 2. APIs and datasets

* [Spotify API](https://developer.spotify.com/discover/) - very rich API, including musical features and structure data along artist, track, album etc. metadata
* [Deezer API](https://developers.deezer.com/api) - easy to use API including track, artist, song, playlist, genre etc. data
* [ISMIR datasets](https://www.ismir.net/resources/datasets/) - list of useful MIR datasets curated by the International Society for Music Information Retrieval
* [mirdata](https://github.com/mir-dataset-loaders/mirdata) - Python wrappers for working with many popular MIR datasets

## 3. Music processing with AI methods

* [Music Classification: Beyond Supervised Learning, Towards Real-world Applications](https://music-classification.github.io/tutorial/landing-page.html) - great resource for music classification and deep learning in MIR
* [SOTA tagging models](https://github.com/minzwon/sota-music-tagging-models) - state of the art music classification models implemented in PyTorch
* [Demucs](https://github.com/facebookresearch/demucs) - source separation model
* [Spleeter](https://github.com/deezer/spleeter) - source separation model
* [nussl](https://github.com/nussl/nussl) - source separation library with deep learning and more traditional methods
* [Basic Pitch](https://github.com/spotify/basic-pitch) - audio to MIDI transcription model
* [openL3](https://github.com/marl/openl3) - state of the art music embedding model and library

## 4. Generating music

* **key distinction:** neural audio synthesis (generating audio) vs. AI composition (generating symbolic music, ie. MIDI)
* [PixelRNN](https://arxiv.org/abs/1601.06759), [PixelCNN](https://arxiv.org/abs/1606.05328), [WaveNet](https://www.deepmind.com/blog/wavenet-a-generative-model-for-raw-audio) - raw audio synthesis
* [DDSP](https://magenta.tensorflow.org/ddsp), [Music Transformer](https://magenta.tensorflow.org/music-transformer) and other works by [Google Magenta](https://magenta.tensorflow.org/) with audio and symbolic music generation
* [OpenAI Jukebox](https://openai.com/blog/jukebox/) - raw audio synthesis
* [MuseGAN](https://salu133445.github.io/musegan/) -

## 5. Fun stuff!

* [Dadabots](https://dadabots.com) - musicians/programmers creating experimental music with deep learning
    - [Relentless Doppelganger](https://www.youtube.com/watch?v=MwtVkPKx3RA) - infinite live-stream of AI generated technical death metal
    - [Nuns in a moshpit](https://www.youtube.com/watch?v=tgq1YTQ2c0s) 😂 - metal/electronic song created using a variety of AI methods
* [Magenta demos](https://magenta.tensorflow.org/demos), including VSTs and Ableton plug-ins!
