+++
# Date this page was created.
date = 2018-05-31T00:00:00

# Project title.
title = "Learning Real-world Visuo-motor Policies from Simulation"

# Project summary to display on homepage.
summary = ""
#summary = "Sensor-based robot tasks such as visual reaching are traditionally implemented by hand-crafted controllers. Typically a perception system will identify the target in some local or global coordinate system and the robot motion planner and joint control system will ensure that the required collision-free motion is executed. Understanding complex visual scenes has traditionally been a hard problem but in recent years deep learning techniques have led to significant improvements in robustness and performance. Recently deep learning approaches have also been used in robotic applications to learn visuo-motor policies where motors are directly controlled by observations from raw-pixel images. However, a consistent issue faced by most approaches is the reliance on large amounts of data for training. In practice, labelling of real robotic data is very expensive, or even impractical. In contrast, simulated data is much cheaper. Therefore, this thesis focuses on investigating how simulation can be used to reduce the cost of data collection for visuo-motor policy learning. Firstly, we evaluate the feasibility of learning vision-based planar reaching using a Deep Q Network (DQN), showing that DQN is able to learn reaching in simulation, however the learned policies do not transfer directly to real robots with real cameras observing real scenes. Therefore, modular deep Q networks are proposed to transfer policies from simulation to the real world in a low-cost manner with a small number of labelled real images. To further weaken the reliance on real data, an adversarial discriminative loss based semi-supervised approach is proposed to transfer visuo-motor policies with fewer labelled real data. A comparable performance can be achieved with 50% fewer labelled real images in a benchmark task of 7 DoF robotic reaching in clutter."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "projects/phd.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["reinforcement-learning", "deep-learning"]`
tags = ["transfer learning", "sim-to-real transfer", "deep learning", "reinforcement learning", "visuo-motor policy", "robotic reaching"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""

+++

This is my Ph.D. project in the [Australian Centre for Robotic Vision](https://www.roboticvision.org/) at [QUT](https://wiki.qut.edu.au/display/cyphy/Robotics@QUT), with supervisions from [Prof. Peter Corke](https://wiki.qut.edu.au/display/cyphy/Peter+Corke), [Dr. Jürgen Leitner](http://juxi.net/), [Prof. Michael Milford](https://wiki.qut.edu.au/display/cyphy/Michael+Milford) and [Dr. Ben Upcroft](https://www.roboticvision.org/rv_person/ben-upcroft/).

### **Learning Planar Reaching in Simulation**
{{< youtube 6cz-mcM4Qkc >}}

### **Robotic Planar Reaching in the Real World**
{{< youtube ybuFdsE6AjY >}}

### **Learning Table-top Object Reaching with a 7 DoF Robotic Arm from Simulation**
{{< youtube bVIw1DeuuYg >}}

Contributions:

- Feasibility analysis on learning vision-based robotic planar reaching using DQNs in simulation.
- Proposed a modular deep Q network architecture for fast and low-cost transfer of visuo-motor policies from simulation to the real world.
- Proposed an end-to-end fine-tuning method using weighted losses to improve hand-eye coordination.
- Proposed a kinematics-based guided policy search method (K-GPS) to speed up Q learning for robotic applications where kinematic models are known.
- Demonstrated in robotic reaching tasks on a real Baxter robot in velocity and position control modes, e.g., table-top object reaching in clutter and planar reaching.
- More investigations are undergoing for semi-supervised and unsupervised transfer from simulation to the real world using adversarial discriminative approaches.
