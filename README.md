# SDL-Libraries
In Future all SDL Libraries

How  install :

wget https://www.libsdl.org/release/SDL2-2.0.5.tar.gz https://www.libsdl.org/projects/SDL_ttf/release/SDL2_ttf-2.0.14.tar.gz https://www.libsdl.org/projects/SDL_image/release/SDL2_image-2.0.1.tar.gz https://www.libsdl.org/projects/SDL_mixer/release/SDL2_mixer-2.0.1.tar.gz https://www.libsdl.org/projects/smpeg/release/smpeg2-2.0.0.tar.gz https://www.libsdl.org/projects/SDL_net/release/SDL2_net-2.0.1.tar.gz

ls smpeg2*.tar.gz SDL2*.tar.gz | xargs -i tar -zxvf {}


ls -d smpeg2*/ SDL2*/ | xargs -i bash -c "cd {} && ./configure && make   -i - k"


ls -d smpeg2*/ SDL2*/ | xargs -i bash -c "cd {} && sudo make install  -i - k "


https://forum.outpost2.net/index.php?topic=5978.0
