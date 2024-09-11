install: 

sudo apt install ffmpeg libavformat-dev libavcodec-dev libswresample-dev

build:

mkdir build && cd build
cmake -DBUILD_EXAMPLES=ON ..
make


example: 

./convert input.ext1 output.ext2

./generate_a(create music files)