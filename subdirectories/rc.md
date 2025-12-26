---
title: "Rc Car"
permalink: /rc/
---

# 3D Printed RC Car

---

## Initial Idea
I wanted to create a drift RC car on my own from scratch. The goal was to build a budget RC car, since it seemed cheaper than buying one from AliExpress (although the battery alone ended up costing about as much as an entire RC drift car). In the end, this project was a fun way of learning how to code an ESP32, create a local WiFi network, control a microcontroller with my phone, and improve my 3D printing skills. I used this guide from <a href="https://dukedoks.com/portfolio/guia-chasis-rc/" target="_blank" rel="noopener noreferrer">DukeDoks</a> to 3D print and assemble the chassis, and designed and built the electronic circuit myself.

---

## Electrical circuit diagrams
The idea was to create a fully custom circuit, controlled by a single ESP32, using PWM to control the 12V DC motor. Since I didn't have the right transistor to do so, I finally opted to control the DC motor using a <a href="https://spurqlabs.com/controlling-dc-motors-with-arduino-using-the-l298n-motor-driver-for-iot-automation/" target="_blank" rel="noopener noreferrer">L298N Drive module</a>. The code for the WiFi network and the servo motor was done by <a href="https://remotexy.com/en/editor/" target="_blank" rel="noopener noreferrer">Remote XY</a>.

Diagram:

![drawing](../assets/rc/diagram.jpg)

Code: _Incomplete_

---

## Final Result
_This project is currently incomplete, therefore I can't share any finished progress_

--- 

## Axle Shaft side project
My cousin, who owns an RC car, broke both front axles, and asked me to fix them. Using Fusion 360, I designed and 3D printed some replacement parts, which were designed to be assembled using only 3 parts, and a cut paperclip.

<img src="/assets/rc/Axles_1.jpg" alt="Axles 1" width="400"> <img src="/assets/rc/Axles_2.jpg" alt="Axles 2" width="400">