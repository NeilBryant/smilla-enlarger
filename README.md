# SmillaEnlarger

## About
One fascinating aspect of analogue photography is, that by means of an Enlarger, you can pick an interesting part of your photo and blow it up to poster size. Whereas zooming into a digital photo just leads to a bunch of colored blocks.

This tool tries to be an easy-to-use equivalent of the analogue enlarger for the digital photography:

You choose an image file, pick a rectangle and decide how big the result should be (by scaling factor or by giving width or height of the result), then you press 'Enlarge & Save' and get an enlarged image with smooth curves instead of blocks, where edges in the original stay (more or less) unblurred edges in the result.

If you want to know more about the usage of this program [click here](./docs/usage.md)

## Compilation
The compilation requires QT5.

### Debian
Compilation Dependencies:
````
apt install -y git g++ build-essential qt5-qmake qt5-default
````

Compilation: run `qmake && make` in the main directory.

### Fedora
Compilation Dependencies:
````
dnf install -y qt5-devel gcc-c++ git qt5-qtbase-devel
````

Compilation:  run `qmake-qt5 && make` in the main directory.

### Arch
Compilation Dependencies:
````
pacman -S git qt5-base base-devel
````

Compilation:  run `qmake && make` in the main directory.

## Atributions
The original code is hosted here: https://sourceforge.net/projects/imageenlarger/

Desktop file by Dariusz Duma < dhor@toxic.net.pl >
