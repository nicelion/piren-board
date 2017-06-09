# piren-board
GERBER and Fritzing files for a PCB for the Piren Project


[Piren](www.github.com/nicelion/piren) is an open source project for Raspberry Pi. With Piren, you can turn your Pi into a siren box and horn box for your car. In this repository, you can find the GERBER files if you'd like to have a PCB made. 

Please note, I am **NOT** an electrical engineer. So, this PCB is not beautiful as it's my first one, but feel free to fork it, and improve it!


# Hooking it up to your Pi

Hooking it up to your Pi is very easy. You'll notice at the top of the PCB, there is place for 12 pin headers. Solder the pin headers on. 

Once soldered on, you can now connect the Pi's GPIO pins to the pins on the PCB. Follow the table below:

| Function | GPIO Pin # | Pin # on PCB |
| :---         |     :---:      |          ---: |
|  Siren LED  | 12     | 1   |
| AUX LED     | 20     | 2 |
|  AUX BTN    | 26     | 3  |
| Loop        | 25     | 4 |
|  Horn       | 24     | 5   |
| Phaser/Piercer    | 18     | 6 |
|  Yelp        | 5     | 7   |
| Manual Wail  | 27     | 8 |
|  Previous    | 9     | 9   |
| Next         | 17     | 10 |
|  Next Brand  | 11     | 11   |
| Previous Brand     | 8     | 12 |

Also, you'll notice a place for two pin header labeled as "power". Connect the positive to the 3.3v GPIO pin, and the negative to a ground pin.

You will also notice 2x6 pins toward the bottom of the board. These have no function in the current version of Piren, they are just there in case an idea is thought of.  
