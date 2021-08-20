# OST-Morse-Box-DG
Extension of the original OST Morse Box with a **Transmit and Receive Decoder** and an **AF Generator**, but remaining fully compatible with the existing hardware.
You will need to build the basic OST Morse Box first, see https://github.com/on7dq/OST-Morse-Box

Additionaly, the keyer routine has been enhanced with **Iambic A and B** modes, settable in the latest version of the Windows Control program.

The OST Morse Box can be extended in software and hardware, to include a CW decoder for transmitted AND received signals. 
For receiving, a small extra PCB must be assembled, and connected to input D2 (connect at the Paddle Test jumper).
There are two versions of the decoder:
- one is based on a simple circuit with a PLL Tone Decoder (LM567), and can be built with through-hole components (easy)
- one is based on a bandpass filter and level detector, and is only available in an SMD version (advanced)

For alignment purposes, the OST Morse Box now also contains an AF Generator, which can provide a test signal for general use (sine wave only).

The Windows program has been updated with the necessary extra functions, and some other improvements.

There is now also a quick and easy way to program the firmware into the Arduino Nano, using the program XLOADER.

An 18 page manual describing the new functions is available in Dutch and English (volunteers to translate into other languages welcome!).

We hope you find these extensions useful and fun!

73,
Luc ON7DQ and Gil ONL12523
Ostend - January 2021

**EDIT** : in August 2021, I rebuilt my prototype, now to include all known "bells and whistles" of this project, see pictures of the front and back of my new box above, or visit my blog for a detailed description of my build. 
https://on7dq.blogspot.com/2021/08/ost-morse-box-dg-on7dq-version.html

