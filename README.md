# Lua Music

This is the Day 3 Project for Chapter 1 ('Lua') of [Seven More Languages in Seven Weeks](https://pragprog.com/book/7lang/seven-more-languages-in-seven-weeks).

It is uses C++ to generate MIDI, wrapped in a Lua API.

### Dependencies

* A C++ compilier
* The CMake tool
* The Lua C headers and libraries
* The RtMidi sound library
* A Midi synthesizer app

### Setup

```
git clone http://github.com/jwworth/lua-music
cd lua-music
cmake .
make
./play canon.lua
```
