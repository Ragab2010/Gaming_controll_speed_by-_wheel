# Gaming_controll_speed_by-_wheel

connect an exercise bike to a PC to use for interactive exercise.

I have already got a USB programmable input device which uses native HID drivers the input reads switch events and can emulate a key or a button press for different input devices on a PC i.e. keyboard, mouse or games pad.

I did do a similar project many years ago using RS232 input but since all modern computers have gone USB it is now all but redundant. As I have this USB input I am wanting to do a USB version of my original project.

The original project used information from a reed switch attached to the bike this could calculate speed if you measured the time between each switched event which corresponded with a 360° turn of the crank shaft. The purpose of the PIC was to calculate how fast I was cycling then output (emulate) switch events which were to be put out in quick succession based upon a formula for my cycling speed this was then converted to a series of up arrow's on a keyboard stopping and starting to emulate acceleration or speed of a character in a PC video game. The character could be an avatar, a motorcar, motorbike, aeroplane etc.

The purpose of this was to make exercise interactive and interesting.

this project. The new USB input can emulate a PC gamepad so no longer do I require to use the up arrow but instead emulate a press of the controller on a PC gamepad. 
