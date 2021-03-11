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
* PhD in Computer Science, University of Tokyo, Japan, 2017.
  * I obtained PhD degree from the Department of Computer Science at the University of Tokyo under supervision of Prof. Masashi Sugiyama
  * PhD thesis titled <i>Single-step Dimension Reduction for High-dimensional Data Analysis with Application in Reinforcement Learning</i>

* Masters in Computer Science, Tokyo Institute of Technology, Japan, 2014.
  * I obtained Master degree from the Department of Computer Science at Tokyo Institute of Technology under supervision of Prof. Masashi Sugiyama.
  * Master thesis titled <i>Least-Squares Conditional Density Estimation with Dimensionality Reduction</i>

* Bachelors in Engineering, Chulalongkorn University, Thailand, 2011.
  * I obtained Bachelor degree from the Faculty of Computer Engineering at Chulalongkorn University.

Work experience
======
* From March 2017 to present: Post-doctoral researcher
  * RIKEN Center for Advanced Intelligence Project (AIP), Tokyo, Japan
  * Imperfect Information Learning team. Supervisor: Masashi Sugiyama.
  * I conduct machine learning research on the topic of robust and efficient reinforcement and imitation learning.

* Summer 2016: Visiting Student
  * Technische Universität Darmstadt, Darmstadt, Germany
  * Intelligent Autonomous Systems (IAS) group. Supervisors: Jan Peters and Gerhard Neumann
  * I conducted collaborative research with IAS members on efficient reinforcement learning for robotics.
  
* Summer 2015: Intern Student
  * Advanced Telecommunications Research Institute (ATR), Kyoto, Japan
  * Department of Brain-Robot-Interface. Supervisor: Jun Morimoto
  * I conducted collaborative research with ATR members on controlling humanoid robots by reinforcement learning.
  
Skills
======
* Expertise on machine learning research
  * Specialized on reinforcement learning and imitation learning research.
* Python programming
  * Deep learning libraries (Pytorch and Tensorflow)
  * Reinforcement learning related libraries (Gym, Mujoco, and Pybullet) 
* Academic paper writing, reading, and reviewing 
* Language skill
  * English: Academic level  
  * Thai: Native 
  * Japanese: Beginner level


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
