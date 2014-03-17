raspio-breakout-pro
===========

https://github.com/raspitv/raspi-breakout-pro


RasPiO® Breakout Pro Python scripts

By Alex Eames http://RasPi.TV

These scripts go with the RasPiO® Breakout Pro board
http://rasp.io/breakoutpro


Preparation
-----------

Connect a wire from each port to an led (long leg, +ve side).
Connect the other end of the LED to GND.

With the RasPiO Breakout Pro, you don't need a resistor for your LED as there is already one on the underside of the board.

Do this for each port with a GPIO number (17 altogether). Then you are ready to test the ports.


Contents
--------
With these scripts you should be able to...


port-test.py       - up and down pattern, increasing speed
port-test-pwm1.py  - brighten and dim the leds in succession
port-test-pwm2.py  - brighten and dim alternate sides
port-test-pwm3.py  - brighten and dim alternate groups of leds


Have fun connecting things to your Raspberry Pi


