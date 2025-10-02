---
layout: project
title: Lifting a Weight
description: We were tasked with lifting a weight to the maximal height
technologies: [MATLAB, python]
image: /assets/images/Statics Design Project 1-1.png
---


As part of a class project we were given a 2D design space of 150cm long and 50cm tall, a rigid bar of a fixed length (your choice), 3 pin supports of which two need to be mounted on the ground and a linear
actuator (pick from this online catalog, use max force values only) in order to design a
frame/mechanism to lift the maximum possible weight to the highest possible height.
Assume all the supports and bar/actuator are rigid.

This is how I solved the problem:

The most complicated part of this was choosing a linear actuator that (1) fit the specifications and (2) could exert the largest amount of force. I ended up choosing the IMA 22 since it has a very good force/stroke length that the other actuators did not provide. The organization of the system is having the linear actuator pushing straight up 100 centimeters away from the pivot point.The limitations only allow a 150 cm length frame so it was important to me to not waste space. Doing a moment calculation, my system can lift 966.7 N. 


