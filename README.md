# HopperHawk
### Overview
HopperHawk is a simple sensor designed to measure how full the hopper of your pellet smoker is. The code in this repository is intended to be used on custom designed hardware ([which is still under development, but will be able to be purhcased here](https://sidelinedata.com)). The board I have designed is based around the ESP32 and uses an Ultrasonic Sensor to capture the measurements. 

After an initial calibration (measuring the hopper empty and full) you should be able to leave HopperHawk inside your hopper and use it with little intervention. The board contains a rechargeable battery and should last long enough to get through any smoking session.

Check out the Wiki in this repository for detailed information on requirements, setup, and general usage!

### Connectivity
HopperHawk will connect to your home WiFi network and you are able to communicate with it a few different ways:

- Mobile App (currently in development)
- API calls directly to the device (see documentation)
- MQTT (for use in something like Home Assistant)



## Status
This project is under active development and as of 03/09/2024 I have a new round of hardware that I am actively testing. The goal is to open up pre-ordes in the next few weeks and get the mobile app published to the app store! For more detailed updates, [be sure to sign up on the website and check out the blog :)](https://sidelinedata.com/blogs/hopperhawk-1)


