# Bandwidth Dragon

This article is currently WIP

Once upon a time a store called Spencers Gifts existed. I think it probably still does, but malls don't exactly exist in my mind anymore. When I was a teenager, I was a bit of a mall rat due to an addiction to [Pump It Up](https://en.wikipedia.org/wiki/Pump_It_Up_(video_game_series)). Since I had a (small) disposable income as a teenager with a job and a car, I had the pleasure to buy strange things. I am also a bit of a nerd, so I got a dragon lamp.

I used to take this thing to a local LARP (yeah, that much of a nerd) and hang it on the wall as a mood light.

Here's a photo of the dragon today:

![Dragon](img/dragon.jpg){ width="600" }

One thing to note, the lamp part of this dragon is completely redone. I wanted an art project to flex my creative bone and that's what this project is about.

## What is it?

I found this dragon in a box when moving into my new house. After opening the globe-like lamp to replace the bulb, a thought went through my mind. "Why would you use a tiny christmas light in this thing?" A friend introduced me to [neopixels LED's](https://www.adafruit.com/product/1138?length=2) in the past and I wanted to use one to make this globe really shine.

## Hardware

I needed a way to use a raspberry pi zero w and a neopixel ring together. Because +5V is native to the raspberry pi, the 3V data path the neopixel ring operates on requires a level stepper to accomplish and properly address each light in the array. Lucky for me, the chip shortage didn't start yet so I got a few from adafruit.

Build requirements:

 - 74AHCT125 - Quad Level-Shifter (3V to 5V) (1)
 - 5V 4A (4000mA) switching power supply
 - NeoPixel Ring - 12 x 5050 RGB LED with Integrated Drivers
 - Breadboard
 - Flux
 - Solder
 - Soldering Iron

Once I had all the hardware, the wiring was pretty simple:

![Wiring](https://cdn-learn.adafruit.com/assets/assets/000/064/121/original/led_strips_raspi_NeoPixel_Level_Shifted_bb.jpg?1540314807)

From: <https://learn.adafruit.com/neopixels-on-raspberry-pi/raspberry-pi-wiring>
