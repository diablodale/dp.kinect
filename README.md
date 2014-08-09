****************************************************************************
  dp.kinect - a Cycling 74 Max Jitter external for Kinect based on the Microsoft Kinect SDK

  Copyright (C) 2012-2014 Dale Phurrough
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

* The 3D coordinates for facetracking are not rotated by gravity or elevation of the Kinect. This feature will be added in a future release.
* I request you report any issues at https://github.com/diablodale/dp.kinect/issues

Licensing, Terms of Use, Conditions, and Warranty
==============================

Please visit http://hidale.com/terms/ for all licensing, terms of use, conditions, and warranty information.

Installation and Documentation
==============================

Documentation for dp.kinect is available at the wiki https://github.com/diablodale/dp.kinect/wiki,
in the descriptive information readily available in the Max inspector for dp.kinect, or implied
with the usage examples in the included demo patcher.

The registration key (trial.dpreg) included with this download grants you a 14 day trial period.

You can download the current version at http://hidale.com/shop/dp-kinect/#download
