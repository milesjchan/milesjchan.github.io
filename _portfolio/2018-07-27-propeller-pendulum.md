---
layout: post
title: "2 Motor Propeller Pendulum"
---

![Dual propeller pendulum]({{site.url}}/assets/portfolio/dual_prop_pend.jpg "Dual propeller pendulum")

* Undergrad controls project
* Designed in SolidWorks
* Manufactured using laser cutter, 3D printer
* Custom PID code implemented on Arduino
* Characterized using open loop testing
* Uses 2 motors for thrust in opposite directions

The propeller pendulum has a thrust source mounted on the end of a single pivot arm. Arm angle is measured by measuring the voltage drop across a rotary potentiometer. PID control using custom code is implemented on an Arduino, outputting a desired thrust. The code converts the desired total thrust into PWM signals for both motors.
