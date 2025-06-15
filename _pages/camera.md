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

- Images display in JS9 zoomed in at first--remember to zoom out to see the entire field.

- Once you start exposing the page will essentially freeze. Commands and temperature updates won't work at first, but they are queued for when the exposure is finished. We recommend timing long exposures so you know when they'll end.


### Troubleshooting

Restart the Evora server with:

`$ sudo systemctl restart evora-server`
