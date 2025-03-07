# Coda88_Eurorack_Module
An eurorack adaption of the Coda88 sampler by Sandrolab

![IMG_3320](https://github.com/user-attachments/assets/b91c0414-67f6-498e-a212-05caa63e5c23)


Differences compared to the original version:
- Removed onboard amp (line out output for eurorack usage)
- Removed release and damper pedal sounds
- 6 instruments: Grand Piano, DX7 Electric Piano 1, Fender Rhodes, Wurlitzer, Korg M1 Organ 2, Pink Floyd Echoes Piano 
- Added switch for instrument selection
- Powered by eurorack 10-pin connector (no need for external DC-DC converter)

Demo video: 

### Features:
- Stereo 44.1 KHz 16 bit CD quality audio
- 6 Instruments: Grand Piano, DX7 Electric Piano 1, Fender Rhodes, Wurlitzer, Korg M1 Organ 2, Pink Floyd Echoes Piano 
- 14 notes polyphony
- MIDI In
- 
### Samples
Samples are from http://pianobook.co.uk, sampled with AutoSampler on Logic.

[Grand Piano]((https://www.pianobook.co.uk/packs/the-experience-fazioli-f308/))
[DX7 Electric Piano 1]((https://www.pianobook.co.uk/packs/e-piano/))
[Rhodes](https://www.pianobook.co.uk/packs/matts-fender-rhodes/)
[Wurlitzer](https://www.pianobook.co.uk/packs/baltiwurli/)
[Korg M1 Organ 2](https://www.pianobook.co.uk/profile/antonjacobsson/)
Pink Floyd Echoes Piano -> Same as grand piano, run through Logic rotary cabinet at max speed


## Overview

Schematics are available in the repo

## BOM
- 1 x Robertsonics/Sparkfun WavTrigger board (the first version)
- 1 x SD Card (I used a 16 GB one)
- 1 x Arduino Nano
- 2 x 3.5mm female mono jacks (Out L, Out R)
- 1 x 3.5mm female stereo TRS jack (MIDI In, a standard 5 pin din can be used as well)
- 1 x NC momentary push button
- 1 x 6N138 Optocoupler
- 2 x 220 Ohm Resistor
- 1 x 4.7KOhm Resistor
- 7 x 470 Ohm Resistor
- 1 x 1N4148 Diode
- 7 x 3mm LEDs (I used 6 green LEDs and 1 red LED)

Thanks to:

- [sandrolab]((https://github.com/sandrolab)) , for the original project
- [pianobook.co.uk](pianobook.co.uk) and its users for the samples
