# led-control

This program utilizes the [rpi-rgb-led-matrix](https://github.com/hzeller/rpi-rgb-led-matrix) library (among others) to create and control animations on an LED matrix. This is meant to run on a Raspberry Pi or similarly capable SBC.

The [input_receive](https://github.com/Masieono/input-receive) module sends inputs as serial data to led_control via either a wired serial connection or wireless bluetooth. 

This data is then used to generate animations on the LED screen. 
