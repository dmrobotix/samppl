---
layout: post
title:  "Slug Wars -- Prototyping Checkoff"
date:   2015-11-17 11:20:10 -0800
categories: samppl update prototype foamcore mdf solidworks boards sensors drivers
---

Please review the following images, videos, and links for this week's checkoff.

__SolidWorks Model__
------
We modeled the basic chasis in SolidWorks. Below, you can see in the drawings the three levels with the beacon detector and with a first iteration of our bumpers. We have since made modifications to the bumpers (which you can see below). The new bumpers are modeled in SolidWorks but have not been added to the full assembly.

|-----------------+------------|
| [![Isometric Right View]({{site.baseurl}}/images/isorightview.png)][isoright] |[![Right View]({{site.baseurl}}/images/rightview.png)][right]|
|-----------------|-----------|
| Isometric View      | Right View  |
| [![Rear View]({{site.baseurl}}/images/rearview.png)][rear]  | [![Top View]({{site.baseurl}}/images/topview.png)][top]  |
| Rear View  | Top View   |
|-----------------+------------|

__Foamcore Prototype__
------
[![Foamcore Prototype]({{site.baseurl}}/images/foamcore-robot.jpg){:width="300px"}][foamcore]

__Working Bumper Prototype (Foamcore)__

Please watch the video to see our bumper prototype in action.
<iframe width="420" height="315" src="https://www.youtube.com/embed/73b4YhN_Y6I" frameborder="0" allowfullscreen></iframe>


__Perf-boarded sensors and regulators__
------

|----------------+------------+-----------------|
|[![Track Wire Detector]({{site.baseurl}}/images/trackwiredetector.jpg)][trackwire]|[![Voltage Regulators 5V, 3.3V 1.5A]({{site.baseurl}}/images/voltageregulators5v33v15a.jpg)][volreg1]|[![Voltage Regulators 6V, 5V, 3.3V]({{site.baseurl}}/images/voltageregulators5v6v33v.jpg)][volreg2]| 
|-----------------|-----------|------------|
|Track wire detector|Voltage Regulator board: 5V, 3.3V 1.5A|Voltage Regulator board: 6V, 5V, 3.3V 100mA|
|-----------------|------------|------------|
|[![Bumpers]({{site.baseurl}}/images/bumpers.jpg)][bumpers]|[![Tape Sensors]({{site.baseurl}}/images/tapesensors.jpg)][tape]|[![Beacon Detector]({{site.baseurl}}/images/beacondetector.jpg)][beacon]| 
|-----------------|-----------|------------|
|Bump sensors|Tape sensors| Beacon detector|
|-----------------+------------+-----------------|


__Hardware Drivers__
------
We are maintaining our code for the drivers on [Dropbox](https://www.dropbox.com/sh/v8sjxvh7grjp1ka/AAAzdhRPmgMnUnuQns-ECcOEa?dl=0). Please click the link to look through the code. We have finished the drivers for all of our sensors and acuators.


__Breadboard Acuators__
------
We breadboarded our acutators but we also mounted them onto our robot and tested them. We posted videos in a previous entry that can be found [here]({{site.baseurl}}/update/wheels/motor/2015/11/10/wheel-testing.html). You will find two videos there that show that the robot can move and make tank turns using the tank treads.




[isoright]: {{site.baseurl}}/images/isorightview.png
[right]: {{site.baseurl}}/images/rightview.png
[rear]: {{site.baseurl}}/images/rearview.png
[top]: {{site.baseurl}}/images/topview.png
[foamcore]: {{site.baseurl}}/images/foamcore-robot.jpg
[trackwire]: {{site.baseurl}}/images/trackwiredetector.jpg
[volreg1]: {{site.baseurl}}/images/voltageregulators5v33v15a.jpg
[volreg2]: {{site.baseurl}}/images/voltageregulators5v6v33v.jpg
[bumpers]: {{site.baseurl}}/images/bumpers.jpg
[tape]: {{site.baseurl}}/images/tapesensors.jpg
[beacon]: {{site.baseurl}}/images/beacondetector.jpg