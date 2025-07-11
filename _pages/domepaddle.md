---
layout: page
permalink: /domepaddle/
title: Dome Paddle
nav: false
---
The dome paddle is an Xbox 360 controller that operates the dome. Currently it does *not* control the telescope, but it does control the dome:

![Dome Paddle button assignments](../../assets/img/DomePaddle.png)

The triggers enable motion. Hold the right trigger to enable dome motion.

### Troubleshooting
If the Xbox controller doesn't light up at all, new batteries are located in the dark room. =)

If it lights up but nothing responds, it's possible the Xbox controller has to be paired again with the receiver. To pair, find the circular black button on the top of the wireless receiver for the Xbox controller (a black device just inside the yellow base of the telescope; should say 'Microsoft' on it) and the tiny circular black button on the front of the controller itself. These must be pressed and HELD at the SAME time (the green lights on the receiver and controller should start flashing). Keep them pressed until the lights stop flashing (and possibly the Xbox controller's green light is located at the top left of the silver 'X' button--but possibly that just indicates the state of the battery).

### How it works

 The Xbox controller communicates wirelessly to an Arduino via a wired (usb) Xbox receiver. The Arduino is wired to the telescope and (via a relay board) to the dome control box. Code is available [on github](https://github.com/UWMRO/TCC/tree/master/dome_paddle). Dome rotation from the control room paddle has been disabled.

Not implimented yet: ~~the speed of the telescope's motion can be adjusted between "set" (slow) and "slew" (fast) using the two buttons on either side of the On button, but note that the position of the Set/Slew switch on the control room paddle may take priority.~~
