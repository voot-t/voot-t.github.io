---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}


[PDF version](https://voot-t.github.io/files/cv.pdf) 

Work history
======
* **Senior Research Scientist** at **Sony AI**, Tokyo, Japan
  * January 2022 -- present 
  * Research and development of robot learning pipeline, models, and algorithms for fine manipulation in gastronomy robotics.

* **Post-doctoral researcher** at **RIKEN Center for Advanced Intelligence Project (AIP)**, Tokyo, Japan
  * April 2017 -- December 2021 
  * Research and development of robust imitation and reinforcement learning models and algorithms under real-world data constraints.

Education
======
* **PhD in Computer Science**: University of Tokyo, Graduate School of Information Science and Technology, Japan, 2017

* **Masters in Computer Science**: Tokyo Institute of Technology, Japan, 2014

* **Bachelors in Computer Engineering**: Chulalongkorn University, Thailand, 2011

* **High school**: Suankularb Wittayalai School, Thailand, 2002-2008.

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
* **Research and development**
  * Expertised in research and development of imitation (behavioral cloning, GAIL, VLA) and reinforcement learning (e.g., actor-critic, model-based RL, offline RL) models and algorithms..
  * Experience in training and deploying learning models on real-world robots. 
  * Experience with reward design and reward learning (e.g., inverse reinforcement learning and preference reward learning).
  * Experience in research and development of robust ML (e.g., robust optimization and uncertainty estimation).
  * Experience in implementing deep learning models and architectures. 
  * Experience in implementing a robot learning pipeline on real-world robots with Python
  * Experience in collecting real-world robot data of proprioceptor, vision, and tactile sensors using kinesthetic teaching, tele-operation, and motion capture systems.
  * Familiarity with using GPU clusters for model training. 
  * Familiarity with using position and impedance controllers for controlling robot manipulators.

* **Programming**
  * Experience in Python programming.
  * Experience in deep learning libraries (Pytorch, Jax, Keras, and Tensorflow).
  * Experience with Robot Operating System (ROS) 1 and 2.
  * Experience with robot simulation libraries (Gymnasium, Mujoco, and Pybullet).
  * Familiarity with software development tools including AWS, Git, and Docker containers.

* **Language**
  * Academic and business-level English
  * Intermediate-level Japanese
  * Native Thai


Non-technical Skills:
======
* Experience in managing roadmaps and development of a small group of engineers and researchers.
* Experience with collaborating with external organizations for research, development, publications, and patents.

Awards
======
* RIKEN 2019 Ohbu Award
  * Research & Industry Partnership Incentive Award
* Best student presentation award: 
  * Venue: Information-Based Induction Sciences and Machine Learning 2016, Kyoto, Japan

Recent Publications
======
  <ul>
  {% assign items = site.publications | sort: items.year | reverse %}
  {% for post in items limit:5 %}
    {% include archive-single-cv.html %}
  {% endfor %}
  </ul>
