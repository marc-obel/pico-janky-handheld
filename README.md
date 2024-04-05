# pico-janky-handheld
A janky PICO 8 handheld console for people with limited experience with electronics and hardware.

This is a quick first draft of the idea. A square display with 3x mx style switches on each side.
<img width="857" alt="image" src="https://github.com/marcentusch/pico-janky-handheld/assets/14914250/af5d0b8e-2a7e-4835-86a6-c1ec021b00bf">

## Parts
- 4" square display. I will be using this one from Pimoroni: https://shop.pimoroni.com/products/hyperpixel-4-square?variant=30138251477075
- Raspberry Pi. I will be using a Pi 3 since that is what I have. Pico 8 does
- Raspberry Pi Pico. The display uses all the GPIO pins on the normal Raspberry Pi so the 6 buttons for input will actually just function as a tiny keyboard that will be plugged into the Pi
- Power Bank that can provide reliable power for raspberry pi. This is the JANKY part of this build, I don't want to think about power so my plan is to just use a power bank that will be external to the actual handheld.
- 6x mx style switches
- 6x keycaps
- Wire for handwiring the switches to the Pico
