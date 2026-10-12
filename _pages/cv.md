---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Resume (PDF)](http://JayantTeotia16.github.io/files/Resume.pdf)

Research Interests
======
Affective Computing, Emotion Recognition, Multimodal Large Language Models, Cognitive Science for AI

Education
======
* **Nanyang Technological University, Singapore** (Aug 2024 – Present)
  * Doctor of Philosophy, Computer Science. Supervisor: Prof. Erik Cambria
  * Research on emotion understanding in multimodal LLMs grounded in cognitive appraisal theory, covering future-emotion prediction in dialogue and MLLM evaluation on affective art and narrative interpretation.

* **Indian Institute of Technology Roorkee, India** (Jul 2016 – Jul 2020)
  * Bachelor of Technology, Mechanical Engineering. GPA: 8.04/10

Research Experience
======
* **Artificial Intelligence Lab, NTU Singapore**, Research Assistant (Aug 2024 – Present)
  * Supervisor: Prof. Erik Cambria
  * Developing a model to predict future emotional states, combining evolutionary prompt optimization with reinforcement learning.
  * Surveyed cognitive science theories of affect and analyzed how they are applied in current AI research, datasets, and evaluation methods.
  * Evaluated large language models (LLMs) and multimodal LLMs (MLLMs) on affective tasks, including student engagement in educational settings, narrative interpretation, and affective art understanding.

* **Robert Bosch Centre for Cyber-Physical Systems, IISc Bangalore**, Research Assistant (Jun 2022 – Jul 2024)
  * Supervisor: Prof. Suresh Sundaram
  * Proposed OGP-Net, an RGB–IR fusion method robust to missing modalities, using automatic mixed feature exchange and spectral knowledge distillation for semantic segmentation (AAAI 2025).
  * Developed SKD-Net, spectral knowledge distillation for segmentation in low-light thermal imagery (ICRA 2024).
  * Implemented a rotation-equivariant detector and Oriented R-CNN to improve small-object detection in remote sensing imagery.

* **AI and Robotics Technology Park (ARTPARK), IISc Bangalore** (Mar 2021 – May 2022)
  * Research Associate (Jun 2021 – May 2022); Research Intern (Mar 2021 – May 2021)
  * Supervisors: Prof. Suresh Sundaram, Badrinarayana Rangarajan
  * Trained and benchmarked YOLOv3, Faster R-CNN, and SSD for aerial object detection, reaching 93% accuracy.
  * Cut YOLOv3 inference latency by 40% (20 ms → 12 ms) on an NVIDIA A6000 via pruning and knowledge distillation.
  * Built a gRPC client–server pipeline for bidirectional UAV data streaming over Wi-Fi, removing dependence on AirSim and ROS APIs.
  * Simulated single- and multi-UAV missions with integrated object detection (MAVSDK, AirSim), and teleoperated a ground robot using the ROS navigation stack.

Industry Internships
======
* **Robert Bosch Engineering and Business Solutions**, Summer Intern (May 2019 – Jul 2019)
  * Applied nonlinear Model Predictive Control (VIATOC) to overhead-crane obstacle avoidance and benchmarked auto-generated C++ solvers on a Raspberry Pi 3B.

* **iX Energy Pvt. Ltd.**, Summer Intern (May 2018 – Jul 2018)
  * Modelled an electric vehicle's electrical, mechanical, and cooling systems and wrote Stateflow-based ECU code for start-up, error handling, and CAN communication.

Selected Project
======
* **IIT Roorkee Motorsports (Formula SAE)**, Vehicle Dynamics and Controls Lead (Jul 2017 – Jun 2020)
  * Led the Vehicle Dynamics division for RMS E-19, a formula-style electric race car.
  * Built vehicle dynamics models and a lap-time simulator whose design optimizations cut lap time by 2 s.
  * Developed SLAM and Model Predictive Control algorithms for a simulated autonomous Formula Student car.

Publications
======
{% assign pubs = site.publications | sort: "date" | reverse %}
  <ul>{% for post in pubs %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Technical Skills
======
* **Languages:** Python, C++, LaTeX
* **ML & LLMs:** PyTorch, TensorFlow, scikit-learn, Hugging Face Transformers
* **Robotics & Simulation:** ROS, PyBullet, AirSim, MATLAB/Simulink, SolidWorks
* **Tools:** Docker, Git

Awards & Achievements
======
* 1st in Acceleration and 3rd Overall, Formula Green 2020 (Formula Student competition).
* MCM Scholarship, IIT Roorkee (2 years).
* All India Rank 1986 in JEE Advanced 2016 among 150,000 candidates.

Service & Outreach
======
* Mentored seven first-year Mechanical and Industrial Engineering students (Student Mentorship Program, IIT Roorkee).
* Taught high school students and organized blood donation camps (National Service Scheme); led a mushroom-farming training initiative under Unnat Bharat Abhiyan.
