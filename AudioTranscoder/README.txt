install: 

sudo apt install ffmpeg libavformat-dev libavcodec-dev libswresample-dev

build:

mkdir build && cd build
cmake -DBUILD_EXAMPLES=ON ..
make


example: 

./convert ../music/music.mp3 ../music.wav

./generate_a(create music files)
