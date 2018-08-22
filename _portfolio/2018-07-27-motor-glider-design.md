---
layout: post
title: "Motor Glider Design"
---
![Motor Glider]({{site.url}}/assets/portfolio/mg_full.jpg "Fixed wing aircraft")
<!--more-->
<h3>Summary</h3>
This project actually began with a MATLAB script I wrote to calculate the center of gravity (CG) location of a conventional-layout aircraft, given measurements of the aircraft and a desired static margin. It made picking the CG location for new model airplanes substantially easier, since the manufacturer markings are often incorrect. After writing the tool, I realized that it might have applicability in a design project.

Given a constraining overall longitudinal length for the wing and tail positions, I could use this math tool to solve for the dimensions of the horizontal and vertical stabilizers for a conventional aircraft with a given wing geometry. This drove me to add features to the MATLAB tool, turning it into an object oriented program for model aircraft design.

<h3>Software Skills Used</h3>
* SolidWorks
* MATLAB
* ImageJ

<h3>CG Location Determination</h3>
I have always found the definitions of the horizontal stabilizer (hstab) arm and volume fraction in longitudinal stability to be inconvenient when it comes to picking the CG location for a model aircraft I have sitting in front of me. My tool simply uses the symbolic math capabilities of MATLAB to solve for the horizontal stabilizer moment arm and CG location based on the overall distance from the rear of the horizontal tail to the wing apex, which is much easier to measure.

After validating my model against model airplanes I've already built, I realized that I could apply it to aircraft I do not own. By pulling measurements from planform pictures using ImageJ, I was able to study the geometric dimensions of several model airplanes. I became more comfortable with the idea of designing a new aircraft, using my new tool and familiarity with usual airplane proportions in the process.

<h3>Design Method</h3>
Based on data from previous aircraft designs, I predicted the takeoff weight of my aircraft for a given motor, speed controller, and battery combination. I used this to define my wing planform geometry for my desired aspect ratio, which came from my desire to have glider-like performance.

![MATLAB Planform Geometry]({{site.url}}/assets/portfolio/mg_matlab.png)
For that given wing geometry, and a tail constraint dimension, I solved for the CG location, vertical and horizontal stabilizer positions and dimensions for reasonable values of vertical and horizontal stabilizer volume fractions. I implemented object-oriented tools in MATLAB to automate the process and provide design visualization capability.

After defining the dimensions of my aircraft, I created a CAD model in SolidWorks.