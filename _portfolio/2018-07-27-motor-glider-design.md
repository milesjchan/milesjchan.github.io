---
layout: post
title: "Motor Glider Design"
---
![Motor Glider]({{site.url}}/assets/portfolio/mg_full.jpg "Fixed wing aircraft")

<h3>Summary</h3>
This project actually began with a MATLAB script I wrote to calculate the center of gravity (CG) location of a conventional-layout aircraft, given measurements of the aircraft and a desired static margin. It made picking the CG location for new model airplanes substantially easier, since the manufacturer markings are often incorrect. After writing the tool, I realized that it might have applicability in a design project.

Given a constraining overall longitudinal length for the wing and tail positions, I could use this math tool to solve for the dimensions of the horizontal and vertical stabilizers for a conventional aircraft with a given wing geometry. This drove me to add features to the MATLAB tool, turning it into an object oriented program for model aircraft design.

<h3>About the Method</h3>
I have always found the definitions of the horizontal stabilizer (hstab) arm and volume fraction in longitudinal stability to be inconvenient when it comes to picking the CG location for a model aircraft I have sitting in front of me. My tool simply uses the symbolic math capabilities of MATLAB to solve for the horizontal stabilizer moment arm and CG location based on the overall distance from the rear of the horizontal tail to the wing apex, which is much easier to measure.
