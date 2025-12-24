---
layout: project
title: Lifting a Weight
description: We were tasked with lifting a weight to the maximal height and finding the corresponding deflection
technologies: [MATLAB, python]
image: /assets/images/Statics portfolio-1.png
image: /assets/images/Statics portfolio-2.png

---


As part of a class project we were given a 2D design space of 150cm long and 50cm tall, a rigid bar of a fixed length (your choice), 3 pin supports of which two need to be mounted on the ground and a linear
actuator (pick from this online catalog, use max force values only) in order to design a
frame/mechanism to lift the maximum possible weight to the highest possible height.
Assume all the supports and bar/actuator are rigid.

This is how I solved the problem:

The most complicated part of this was choosing a linear actuator that (1) fit the specifications and (2) could exert the largest amount of force. I ended up choosing the IMA 22 since it has a very good force/stroke length that the other actuators did not provide. The organization of the system is having the linear actuator pushing straight up 100 centimeters away from the pivot point.The limitations only allow a 150 cm length frame so it was important to me to not waste space. Doing a moment calculation, my system can lift 966.7 N. 

After finding how much my system can lift it would be helpful to find how much our beam deflects because of the linear actuator. We can set boundary conditions and take multiple cuts to find the moment. Knowing the relationship between moment and EI* the second derivative of the deflection (y), we can find the equations of the deflection of the beam. After integrating and solving for the constants of integration, we can impose that we want less than 2% of 150 cm, 3 cm, deflection. 

If we use structural steel for the beam, we can find the necessary I value. The most material efficient shape for that I-value is the Wide flange 410 x 46.1 flange. 
