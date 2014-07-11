****************************************************************************
  dp.kinect - a Cycling 74 Max Jitter external for Kinect based on the Microsoft Kinect SDK

  Copyright (C) 2012-2014 Dale Phurrough

  dp.kinect is distributed WITHOUT ANY WARRANTY; without even the implied
	warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
****************************************************************************

Full setup and documentation is available at the wiki https://github.com/diablodale/dp.kinect/wiki

Most recently written and tested using:
- Windows 8.1 64-bit
- Microsoft Visual C++ 2012 Express Version 11.0.61030.00 Update 4
- Microsoft Kinect SDK v1.7
- Max/MSP/Jitter 6.1.7 for Windows
- Max/MSP/Jitter SDK 6.0.4 for Windows

Quick Notes
============

* It is based on the Microsoft Kinect SDK/Runtime. You need v1.5.2 or greater to use this external.
* It supports multiple Kinects on the same PC.
* It was developed and tested against Max 6. Earlier versions may work but are not widely tested.
* Read the wiki https://github.com/diablodale/dp.kinect/wiki
* It has the same inlets and outlets as compared to my other external jit.openni. You can retype
  dp.kinect in the same max patcher box and quickly migrate to this external.
  All output is supported and should be equivalent except the orientation of joints is optionally
  available after the confidence value on the same message.
  It is in your choice of two formats: quat or 4x4 rotation matrix
* Many of the attribute names have changed as compared to jit.openni. However, you will find
  that there is usually an exact equivalent for an attribute you previously used. This change
  is intentional.
* Did you read the wiki https://github.com/diablodale/dp.kinect/wiki?

Known Issues
============

* I request you report any issues at https://github.com/diablodale/dp.kinect/issues

Licensing and Terms of Use
==========================

The dp.kinect software is free to use for a limited 14 day trial evaluation period. For all other
uses, including commercial applications, you need to arrange for a license by visiting
http://hidale.com/dp-kinect/.

If you want to license dp.kinect before the online store is available, please email dale@hidale.com.
Other than those rights granted with a license, the following applies.

This software comes with ABSOLUTELY NO WARRANTY. Unless otherwise specified, this software is only
for your evaluation and non-commercial use. You may not modify, distribute, transmit, publish,
license, decompile, create derivative works from, transfer, or sell any information, software,
products or services obtained from or with the use of this software. I reserve the right to update
these terms at any time during the beta period. The most current version of these terms can be
viewed on this same web page.

I do support creative endeavors and artists. I am an artist myself. As such, I believe that artists
should be compensated for their work. No starving artists! When an artist builds on the work of
another, I believe that one artist should recognize the other. That recognition can come in many
forms (e.g. attribution, compensation, or a beer). The license is simply the means to formalize
that recognition in a durable way.

Here are examples which will need paid licenses
* Installation artist creating a work for a exhibition
* VJ performing in a local club
* Education class, university, or research
* Bundled as part of a software solution sold to multiple customers
* Used in the touring show of a performer, band, or DJ
* Used in an presentation or installation for an outside environment

Installation and Documentation
==============================

Documentation for dp.kinect is available at the wiki https://github.com/diablodale/dp.kinect/wiki,
in the descriptive information readily available in the Max inspector for dp.kinect, or implied
with the usage examples in the included demo patcher.

The registration key (trial.dpreg) included with this download grants you the 14 day trial
evaluation period.

You can download the current version at http://hidale.com/dp-kinect/#download
