# Arabic-Synthesizer
An arabic synthesizer that utilizes the 24 tone equal temprament tonal system and played via a keyboard

## Prerequisits
The **Arabic-Synthesizer** is built in nim, and requires the following nim dependencies:
  1. ``Nim >= 2.0.2`` 
  2. ``x11 >= 1.2.0`` 
  3. ``sdl2 >= 2.0.5``
    
Install the corresponding packages for the bindings above in your choice of distribution

## How to build
Assuming that you installed [**nim and nimble**](https://nim-lang.org/install_unix.html)
```
git clone https://github.com/DigitalRedPanda/arabic-synthesizer.git
nimble install sdl2 x11
nimble build -d:release --opt:speed
./synthesizer
```
