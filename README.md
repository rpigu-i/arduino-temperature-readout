# arduino-temperature-readout
Simple code for reading out the Temperature and Humidity via a web server on Arduino

Brought to you by rpigu-i: https://github.com/rpigu-i/arduino-temperature-readout

# Background 

The code in this repository supports the blog post on building smart thermostats at:

https://iothome.org/2012/10/18/thermostats-part-2-the-ethernet-model-prototyping/

This is an older blog post from 2012, so many of the techniques and hardware may have been superceded in the past
 10 year. As a result the project is now archived, but may still prove useful for learning.

At the time this was written it was also forming part of a set of broader research topics to support the writings in:

https://www.packtpub.com/product/raspberry-pi-home-automation-with-arduino/9781849695862


# Hardware Required

The blog post and this code requires/was tested on:

1. Arduino Uno

2. Temeprature sensor

3. Visual display unit

4. Ethernet shield

5. Buttons/manual method of input

6. Power supply

7. Ethernet cable

8. Relays

In the case of these components, look for whatever the latest are on the market.


## Pins used

* Ethernet shield attached to pins 10, 11, 12, 13
* Analog inputs attached to pins A0 through A5 (optional)

# Software

The code runs on port 80. This can be changed on line `42`

To run the code, upload it to your Arduino via the IDE.
