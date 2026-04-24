---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Job experience
======
* **Senior Research scientist**: January 2022 to present 
  * Sony AI, Tokyo, Japan
  * Gastronomy robotics project

* **Post-doctoral researcher**: April 2017 to December 2021 
  * RIKEN Center for Advanced Intelligence Project (AIP), Tokyo, Japan
  * Imperfect Information Learning team

Education
======
* **PhD in Computer Science**: University of Tokyo, Japan, 2017
  * PhD degree from the Department of Computer Science under supervision of Prof. Masashi Sugiyama
  * Thesis: <i>Single-step Dimension Reduction for High-dimensional Data Analysis with Application in Reinforcement Learning</i>

* **Masters in Computer Science**: Tokyo Institute of Technology, Japan, 2014
  * Master degree from the Department of Computer Science under supervision of Prof. Masashi Sugiyama
  * Thesis: <i>Least-Squares Conditional Density Estimation with Dimensionality Reduction</i>

* **Bachelors in Computer Engineering**: Chulalongkorn University, Thailand, 2011
  * Bachelor degree from the Faculty of Computer Engineering

Internships
======
* **Visiting Student**: 2016
  * Technische Universität Darmstadt, Darmstadt, Germany
  * Intelligent Autonomous Systems (IAS) group. Supervisors: Jan Peters and Gerhard Neumann
  * Responsibility: Conduct collaborative research on reinforcement learning in robot manipulators
  
* **Intern Student**: 2015 
  * Advanced Telecommunications Research Institute (ATR), Kyoto, Japan
  * Department of Brain-Robot-Interface. Supervisor: Jun Morimoto
  * Responsibility: Conduct collaborative research on reinforcement learning in humanoid robotics
  
Technical Skills
======
* Expertise in **Machine learning**
  * Specialized on reinforcement learning and imitation learning
* Expertise in **Robot learning**
  * Specialized in applications of machine learning in robot manipulators
* Programming skills
  * Deep learning libraries (Pytorch, Jax, Keras, and Tensorflow)
  * Robot simulation libraries (Gymnasium, Mujoco, and Pybullet)
  * Python language programming
  * Robot Operating System (ROS)
  * Software development tools: Git version control, Docker container, and Linux OS 
* Language skill
  * English: Academic level, including paper reading, writing, and reviewing
  * Japanese: Intermediate level
  * Thai: Native 

Soft Skills:
======
* Team management experience:
  * Team leader of a 5-members subteam of robot learning researchers and engineers
  * Responsibility: Outline development roadmaps and present them to the executives and stakeholders
* Mentorship:
  * I have experience as a mentor of internship students who joined the team.
* External collaboration:
  * I have experience collaborating with external organizations for joint research, publications, and patents.

Awards
======
* RIKEN 2019 Ohbu Award (Research & Industry Partnership Incentive Award)
* IBIS 2016 best student presentation award

Recent Publications
======

  <ul>
  {% assign items = site.publications | sort: items.year | reverse %}
  {% for post in items limit:5 %}
    {% include archive-single-cv.html %}
  {% endfor %}
  </ul>
