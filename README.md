# freeglut-binary
Instructions for compiling freeglut versions

## Pre-compiled packages
Freeglut can be installed directly from package managers on the following systems: 
- **macOS** via `brew install freeglut`,
- **Debian, Ubuntu, Linux Mint, etc.** via `apt install freeglut`,
- **Arch Linux** via `pacman -S freeglut`

For more detailed instructions, please follow the tutorials on the freeglut project website: [Freeglut project](https://freeglut.sourceforge.net/index.php#download) or in the documentation for your package manager and the associated repositories.

# Cross-compile on your system
1. Install [cmake](https://cmake.org/download/) on your system using the attached website
2. Download the source code from the Freeglut [wesbite](https://freeglut.sourceforge.net/index.php#download)
3. Extract the code using: `tar -xvf freeglut-*.tar`
4. Enter the directory of the extracted project: `cd freeglut-*`
5. Run `cmake .`
6. Run `make`
7. Run `make install`
