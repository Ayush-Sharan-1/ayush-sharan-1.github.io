---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **Master of Science in Robotics Systems Development**, Carnegie Mellon University, Pittsburgh, PA, May 2027
  * GPA: 4.08/4.00
  * Relevant coursework: 16-720 Computer Vision, 16-665 Robot Mobility (Legged locomotion dynamics and control (LIPM, spring mass models)), 16-833 Robot Localization and Mapping

* **Bachelor of Technology in Mechanical Engineering**, National Institute of Technology Karnataka, Surathkal, Mangalore, India, October 2022
  * GPA: 9.47/10.00

Work experience
======
* **July 2022 – April 2025: Senior Associate Engineer**
  * Caterpillar Inc, Bengaluru, India
  
  **Reinforcement Learning Based Microgrid Controller**
  * Developed a Soft Actor-Critic (SAC) reinforcement learning-based microgrid energy management controller, achieving a median 5% reduction in operating costs over the rule-based controller across diverse 24-hour cycles.
  * Curated and processed rule-based controller field data to bootstrap model learning via off-policy training.
  * Built a high-fidelity microgrid simulation model in MATLAB Simulink for online training and validation.
  
  **Scheduling and Route Planning for EV Mining Trucks**
  * Developed a rule-based charging scheduler and A*-based route planner in ROS2 for electric mining trucks, integrated with the microgrid and its controller.
  * Presented analysis showing a 5% reduction in operating costs to senior leadership, driving inclusion of the feature in the product roadmap.
  
  **Hardware-in-the-Loop (HIL) Test Bench Development**
  * Defined system requirements and architecture, and led a team of 3 engineers in designing and delivering a HIL test bench for Microgrid controller validation.
  * Integrated 7 embedded ECMs with a real-time simulation platform through CAN, Modbus, and digital/analog I/O.
  * Developed microgrid simulation models in MATLAB, implementing generator control systems with PI frequency control (Governor), PI voltage control (AVR), and droop-based load sharing.
  * Collaborated with cross-functional teams to define requirements, plan, and execute validation, achieving a 95% defect detection rate.

Skills
======
* **Programming Languages**: Python, C++, MATLAB
* **Tools & Software**: ROS2, PyTorch, OpenCV, Gazebo, MoveIt, RViz, Git, MATLAB Simulink, Linux

Projects
======
* **May 2025 – July 2025: Imitation Learning and Perception for a Tic Tac Toe Robot**
  * Implemented a computer vision pipeline for board detection and classification followed by a hierarchical system for playing by integrating a Tic Tac Toe Minimax strategy engine with an Action Chunking Transformer (ACT) policy, deployed on the LeRobot SO100 6-DOF manipulator.
  * Developed the computer vision pipeline using ORB feature matching and homography estimation to detect and rectify the Tic Tac Toe board, followed by HSV-based classification to infer the game state.
  * Extended the ACT architecture with language conditioning, enabling execution of different moves through simple natural language input under a single policy.
  * Integrated spatial attention maps to visualize action selection and improve the interpretability of the learned policy.

* **September 2025 – Ongoing: Dual-Arm Robot for Medical Inventory Labeling** (CMU Capstone Project)
  * Developing a dual-arm robotic system with two X-Arm 7's in collaboration with UPMC for applying RFID labels to medical items, to improve item tracking efficiency within the Operating Room supply rooms.
  * Focusing on designing the motion and grasp planning pipeline for item pick-and-place operations and the precise application of RFID stickers for medical items of varying form factors, rigidity, and transparency.

Patents
======
* **[Sharan, Ayush] Dissociated Microgrid Controller** [20250260235] filed [Feb 08, 2024] and issued [Aug 14, 2025]
* **[Sharan, Ayush] Dynamic Reserve Evaluation for Microgrid Controls** [19/289465] filed [Aug 4, 2025] Patent Pending

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
