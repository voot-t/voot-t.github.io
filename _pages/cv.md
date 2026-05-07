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
  * Conduct research on <span style="color:blue">vision-and-tactile-based robot learning algorithms for fine manipulation in gastronomy domains</span>.

* **Post-doctoral researcher** at **RIKEN Center for Advanced Intelligence Project (AIP)**, Tokyo, Japan
  * April 2017 -- December 2021 
  * Conduct research on <span style="color:blue">robust machine learning algorithms under real-world data constraints</span>.

Education
======
* **PhD in Computer Science**: University of Tokyo, Graduate School of Information Science and Technology, Japan, 2017
  * **Thesis**: Single-step Dimension Reduction for High-dimensional Data Analysis with Application in Reinforcement Learning

* **Masters in Computer Science**: Tokyo Institute of Technology, Japan, 2014
  * **Thesis**: Least-Squares Conditional Density Estimation with Dimensionality Reduction

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
* **Machine learning (ML) skills**
  * Expertised in <span style="color:blue">vision-based robust imitation and reinforcement learning</span>.
  * Experience with <span style="color:blue">general robust ML</span>, such as robust objective and optimization, data augmentation, domain randomization, and uncertainty estimation.
  * Experience with <span style="color:blue">reward design and learning from human experts</span>, including  industry experts who are not familiar with AI/ML or robotics.
  * Experience in <span style="color:blue">deep learning architectures</span> (e.g., MLP, RNN, Convolutions, Transformers) and shallow architectures (e.g., non-parametric, kernels).

* **Robot learning skills**
  * Experience with using <span style="color:blue">real-world multi-modal data from proprioceptor, vision, and tactile sensors</span> collected from human demonstrators.
  * Experience with using <span style="color:blue">robust ML to address real-world sensor noises and sim-to-real gaps</span> in robot learning.
  * Experience with <span style="color:blue">prototyping a robot learning pipeline on real robots</span>:
    * The pipeline includes collecting raw data, processing data, training models on local and GPU clusters, and deploying models on real robots.
  * Familiarity with using <span style="color:blue">position and impedance controllers</span> in real robots.

* **Programming skills**
  * Experience in <span style="color:blue">Python</span> programming.
  * Experience in <span style="color:blue">deep learning libraries</span> (Pytorch, Jax, Keras, and Tensorflow).
  * Experience in using open-source <span style="color:blue">vision and vision-language-action models</span> for prototyping and evaluation.
  * Experience with <span style="color:blue">Robot Operating System (ROS)</span> 1 and 2.
  * Experience with <span style="color:blue">robot simulation libraries</span> (Gymnasium, Mujoco, and Pybullet).
  * Familiarity with software development tools such as Git and Docker containers.

* **Language skills**
  * Academic-level English
  * Intermediate-level Japanese
  * Native Thai


Non-technical Skills:
======
* Experience with managing a small group of members as a <span style="color:blue">sub-team leader</span>.
  * Responsibility includes managing roadmaps, milestones, meetings, software and hardware resources, multi-modal datasets, and large-scale GPU clusters of the subteam.
* Experience with <span style="color:blue">collaborating with external organizations</span> for research, development, publications, and patents.

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
