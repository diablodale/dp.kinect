dp.kinect http://hidale.com/dp-kinect/
=========

Cycling 74 Max external using Microsoft Kinect SDK

I have released a BETA of dp.kinect; an external which can be used within the
Cycling '74 Max development environment to control and receive data from your Microsoft Kinect.

* It is based on the Microsoft Kinect SDK v1.5.
* It will support multiple Kinects on the same PC.
* It was developed and tested against Max 6.0.7. It is untested against earlier versions.
* There is good compatibility with the output of the external as compared to my other external jit.openni. All output is supported and should be equivalent except the IRmap; raw infrared is not exposed by the Microsoft SDK v1.5. Additionally, the colormap is not yet supported by the Beta.
* Many of the attribute names have changed as compared to jit.openni. However, you will find that there is usually an exact equivalent for an attribute you previously used. This change is intentional.

Known Issues
============

* Multiple Kinects on the same PC is not yet implemented.
* Colormap output is not yet implemented.

Licensing
=========

dp.kinect is free for evaluation and non-commercial use. For all other uses, including commercial
applications, you need to arrange for a license. During the Beta period, there are only no-cost licenses.﻿﻿

I do support creative endeavors and artists. I am an artist myself. As such, I believe that artists
should be compensated for their work. No starving artists! When an artist builds on the work of another,
I believe that one artist should recognize the other. That recognition can come in many
forms (e.g. attribution, compensation, or a beer). The license is simply the means to formalize that
recognition in a durable way.

Here are examples which will likely be granted a no or low-cost license:

* Installation artist creating a work for a private gallery
* VJ performing in a local club

Here are examples which will require a paid license:

* Bundled as part of a software solution sold to multiple customers
* Used in the touring show of a performer, band, or DJ
* Used in an presentation or installation for an outside environment

Installation and Documentation
==============================

During the Beta period, there is little documentation specific to dp.kinect.
I recommend you reference the documentation for jit.openni and look a the descriptive
information in the Max inspector. The output of the external should be equivalent to jit.openni.
Any difference is a bug and I request you report it at https://github.com/diablodale/dp.kinect/issues

The externals available in the Beta has a limited lifespan; typically 4 weeks from the release date.
The intention is to encourage frequent updating and feedback during the Beta period.

Current Beta version is v0.3.9 with an expiration date of 1 Oct 2012.
Download is at https://github.com/diablodale/dp.kinect/downloads


