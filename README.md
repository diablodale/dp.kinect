****************************************************************************
  dp.kinect - a Cycling 74 Max Jitter external for Kinect based on the Microsoft Kinect SDK

	Copyright (C) 2011-2013 Dale Phurrough
	All rights reserved except for those documented in the dp.kinect terms at http://hidale.com.
	dp.kinect is distributed WITHOUT ANY WARRANTY; without even the implied
	warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

	Includes some derivative work which was originally
	Copyright (C) 2013 Microsoft Corporation
	Licensed under the Apache License, Version 2.0 (the "License");
	you may not use this file except in compliance with the License.
	You may obtain a copy of the License at
		http://www.apache.org/licenses/LICENSE-2.0
	Unless required by applicable law or agreed to in writing, software
	distributed under the License is distributed on an "AS IS" BASIS,
	WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
	See the License for the specific language governing permissions and
	limitations under the License.
****************************************************************************

Full setup and documentation is available at the wiki https://github.com/diablodale/dp.kinect/wiki

Most recently written and tested using:
- Windows 8 64-bit
- Microsoft Visual C++ 2012 Express Update 3
- Microsoft Kinect SDK v1.7
- Max/MSP/Jitter 6.x for Windows
- Max/MSP/Jitter SDK 6.1.3 for Windows

Quick Notes
============

* It is based on the Microsoft Kinect SDK. You will need at least v1.5.2 to use this external.
* It supports multiple Kinects on the same PC.
* It was primarily developed and tested against Max 6.x. It has only been casually tested against Max 5.1.9.
* Read the wiki https://github.com/diablodale/dp.kinect/wiki
* It has the same inlets and outlets as compared to my other external jit.openni. You can retype dp.kinect in the same max patcher box and quickly migrate to this external.
All output is supported and should be equivalent except the following two:  
1) orientation of joints is optionally available after the confidence value on the same message. It is in your choice of two formats: quat or 4x4 rotation matrix  
2) Many of the attribute names have changed as compared to jit.openni. However, you will find that there is usually an exact equivalent for an attribute you previously used. This change is intentional.
* Did you read the wiki? You really should read the wiki https://github.com/diablodale/dp.kinect/wiki

Known Issues
============

* I request you report any issues at https://github.com/diablodale/dp.kinect/issues

Licensing and Terms of Use
==========================

The dp.kinect software is free for evaluation and non-commercial use. For all other uses,
including commercial applications, you need to arrange for a license. **During the Beta period,
there are only no-cost licenses.** The software also has a limited lifespan (approximately 30 days)
to encourage feedback and frequent updating during the beta period. Some individuals/organizations
have been provided private builds and granted specific limited rights. Other than those
rights and/or grantees, the following applies.

This software comes with ABSOLUTELY NO WARRANTY. Unless otherwise specified, this software is
only for your evaluation and non-commercial use. You may not modify, distribute, transmit,
publish, license, decompile, create derivative works from, transfer, or sell any information,
software, products or services obtained from or with the use of this software. **I reserve the
right to update these terms at any time during the beta period. The most current version of
these terms can be viewed on this same web page.** And...relax...I will be generous as time goes forward.

I do support creative endeavors and artists. I am an artist myself. As such, I believe that
artists should be compensated for their work. No starving artists! When an artist builds on
the work of another, I believe that one artist should recognize the other. That recognition
can come in many forms (e.g. attribution, compensation, or a beer). The license is simply
the means to formalize that recognition in a durable way.

Here are examples which will likely be granted a no or low-cost license after the beta period:

* Installation artist creating a work for a private gallery
* VJ performing in a local club

Here are examples which will likely require a paid license after the beta period:

* Bundled as part of a software solution sold to multiple customers
* Used in the touring show of a performer, band, or DJ
* Used in an presentation or installation for an outside environment

Installation and Documentation
==============================

Documentation for dp.kinect is available at the wiki https://github.com/diablodale/dp.kinect/wiki,
in the descriptive information readily
available in the Max inspector for dp.kinect, or implied with the usage examples in the included
demo patcher.

The externals available in the Beta has a limited lifespan; typically 4 weeks from the release date.
The intention is to encourage frequent updating and feedback during the Beta period.

You can download the current beta at
http://hidale.com/dp-kinect/#download
