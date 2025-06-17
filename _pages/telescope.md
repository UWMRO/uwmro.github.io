---
layout: page
permalink: /telescope/
title: Telescope Control
nav: false
---

Our telescope is driven in RA and Dec by a [Sidereal Technology](https://siderealtechnology.com/) F1 Controller, the user interface of which, SiTech.exe, runs on the Windows computer in the dome. We typically access this computer using remote desktop softwarefrom the right-hand computer in the control room. Many operations are performed in the SkyView window. Focus is controlled from the [Camera Control](../camera) webpage. The steps to initialize and operate the telescope are described in [the Checklist](../checklist/). 

Notes on SiTech.exe: 
- Scope tab displays paddle speed in the `Mode` box (SLEW, PAN, or GUIDE)
- Numbers tab displays LST, as well as altitude and azimuth
- Goto Sync tab allows the entry of an arbitrary RA & Dec, be sure to click the J2000 checkbox as appropriate.

Notes on SkyView: 
- Zoom1 zooms back out
- right click allows you to move to any arbitrary ("random") area

### Troubleshooting

The F1 will disable the telescope if any error occurs, such as an over-current on the RA or Dec axis. If this happens, the F1's status light for the axis blinks, SiTech.exe reports "Motors In Blinky", and the axis will need to be reset. To reset the axis:

- Navivate to the Features tab in SiTech.exe.
- Click *Controller Stuff* to open the Controller Information Window.
- In that window, click *Reset Errors* on the appropriate axis. In the example below, the Dec axis has an overcurrent error.
- Click *Motors to Auto*.

![SiTech.exe Controller Information Window](../../assets/img/ControllerInfoWindow.jpeg)

