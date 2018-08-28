---
layout: post
title: "2 Motor Propeller Pendulum"
thumbnail: "dual_prop_pend.jpg"
---
<div class="row">
<!-- ![Dual propeller pendulum]({{site.url}}/assets/projects/dual_prop_pend.jpg "Dual propeller pendulum") -->
  <div class="col-lg-3 col-md-3">
    <img class="img-fluid" src="{{site.url}}/assets/projects/dual_prop_pend.jpg">
  </div>
<!-- <div class="img"><img src="{{site.url}}/assets/projects/dual_prop_pend.jpg" class="float-left w-25 mr-3" alt="Prop Pendulum Image"></div> -->
<!--more-->
  <div class="col-lg-9 col-md-9">
    <h3>Summary</h3>
    <p>The propeller pendulum is an interesting controls problem, consisting of a thrust source mounted on the end of a pivoting arm, where angular position is measured using a potentiometer. Most of the papers I've seen use a poor linearization based on the small-angle approximation about the vertical plane. This of course breaks down when the arm is near the horizontal, 90 degree setpoint. Many examples also do not implement bidirectional flow control, or two propeller-motors opposing each other.</p>

    <p>I worked with my partner, Tyler Boone, to implement a propeller pendulum with bidirectional flow control using PID logic for our undergraduate controls class. We were able to reduce the time required to reach the 90 degree setpoint as compared to the single propeller-motor version. We achieved some level of agreement with MATLAB simulations, with regard to the overall behavior of the PID controller we implemented. We were also able to move between set points of 0 deg and 110 deg on command, with reasonable response times.</p>

    <p>However, there is much room for improvement, and I believe the propeller pendulum project is well worth revisiting in the future.</p>

    <h3>Details</h3>
    <ul>
      <li>Undergrad controls project</li>
      <li>Designed using SolidWorks</li>
      <li>Manufactured using laser cutter, 3D printer</li>
      <li>Custom PID code implemented on Arduino</li>
      <li>System characterized using open loop testing</li>
      <li>Uses 2 motors for bidirectional flow control</li>
    </ul>

    <h3>Resources</h3>
    <ul>
      <li>Presentation</li>
      <li>MATLAB simulation</li>
    </ul>
  </div>
</div>
