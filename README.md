# Raspberry Pi Flask based Camera Server

This repository provides a light Flask server which can be deployed on a Raspberry Pi.

The sever can handle HTTP requests and return the current image from the camera.

The webapp is also able to handle multiple requests by means of multithreading, and is also able to reduce power consumption by turning off the camera after long periods of inactivity.

I am currently looking to extend the functionality of this repository, and thus feel free to make a pull request.
