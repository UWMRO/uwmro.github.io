---
layout: page
permalink: /telescope/
title: Telescope Control
nav: false
---

The 30" is driven in RA and Dec by a [Sidereal Technology](https://siderealtechnology.com/) F1 Controller, which is controlled by the Windows computer in the dome. This computer runs SiTech.exe, which is typically accessed using remote desktop software from the right-hand computer in the control room. Telescope focus is controlled from the [Camera Control](../camera) webpage. The steps to initialize and operate the telescope are described in [the Checklist](../checklist/). Note that the telescope starts tracking *automatically* upon initialization to zenith or slewing to any object.

Notes on SiTech.exe: 
- The Scope tab has a button for the SkyView window and display current paddle speed in the *Mode* box: SLEW, PAN, or GUIDE.
- The Numbers tab displays LST, as well as altitude and azimuth
- Goto Sync tab allows the entry of an arbitrary RA & Dec. Note that you'll likely want to check the J2000 checkbox.
- Other operations (e.g. slewing to named objects) are performed in the SkyView window. 

Notes on SkyView: 
- Zoom1 zooms out to the entire visible sky.
- Right-click allows you to move to any arbitrary ("random") area.

### Troubleshooting

The F1 will disable the telescope if any error occurs, such as hitting the horizon limit--which cuts power to the motors--or an over-current on either axis. If this happens, the F1's status light for the axis blinks, SiTech.exe reports "Motors In Blinky", and the axis will need to be reset. To reset the axis:

- Navigate to the Features tab in SiTech.exe.
- Click *Controller Stuff* to open the Controller Information Window. In the example shown below, motors are disabled due to a Dec axis overcurrent error.
- Click *Reset Errors* on the appropriate axis.
- Click *Motors to Auto*.

![SiTech.exe Controller Information Window](../../assets/img/ControllerInfoWindow.png)
