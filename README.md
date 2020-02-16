# SDL-Libraries
In Future all SDL Libraries

How  install :

wget https://www.libsdl.org/release/SDL2-2.0.5.tar.gz https://www.libsdl.org/projects/SDL_ttf/release/SDL2_ttf-2.0.14.tar.gz https://www.libsdl.org/projects/SDL_image/release/SDL2_image-2.0.1.tar.gz https://www.libsdl.org/projects/SDL_mixer/release/SDL2_mixer-2.0.1.tar.gz https://www.libsdl.org/projects/smpeg/release/smpeg2-2.0.0.tar.gz https://www.libsdl.org/projects/SDL_net/release/SDL2_net-2.0.1.tar.gz

ls smpeg2*.tar.gz SDL2*.tar.gz | xargs -i tar -zxvf {}


ls -d smpeg2*/ SDL2*/ | xargs -i bash -c "cd {} && ./configure && make   -i - k"


ls -d smpeg2*/ SDL2*/ | xargs -i bash -c "cd {} && sudo make install  -i - k "


https://forum.outpost2.net/index.php?topic=5978.0



1. SDL Installation

To install latest version of SDL (1.2, SDL 1.3 is still under development), run this sequence of commands from the terminal:

wget -O SDL-1.2.14.tar.gz  http://goo.gl/ByL0B


tar -xzvf SDL-1.2.14.tar.gz -C ~/ && cd SDL-1.2.14


./configure && make


sudo make install

2. SDL_image 1.2 Installation

Via the terminal, run the following commands:

wget -O SDL_image-1.2.11.tar.gz http://goo.gl/98zi6


tar -xzvf SDL_image-1.2.11.tar.gz -C ~/ && cd SDL_image-1.2.11


./configure && make


sudo make install

3. SDL_mixer 1.2 Installation

Run the following commands:

wget -O SDL_mixer-1.2.12.tar.gz http://goo.gl/o0GIX


tar -xzvf SDL_mixer-1.2.12.tar.gz -C ~/ && cd SDL_mixer-1.2.12


./configure && make


sudo make install

4. SDL_net 1.2 Installation

Issue these commands:

wget -O SDL_net-1.2.8.tar.gz http://goo.gl/AQuv5


tar -xzvf SDL_net-1.2.8.tar.gz -C ~/ && cd SDL_net-1.2.8


./configure && make


sudo make install


http://www.upubuntu.com/2012/01/how-to-install-sdl-12-simple.html
