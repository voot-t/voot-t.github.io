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
  * 2025 -- 2026 (Promoted from Research Scientist)
  * Managed a small team of researchers and engineers on daily technical execution.
  * Collaborated directly with industrial domain experts to extract practical knowledge and translate it into robot learning systems.

* **Research Scientist** at **Sony AI**, Tokyo, Japan
  * 2022 -- 2025
  * Researched and developed robot learning pipelines and algorithms for fine manipulation tasks in gastronomy robotics.
  * Built and maintained a major portion of the team's large-scale Python codebase.

* **Post-doctoral researcher** at **RIKEN Center for Advanced Intelligence Project (AIP)**, Tokyo, Japan
  * 2017 -- 2021
  * Researched and developed robust imitation and reinforcement learning algorithms under real-world data constraints.
  * Published research findings at international AI/ML conferences.
  * Collaborated with external research and industrial organizations for publications and patents.

Education
======
* **PhD in Computer Science**: The University of Tokyo, Japan, 2014 -- 2017

* **Masters in Computer Science**: Tokyo Institute of Technology, Japan, 2012 -- 2014

* **Bachelors in Computer Engineering**: Chulalongkorn University, Thailand, 2008 -- 2011

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
* **Research & Engineering**
  * **Research, develop, and fine-tune** robot policy networks (including Vision-Language-Action (VLA) architectures) utilizing imitation, reinforcement, and reward learning frameworks in simulation and on real-world hardware.
  * **Implement and optimize** deep learning models and algorithms using PyTorch, Jax, Keras, and TensorFlow.
  * **Design and implement** pipelines to collect multi-modal data from robot manipulators using teleoperation, kinesthetic teaching, motion capture, RGB-D cameras, and tactile sensors.
  * **Deploy** trained learning models to control real-world robot manipulators.

* **Programming & Tools**
  * **Python** (Core language; own and maintain a major portion of large scale codebases)
  * **C++** (Familiar language; analyze and review logic; personal prototyping for self-study)
  * **Robotics & Simulation**: ROS ecosystem, MoveIt, Impedance controllers, RGB-D and tactile data processing, and MuJoCo.
  * **Software**: AWS GPU clusters, Git, CI/CD workflows, and Docker.

* **Language**
  * **English**: Academic and business level
  * **Japanese**: Intermediate level
  * **Thai**: Native speaker

Awards
======
* RIKEN 2019 Ohbu Award: Research & Industry Partnership Incentive Award
* Best student presentation award: Information-Based Induction Sciences and Machine Learning (IBISML) 2016, Kyoto, Japan

Recent Publications
======
  <ul>
  {% assign items = site.publications | sort: items.year | reverse %}
  {% for post in items limit:5 %}
    {% include archive-single-cv.html %}
  {% endfor %}
  </ul>
