---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}


[PDF version](https://academicpages.github.io/files/cv.pdf) 

Work history
======
* **Senior Research Scientist**: January 2022 -- present 
  * **Sony AI**, Tokyo, Japan
  * Part of **Gastronomy Robotics Project**
  * Responsibility: Conduct research and development on learning algorithms and robotics systems to perform _fine manipulation in the gastronomy domain_.

* **Post-doctoral researcher**: April 2017 -- December 2021 
  * **RIKEN Center for Advanced Intelligence Project (AIP)**, Tokyo, Japan
  * Part of **Imperfect Information Learning Team**
  * Responsibility: Conduct research on machine learning algorithms to _enable high-performant models under different data constraints_.

Education
======
* **PhD in Computer Science**: University of Tokyo, Japan, 2017
  * PhD degree from the Department of Computer Science under supervision of Prof. Masashi Sugiyama
  * Thesis: _Single-step Dimension Reduction for High-dimensional Data Analysis with Application in Reinforcement Learning_

* **Masters in Computer Science**: Tokyo Institute of Technology, Japan, 2014
  * Master degree from the Department of Computer Science under supervision of Prof. Masashi Sugiyama
  * Thesis: _Least-Squares Conditional Density Estimation with Dimensionality Reduction_

* **Bachelors in Computer Engineering**: Chulalongkorn University, Thailand, 2011
  * Bachelor degree from the Faculty of Computer Engineering

Internship experience
======
* **Visiting Student**: 2016
  * Technische Universität Darmstadt, Darmstadt, Germany
  * Intelligent Autonomous Systems (IAS) group under supervisors Prof. Jan Peters and Prof. Gerhard Neumann
  * Responsibility: Conduct collaborative research on reinforcement learning in robot manipulators
  
* **Intern Student**: 2015 
  * Advanced Telecommunications Research Institute (ATR), Kyoto, Japan
  * Department of Brain-Robot-Interface under supervisor Dr. Jun Morimoto
  * Responsibility: Conduct collaborative research on reinforcement learning in humanoid robots
  
Technical Skills
======
* Expertise in **Reinforcement learning and Imitation learning for robot learning**
* Programming skills
  * Deep learning libraries (Pytorch, Jax, Keras, and Tensorflow)
  * Robot simulation libraries (Gymnasium, Mujoco, and Pybullet)
  * Python language programming
  * Robot Operating System (ROS)
  * Software development tools: Git version control, Docker container, and Linux OS 
* Language skills
  * English: Academic level, including paper reading, writing, and reviewing
  * Japanese: Intermediate level
  * Thai: Native 

Non-technical Skills:
======
* Team management experience:
  * Team leader of a 5-members subteam of robot learning researchers and engineers
  * Responsibility: Outline development roadmaps and present them to the executives and stakeholders
* Mentorship:
  * I have experience as a mentor of internship students who joined the teams.
* Collaboration with external organizations:
  * I have experience collaborating with external organizations for joint research, publications, and patents.

Awards
======
* RIKEN 2019 Ohbu Award
  * Research & Industry Partnership Incentive Award
* IBIS 2016 Best student presentation award: 
  * Venue: Information-Based Induction Sciences and Machine Learning 2016, Kyoto, Japan
  * Policy Search with High-dimensional Context Variables

Recent Publications
======

  <ul>
  {% assign items = site.publications | sort: items.year | reverse %}
  {% for post in items limit:5 %}
    {% include archive-single-cv.html %}
  {% endfor %}
  </ul>
