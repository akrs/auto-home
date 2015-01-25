# auto-home
Some code I built for my DIY home automation stuff. I use a Raspberry PI B+, and an Arduino Micro currently. I'm using NRF24L01+ modules for communication.

## Raspberry PI

The goal is to make an extensible, flexible core, around which I can build modules for different inputs.

Due to the wireless modules, my code will require [pynrf24](https://github.com/jpbarraca/pynrf24) and [py-spidev](https://github.com/doceme/py-spidev). I ended up downloading both of those manually.
