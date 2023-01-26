# led-control

Firmware for the ESP32 as an input-receiver module on a Eurorack system. The ESP is mounted onto a 10-12hp rack module that accompanies: 
- 3 gate inputs
- 3 CV inputs
- stereo audio (or two separate audio signals)
- USB (for loading image/gif files)
- Program selection for the led_control

The input_receive module sends these inputs as serial data to led_control via either a wired serial connection or wireless bluetooth. 
This data is then used to generate animations on the LED screen. 

