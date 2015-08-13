#Learning About Sensors
You've probably heard about the Internet of Things, or IoT. In a nutshell, IoT describes all sorts of "things" networked and connected via the internet. Lots of these "things" have, or are, sensors. This could be something like a motion detector that turns on a networked security camera, or a soil moisture sensor that sends readings to a server that controls an irrigation system, or a temperature sensor that sends out an alert when a freezer breaks and warms up.

This activity will show you some basics about sensors using an Arduino board and a couple of sensors with LED outputs. And at the end, you'll have a chance to win a prize!

##What are we playing with here?
What we have at this station is an Intel Edison using an Arduino breakout board. If you did the Programming 101 activity, you know about Arduino - it's an open-source hardware project that's used by lots of makers for their projects. One of the great things about Arduino is that there is tons of compatible hardware that can work with it. What we have on top of the Edison is an Arduino shield -- an add-on board that brings new functions. This shield is called an "ArduSensor", and it's designed to make working with sensors easy.

##How does it work?
The ArduSensor has 4 spots to connect sensors. These are the black headers on the board, labeled ArduSensor A0-A3. It also has an RGB LED, a buzzer, and an LED bar graph display, which you can use to visualize (or hear) the sensor readings. In this activity, we'll use two sensors:
- a light sensor, that detects the amount of light
- a force sensor, which is a touch sensor that detects the force of a touch

##You try it!
There should be a program running on the Edison and ArduSensor already, but go ahead and hit the Reset button in the upper right corner of the ArduSensor, and gently pull out any sensors that are attached to it. It should look like this:

[ArduSensor](ardusensor1.jpg)


