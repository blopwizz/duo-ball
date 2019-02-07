# duo-ball

A ball bouncing between two mobile screens.

How to play with it:
* Get 2 iPad with rotation lock in landscape mode. Open the page https://ball-duo.glitch.me/client_left.html with the device on the left, and the page https://ball-duo.glitch.me/client_right.html with the device on the right.
* touch the screen one time to have the sound activated (safari mobile browser protection against intrusive ads)

Features:
* physics simulation for collision, bounce and gravity
* device motion for web mobile browsers (won't work on devices without accelerometer sensor like a PC)
* ball crossing between the two screens (real time handled by a websocket js event library called socket.io)
* cross platform, just works in the browser
* bounce sound handled by audio js library Howl

#TODO :
* get the code from glitch and implement a local version
* connection screen to choose which side is displayed
* adapt to all orientation and all device
* fullscreen or progressive web app integration

#DONE : 20181118 01:52 - constant parameters for RIGHT and LEFT clients – one js file to rule them all ...
