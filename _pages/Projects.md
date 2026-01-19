---
layout: archive
title: "Projects"
permalink: /Projects/
author_profile: true
---

{% include base_path %}

<style>
.project-item{
  display:flex;
  gap:18px;
  align-items:flex-start;
  margin: 0 0 22px 0;
}
.project-fig{
  flex: 0 0 170px;
}
.project-fig img{
  width: 170px;
  height: auto;
  border: 1px solid #ddd;
  border-radius: 6px;
}
.project-body{
  flex: 1 1 auto;
}
.project-title{
  margin: 0 0 6px 0;
  line-height: 1.25;
}
.project-meta{
  margin: 0 0 8px 0;
  font-size: 0.95em;
  opacity: 0.85;
}
.project-abstract{
  margin: 0;
}
@media (max-width: 640px){
  .project-item{ flex-direction: column; }
  .project-fig{ flex-basis:auto; }
  .project-fig img{ width: 100%; max-width: 320px; }
}
</style>

<div class="project-item">
  <div class="project-fig">
    <img src="{{ base_path }}/assets/images/projects/probefly.jpg" alt="ProbeFly cover">
  </div>
  <div class="project-body">
    <h3 class="project-title">ProbeFly <span style="font-weight:normal;">| <em>Principal Investigator</em></span></h3>
    <p class="project-meta"><em>Jun. 2025 – Present</em></p>
    <p class="project-abstract">
      <strong>ProbeFly: Minimal-Sensor Micro-UAVs for Adaptive Nuclear Confined Space Exploration</strong> (RAICo, £10k).
      The project develops micro-UAV autonomy for confined and degraded nuclear environments with minimal sensing,
      focusing on robust navigation, safety-aware control, and learning-based adaptation under uncertainty and partial observability.
    </p>
  </div>
</div>

<div class="project-item">
  <div class="project-fig">
    <img src="{{ base_path }}/assets/images/projects/raico_theme2.jpg" alt="RAICo Theme 2">
  </div>
  <div class="project-body">
    <h3 class="project-title">RAICo <span style="font-weight:normal;">| <em>Co-Investigator</em></span></h3>
    <p class="project-meta"><em>Apr. 2024 – Jun. 2025</em></p>
    <p class="project-abstract">
      <strong>Theme 2: Suppressing Task-Space Vibrations in Robotic Manipulators on a Flexible Platform</strong>
      (RAICo / Sellafield Ltd. / NDA, £150k).
      This project targets vibration-aware planning and control for long-reach robot manipulation on flexible bases,
      enabling safer, faster task execution and improved stability in nuclear decommissioning scenarios.
    </p>
  </div>
</div>

<div class="project-item">
  <div class="project-fig">
    <img src="{{ base_path }}/assets/images/projects/ampi.jpg" alt="AMPI project">
  </div>
  <div class="project-body">
    <h3 class="project-title">AMPI <span style="font-weight:normal;">| <em>Key Researcher</em></span></h3>
    <p class="project-meta"><em>Mar. 2024 – Feb. 2025</em></p>
    <p class="project-abstract">
      <strong>Development of safe learning for manipulator with soft-rigid end-effector</strong>
      (Advanced Machinery &amp; Productivity Initiative, UKRI &amp; NPL, £22.6M).
      The work investigates safe learning-based control and compliant manipulation using soft-rigid end-effectors,
      combining data-efficient adaptation with safety constraints for real-world deployment.
    </p>
  </div>
</div>

<div class="project-item">
  <div class="project-fig">
    <img src="{{ base_path }}/assets/images/projects/longops.jpg" alt="LongOps project">
  </div>
  <div class="project-body">
    <h3 class="project-title">LongOps <span style="font-weight:normal;">| <em>Key Researcher</em></span></h3>
    <p class="project-meta"><em>Jul. 2022 – Sep. 2023</em></p>
    <p class="project-abstract">
      <strong>Challenge 3: Modelling and control of a long flexible manipulator</strong>; 
      <strong>Challenge 4: Teleoperation with Digital Twins</strong>
      (SBRI – digital technologies for robotic nuclear decommissioning, UKAEA, total £300k).
      The project advances modeling, trajectory planning, and vibration suppression for flexible long-reach systems,
      and develops digital-twin-enabled teleoperation for safer remote operations.
    </p>
  </div>
</div>

<div class="project-item">
  <div class="project-fig">
    <img src="{{ base_path }}/assets/images/projects/rain.jpg" alt="RAIN / RAIN+">
  </div>
  <div class="project-body">
    <h3 class="project-title">RAIN and RAIN+ <span style="font-weight:normal;">| <em>Key Researcher</em></span></h3>
    <p class="project-meta"><em>Jan. 2022 – Jun. 2022</em></p>
    <p class="project-abstract">
      <strong>Robotics and Artificial Intelligence for Nuclear (RAIN)</strong> (EPSRC, £12.8M) and
      <strong>Robotics and Artificial Intelligence for Nuclear Plus (RAIN+)</strong> (EPSRC, £1.98M).
      Contributed to robotics and AI research translation for nuclear decommissioning, supporting autonomous inspection,
      remote intervention, and reliable deployment in hazardous environments.
    </p>
  </div>
</div>

<div class="project-item">
  <div class="project-fig">
    <img src="{{ base_path }}/assets/images/projects/adaptit.jpg" alt="ADAPT-IT">
  </div>
  <div class="project-body">
    <h3 class="project-title">ADAPT-IT <span style="font-weight:normal;">| <em>Key Researcher</em></span></h3>
    <p class="project-meta"><em>Sep. 2017 – Dec. 2021</em></p>
    <p class="project-abstract">
      <strong>Reducing vehicle carbon emissions through development of a compact, efficient and intelligent powertrain</strong>
      (Advanced Propulsion Centre UK, £3.9M).
      The project developed adaptive estimation and learning-based optimal control methods for engine and powertrain systems,
      improving performance and emissions robustness under uncertainty and transient operating conditions.
    </p>
  </div>
</div>

<div class="project-item">
  <div class="project-fig">
    <img src="{{ base_path }}/assets/images/projects/aece.jpg" alt="AECE">
  </div>
  <div class="project-body">
    <h3 class="project-title">AECE <span style="font-weight:normal;">| <em>Key Researcher</em></span></h3>
    <p class="project-meta"><em>Sep. 2015 – Dec. 2017</em></p>
    <p class="project-abstract">
      <strong>Adaptive optimal estimation and control for automotive engine systems with approximate dynamic programming</strong>
      (EU FP7 Marie-Curie Fellowship, €231k; with Prof. Jing Na and Prof. Guido Herrmann).
      The project investigated adaptive optimal control and reinforcement learning for engine systems,
      combining estimation, stability analysis, and real-time learning for practical implementation.
    </p>
  </div>
</div>

