Play Melody

This example makes use of a Piezo Speaker in order to play melodies. We are taking advantage of the processors capability to produde PWM signals in order to play music. There is more information about how PWM works written by David Cuartielles here and even at K3's old course guide

A Piezo is nothing but an electronic device that can both be used to play tones and to detect tones. In our example we are plugging the Piezo on the pin number 9, that supports the functionality of writing a PWM signal to it, and not just a plain HIGH or LOW value.

The first example of the code will just send a square wave to the piezo, while the second one will make use of the PWM functionality to control the volume through changing the Pulse Width.

The other thing to remember is that Piezos have polarity, commercial devices are usually having a red and a black wires indicating how to plug it to the board. We connect the black one to ground and the red one to the output. Sometimes it is possible to acquire Piezo elements without a plastic housing, then they will just look like a metallic disc.
