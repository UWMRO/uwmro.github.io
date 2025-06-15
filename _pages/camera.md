---
layout: page
permalink: /camera/
title: Camera Control
description: Camera Control Documentation
nav: false
---
Evora is the name of our Andor iKon-M 934 imaging camera. The Checklist steps you through operation. Remember to initialize the camera and home the filter wheel at the beginning of your session, and shutdown the camera at the end.

### Things to Know
The Camera Control software is under active development. At this time you should expect the following known issues:

- Images display zoomed in at first. Zoom out or zoom to fit to see the entire field.

- Multiple tabs do work, but do not expect the camera to do two things at once.

- Every image is saved in a data directory assessible on Sleipner at [http://localhost/data/ecam](http://localhost/data/ecam).

### Troubleshooting

Restart the Evora server with:

`$ sudo systemctl restart evora-server`
