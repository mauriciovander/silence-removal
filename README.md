# Adaptive voice activity detection


## USAGE: 

Compress audio file by rempving silence:

`python vad.py path/to/in.wav out`

Create a bunch of audio segments separated by occurring silences

`mkdir -p out && python segment.py path/to/in.wav out/out`
