# water-boatman
A small chiptune synthesizer

## Description

Initially consisting of an Attiny85
microcontroller connected to a piezoeletric
buzzer, the first version of the water boatman
chiptune synthesizer will output 8-bit sounds.

## Mechanism

The piezo buzzer will be connected directly to
a PWM port of the Attiny85 which will receive
square wave 5V signals with a variable width.

## Buzzer

The [Buzzer](https://en.m.wikipedia.org/wiki/Buzzer)
is a piezoelectric device that converts audio
electric signals in audio mechanic signals.
Thanks to Helmholtz effect, it is possible.
By variating the electric signal, its possible
to change the output audio frequency's, creating
music 🎵.

## Power source

The power soucer will be a 3V CR2032 or small lithium
battery. The Attiny will be underclocked to run with
voltages less than 5V consuming small amounts of power.
Probably, there will be a need to a voltage converter/
stabilizer.

### Putting Attiny85 in low-power mode

[Hardware and Software mods](https://wiki.liutyi.info/display/ARDUINO/Low+power+projects+digispark+ATtiny85+modification)
