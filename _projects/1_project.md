---
layout: page
title: Learning Real-world Visuo-motor Policies from Simulation
description: This is my Ph.D. project in the Australian Centre for Robotic Vision at QUT, with supervisions from Prof. Peter Corke, Dr. Jürgen Leitner, Prof. Michael Milford and Dr. Ben Upcroft.
img: assets/img/project_1.png
importance: 1
category: work
related_publications: false
---
<!-- Project title and date -->
<h3><strong>Learning Real-world Visuo-motor Policies from Simulation</strong></h3>
<p>May 31, 2018</p>

<!-- Project picture -->
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project_1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<!-- Content -->
<p>This is my Ph.D. project in the <a href="https://www.roboticvision.org/" target="_blank" rel="noopener">Australian Centre for Robotic Vision</a> at <a href="https://wiki.qut.edu.au/display/cyphy/Robotics@QUT" target="_blank" rel="noopener">QUT</a>, with supervisions from <a href="https://wiki.qut.edu.au/display/cyphy/Peter&#43;Corke" target="_blank" rel="noopener">Prof. Peter Corke</a>, <a href="http://juxi.net/" target="_blank" rel="noopener">Dr. Jürgen Leitner</a>, <a href="https://wiki.qut.edu.au/display/cyphy/Michael&#43;Milford" target="_blank" rel="noopener">Prof. Michael Milford</a> and <a href="https://www.roboticvision.org/rv_person/ben-upcroft/" target="_blank" rel="noopener">Dr. Ben Upcroft</a>.</p>

<!-- part 1 -->
<h4 id="learning-planar-reaching-in-simulation"><strong>Learning Planar Reaching in Simulation</strong></h4>
<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden;">
  <iframe src="https://www.youtube.com/embed/6cz-mcM4Qkc" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border:0;" allowfullscreen title="YouTube Video"></iframe>
</div>

<!-- part 2 -->
<h4 class="mt-3" id="robotic-planar-reaching-in-the-real-world"><strong>Robotic Planar Reaching in the Real World</strong></h4>
<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden;">
  <iframe src="https://www.youtube.com/embed/ybuFdsE6AjY" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border:0;" allowfullscreen title="YouTube Video"></iframe>
</div>

<!-- part 3 -->
<h4 class="mt-3" id="learning-table-top-object-reaching-with-a-7-dof-robotic-arm-from-simulation"><strong>Learning Table-top Object Reaching with a 7 DoF Robotic Arm from Simulation</strong></h4>
<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden;">
  <iframe src="https://www.youtube.com/embed/bVIw1DeuuYg" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border:0;" allowfullscreen title="YouTube Video"></iframe>
</div>

<!-- part 4 -->
<p class="mt-3">Contributions:</p>
<ul>
  <li>Feasibility analysis on learning vision-based robotic planar reaching using DQNs in simulation.</li>
  <li>Proposed a modular deep Q network architecture for fast and low-cost transfer of visuo-motor policies from simulation to the real world.</li>
  <li>Proposed an end-to-end fine-tuning method using weighted losses to improve hand-eye coordination.</li>
  <li>Proposed a kinematics-based guided policy search method (K-GPS) to speed up Q learning for robotic applications where kinematic models are known.</li>
  <li>Demonstrated in robotic reaching tasks on a real Baxter robot in velocity and position control modes, e.g., table-top object reaching in clutter and planar reaching.</li>
  <li>More investigations are undergoing for semi-supervised and unsupervised transfer from simulation to the real world using adversarial discriminative approaches.</li>
</ul>




<!-- <header class="post-header">
  <h1 class="post-title">{{ page.title }}</h1>
  <p class="post-description">{{ page.description }}</p>
</header> -->