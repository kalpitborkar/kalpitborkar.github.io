---
title: "Chip8 Emulator"
layout: post
# date: 2016-01-23 22:10
tag:
- cpp
- c++
- chip8
- emulator
image: https://sergiokopplin.github.io/indigo/assets/images/jekyll-logo-light-solid.png
headerImage: false
projects: true
hidden: false # don't count this post in blog pagination
description: "A simple chip-8 emulator written using C++ and SDL2 library."
category: project
author: kalpitborkar
externalLink: false
---

# Chip-8 Emulator
A simple chip-8 emulator written using C++ and [SDL2 library](https://www.libsdl.org/).\
Check the github repository here: [Chip8 Emulator](https://github.com/kalpitborkar/Chip8-Emulator)

## What is an emulator?
An emulator is a computer program that mimics the internal design and functionality of a computer system (System A). It allows users to run software designed for this specific system (Sytem A) on a totally different computer system or architecture (System B).

## What is chip-8?
CHIP-8 is an interpreted programming language, developed by Joseph Weisbecker. It was initially used on the COSMAC VIP and Telmac 1800 8-bit microcomputers in the mid-1970s. CHIP-8 programs are run on a CHIP-8 virtual machine. It was made to allow video games to be more easily programmed for these computers, but CHIP 8 is still used today, due to its simplicity, and consequently on any platform and its teaching of programming Binary numbers.

## Chip-8 Architecture

| Variable                           | Description                                                                    |
| ---------------------------------- | ------------------------------------------------------------------------------ |
| `unsigned short opcode`            | Stores the current opcode, out of a total of 25 opcodes                        |
| `unsigned char memory[4096]`       | Emulated memory of 4KB                                                         |
| `unsigned char V[16]`              | 15 8-bit general purpose registers                                             |
| `unsigned short I`                 | Index register                                                                 |
| `unsigned short pc`                | Program counter                                                                |
| `unsigned char gfx[64 * 32]`       | Graphics for 64x32 pixels (black and white)                                    |
| `unsigned char delay_timer`        | Register that counts at 60 Hz                                                  |
| `unsigned short stack[16]`         | Stack used to remember the current location before a jump is performed         |
| `unsigned short sp`                | Stack pointer to remember current level of stack                               |
| `unsigned char key[16]`            | Stores the current state of the key for HEX based keypad                       |

## Compiling and Running

### Requires cmake and SDL2:
```
$ sudo apt-get install cmake libsdl2-dev
```

### Compile:
```
$ mkdir build
$ cd build
$ cmake ..
$ make
```

### Run:
```
./chip8 <ROM file>
```

## License
Distributed under the MIT License. See `LICENSE.md` for more information.

## References
- https://multigesture.net/articles/how-to-write-an-emulator-chip-8-interpreter/
- https://en.wikipedia.org/wiki/CHIP-8
- https://austinmorlan.com/posts/chip8_emulator/
