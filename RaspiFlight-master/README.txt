===============
  RaspiFlight
===============

Part of a flight controller module for the RaspberryPi. Manages a GPS module, Barometric/Altitude/Temperature sensors, and a camera module.

---------------
     v0.30
---------------
-RaspiFlight.py
  -Added GPS to UI

-GPS.py
  -Removed test code

---------------
     v0.25
---------------
-RaspiFlight.py
  -Made as entry point to the program
  -Created interface to display program output

-piCam.py
  -Changed from a class to a script to enable usage by RaspiFlight.py
  -renamed to PiCam.py
  
-BMP.py
  -general bug fixes and some cleanup of the code

---------------
     v0.01
---------------
-Attached program to Adafruit library for use of the Sensors on the Barometer module

-RaspiFlight
        Added
        Will later make use of as the "main" point of entry into the program

-BMP.py
        Initializes the sensors on the Barometer and can make calls to get
        Temperature (In C), Altitude (approximate), and Pressure

-piCam.py
  -Added function to parse .conf file
  -Executes both Stills and Video

-PiCamConfig.py was removed. Not worth the effor to implement right now.
  Just configure the .conf manually. Instructions are inside of the file.
