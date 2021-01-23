# OST-Morse-Box-DG
Extension of the original OST Morse Box with a Decoder and an AF Generator, but remaining fully compatible with the existing hardware.
You will need to build the basic OST Morse Box first, see https://github.com/on7dq/OST-Morse-Box

The OST Morse Box can be extended in software and hardware, to include a CW decoder for transmitted AND received signals. 
For receiving, a small extra PCB must be assembled, and connected to input D2 (connect at the Paddle Test jumper).
There are two versions of the decoder:
- one is based on a simple circuit with an LM567 Tone Decoder, and can be built with through-hole components (easy)
- one is based on a bandpass filter and level detector, and is only available in an SMD version (advanced)

For alignment purposes, the OST Morse Box now also contains an AF Generator, which can provide a test signal for general use (sine wave only).

The Windows program has been updated with the necessary extra functions, and some other improvements.

There is now also a quick and easy way to program the firmware into the Arduino Nano, using the program XLOADER.

A 20 page manual describing the new functions is available in Dutch and English (volunteers to translate into other languages welcome!).

We hope you find these extensions useful and fun!

73,
Luc ON7DQ and Gilbert ONL12523
Ostend - January 2021
