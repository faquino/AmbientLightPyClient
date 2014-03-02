AmbientLightPyClient
====================

This is a Python Qt client application I wrote that connects to the [https://github.com/waldobronchart/AmbiLightServer](AmbiLightServer), which in turn drives the Ambient Light rig I built. The server captures colors from the TV using a webcam, then samples colors at the edge of the screen and updates a bunch of LEDs at the back of the TV with those colors.

The sampling region and other camera color settings can be controlled by this client. It connects up to the server via the network to receive the webcam feed and send camera settings back to the server.

A video of the project and details on how I built it can be found on my blog: 

* [http://waldobronchart.be/639/ambient-light-tv-with-a-raspberry-pi-part1/](http://waldobronchart.be/639/ambient-light-tv-with-a-raspberry-pi-part1/)
* [http://waldobronchart.be/719/ambient-light-tv-with-a-raspberry-pi-and-camera-part2/](http://waldobronchart.be/719/ambient-light-tv-with-a-raspberry-pi-and-camera-part2/)

Screenshots
----------------------------------------

![alt text](http://i.imgur.com/Ml03Ksz.png)
