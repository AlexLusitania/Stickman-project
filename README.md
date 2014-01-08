Stickman-project
================
Little plateformer game in C++
================

This project works with the SFML-2.1 library. To install it :
1. if you have an old version of SFML, remove it using sudo rm -rf /usr/include/SFML && sudo rm -f /usr/lib/libsfml*
2. sudo apt-get update
3. install : pthread, opengl, xlib, xrandr, freetype, glew (1.7), jpeg, sndfile, openal. Don't forget forget the dev files of these libraries
4. go to the directory where you want to copy the project and use git clone https://github.com/codeOverFlow/Stickman-project.git
5. go to SFML-master/ and use sudo cmake ./
6. sudo make && sudo make install
7. sudo cp -r /usr/local/include/SFML /usr/include && sudo ln -s /usr/local/lib/libsfml* /usr/lib
