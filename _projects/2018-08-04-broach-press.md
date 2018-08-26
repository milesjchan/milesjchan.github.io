---
layout: post
title: "Broach Press"
thumbnail: "bp_1stprincipal.jpg"
---
![Broach Press]({{site.url}}/assets/projects/bp_1stprincipal.jpg)
<!--more-->
<h3>Summary</h3>
Transferring torque between a shaft and rotating component requires a mechanical interface of some sort. Depending on the application, a press fit, machine key, or spline interface may be used. Sometimes, it is convenient to use a shaft with a cross section which has multiple contact vertices, such as a hex shaft.

A push broach can be can be used to create a keyway for a machine key or a hexagonal profile hole. The 1.5 ton force required to perform push broaching of a 1/2" hex shaft generally requires a large arbor press or unwieldy hydraulic press. Given that my FIRST Robotics team did not have a workspace capable of supporting large machinery, I needed to provide a different solution.

I designed and implemented a small and portable structure for a 1.5 ton hydraulic jack to perform a well-aligned push broaching operation. The broach press proved to be extremely successful, and has now been used extensively by my FIRST Robotics team for the past 7 years.

<h3>Design and Analysis</h3>
My goal was to build a small, portable structure capable of delivering and withstanding a 1.5 ton push broaching operation. The structure needed to be rigid enough to keep the broaching operation straight.

I created several structural designs in Autodesk Inventor, and performed finite element analysis using the Inventor finite element analysis (FEA) tool. I ran several design review sessions, in which team mentors and I went over my design decisions and current FEA results. I researched the structural designs of other hydraulic presses, eventually leading me to the final, efficient structure design. I calculated that the weld lengths provided sufficient strength, and demonstrated that the structure was stiff enough to preserve the accuracy of the broaching operation using FEA.

<h3>Fabrication</h3>
I used a jigsaw to cut the steel structure parts, and a small manual mill to face the important ends for welding. One of our gracious mentors, Fernando Reyes, welded the structure together.

<h3>What I Learned and Would Improve</h3>
This remains one of the most interesting design projects I have worked on. As a high school sophomore, it was my first exposure to concepts such as Young's Modulus and using a computer to perform finite element analysis. Now, with a college education in mechanical engineering and more specific experience in stress calculations and finite element analysis, I certainly would have taken a more technically rigorous approach by starting with hand calculations before moving into finite element analysis.

That being said, one of the key lessons I learned is that no number of mathematical equations or computer simulations is more valuable than a fundamental, intuitive understanding of the design problem at hand. Oftentimes, the true value of a hand calculation is that it provides insight into what the design problem really is about. Most of my early designs were inefficient because they used C-channel and I-beam cross sections in ways they are not strong. By studying previous designs and learning how to ask the right questions, I learned how to align these cross sections to more efficiently carry my design loads.

This project succeeded because, between myself and the mentors on the team, we had enough design and manufacturing intuition to determine whether my analysis values made sense and my structural designs were sound.

<h3>Special Acknowledgement</h3>


<h3>Resources</h3>
