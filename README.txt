install: 

sudo apt-get update
sudo apt-get install libasound2-dev

build: 

gcc -o alsa_playback_wav alsa_playback_wav.c -lasound


example: 

./alsa_playback_wav 44100 2 180 < /home/bhien/music.wav 
