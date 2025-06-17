---
layout: page
permalink: /camera/
title: Camera Control
description: Camera Control Documentation
nav: false
---
The science camera is an Andor iKon-M 934 ccd named Evora. It's typically controlled from the left-hand computer using the Camera Control webpage. [The Checklist](checklist/) steps you through initialization, operation. Remember to shut down the camera at the end of each night.

### Things to Know
The Camera Control software is under active development. At this time you should expect the following known issues:

- Images display zoomed in at first. Zoom out or zoom to fit to see the entire field.

- Multiple tabs do work, but do not expect the camera to do two things at once.

- Every image is saved in a data directory the is assessible, on Sleipner, at [http://localhost/data/ecam](http://localhost/data/ecam).

### Troubleshooting

Evora and the Camera Control software have been fairly reliable, but in case of trouble restart the server on Sliepner with:

`$ sudo systemctl restart evora-server`
