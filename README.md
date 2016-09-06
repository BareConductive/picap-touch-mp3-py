[![Bare Conductive](http://bareconductive.com/assets/images/LOGO_256x106.png)](http://www.bareconductive.com/)

# Bare Conductive Pi Cap Polyphonic Touch MP3 Utility

Example MP3 playback code for the [Bare Conductive Pi Cap](http://www.bareconductive.com/shop/pi-cap/). You need twelve MP3 files named TRACK000.mp3 to TRACK011.mp3 in a folder called `tracks` inside this folder. When you touch electrode E0, TRACK000.mp3 will play. When you touch electrode E1, TRACK001.mp3 will play, and so on. Playback is polyphonic, which is nice.

    picap-touch-mp3-py    
    │
    └──tracks
         TRACK000.mp3    
         TRACK001.mp3  
         TRACK002.mp3  
         TRACK003.mp3  
         TRACK004.mp3  
         TRACK005.mp3  
         TRACK006.mp3  
         TRACK007.mp3  
         TRACK008.mp3  
         TRACK009.mp3  
         TRACK010.mp3  
         TRACK011.mp3  

## Requirements
* Requires [python-dev](https://www.python.org/) (`apt-get install python-dev`)
* Requires [WiringPi](http://wiringpi.com/) (`apt-get install wiringpi`)
* Requires [Bare Conductive's MPR121 libary for WiringPi](https://github.com/BareConductive/wiringpi-mpr121)
* Requires [python-pygame](http://www.pygame.org/download.shtml) (`apt-get install python-pygame`)

## Install / Build

* You should install this code as part of the Pi Cap Raspbian package: `sudo apt-get install picap`    
* However, if you are doing this yourself, clone the repository and follow the usage instructions.

## Usage

    python touch-mp3.py

N.B. must be run as root    
