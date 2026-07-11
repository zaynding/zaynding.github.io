---
permalink: /
author_profile: true
redirect_from:
  - /about/
  - /about.html
---
{% include about-homepage-header.html %}

I am an undergraduate in Information Engineering at Xidian University (2025-2029).

My interests lie in embodied intelligence, multimodal perception, and trustworthy machine learning.

I enjoy building end-to-end systems that connect perception, learning, and real-world hardware.

News
---------------
<section class="profile-list-section">
  <ul class="profile-list">
    <li class="profile-list__item">
      <span class="profile-list__date">2026/05</span>
      <span class="profile-list__content">Won the Second Prize in the TI Cup Shaanxi Intercollegiate Engineering League.</span>
    </li>
    <li class="profile-list__item">
      <span class="profile-list__date">2026/05</span>
      <span class="profile-list__content">Won the Grand Prize in the TI Cup Electronic Design Competition at Xidian University.</span>
    </li>
  </ul>
</section>

Experience
--------------

<div class="experience-container">
  <div class="experience-card">
      <img src="https://selen-suyue.github.io/images/XDU.png" alt="Xidian University logo" class="experience-logo">
      <div class="experience-info">
          <strong>Xidian University</strong><br>
          Sep 2025 - June 2029<br>
          B.Eng. in Information Engineering<br>
          School of Telecommunications Engineering
      </div>
  </div>
</div>

Projects
--------
<div class="publication-card featured">
  <div style="display: flex; align-items: center;">
    <img src="https://selen-suyue.github.io/images/maniunicon.png" alt="LeRobot project" width="200" height="120" style="margin-right: 20px; object-fit: cover;">
    <div>
      <strong>LeRobot End-to-End Manipulation Platform</strong><br>
      Built an end-to-end robot manipulation platform using LeRobot, covering hardware integration, servo and camera calibration, demonstration collection, policy training, inference, and evaluation.<br><br>
      Integrated a node-based workflow interface with task configuration, code generation, system execution, and robot deployment, enabling non-specialist users to operate the complete pipeline.<br><br>
      <strong>Role:</strong> Mechanical assembly, low-level calibration, workflow development, and system integration.<br>
      <b><i style="color:#83a1c7;">Embodied Intelligence &middot; Robot Learning &middot; System Integration</i></b><br>
      <em>First Prize, Northwest Region, China Collegiate Computing Competition</em><br>
      <em>Grand Prize, Xinghuo Cup</em>
    </div>
  </div>
</div>

<div class="project-card">
  <div style="display: flex; align-items: center;">
    <img src="https://selen-suyue.github.io/images/U_pre_pipeline.png" alt="Vision-guided tracking" width="200" height="120" style="margin-right: 20px; object-fit: cover;">
    <div>
      <strong>Vision-Guided Gimbal Tracking System</strong><br>
      Built a closed-loop target-tracking system integrating YOLO-based recognition, image-coordinate error estimation, Raspberry Pi-MCU communication, and two-axis gimbal control.<br>
      I was responsible for the vision-control module and converted pixel error into control input. Improved tracking robustness through camera calibration, multi-frame target confirmation, target-loss handling, and closed-loop debugging.<br>
      <b><i style="color:#83a1c7;">Computer Vision &middot; Embedded Systems &middot; Closed-Loop Control</i></b>
    </div>
  </div>
</div>

<div class="project-card">
  <div style="display: flex; align-items: center;">
    <img src="https://selen-suyue.github.io/images/FGSM3D.png" alt="Scientific image detection" width="200" height="120" style="margin-right: 20px; object-fit: cover;">
    <div>
      <strong>&gamma;-H2AX Microscopy Object Detection</strong><br>
      Constructed a YOLO11 dataset for high-noise &gamma;-H2AX microscopy images using Label Studio and trained a lightweight detector for automated object localization.<br>
      I independently completed precise bounding-box annotation and YOLO-format dataset construction. Evaluated precision, recall, and representative failure cases under varying image quality.<br>
      <b><i style="color:#83a1c7;">Scientific Imaging &middot; Object Detection &middot; Dataset Construction</i></b>
    </div>
  </div>
</div>

<h3>Additional Implementations</h3>
<section class="profile-list-section">
  <ul class="profile-list">
    <li class="profile-list__item">
      <span class="profile-list__date">CNN</span>
      <span class="profile-list__content">
        <strong>CNN Architecture Reproduction</strong><br>
        Implemented AlexNet, VGG, and ResNet from scratch in PyTorch using ImageNet and a self-built dataset, covering preprocessing, training, validation, checkpointing, and single-image inference.<br>
        Improved unstable VGG training through Kaiming initialization, with test accuracy reaching approximately 93%.<br>
        <i>PyTorch &middot; Image Classification &middot; Model Reproduction</i>
      </span>
    </li>
  </ul>
</section>

Awards
--------
<section class="profile-list-section">
  <ul class="profile-list">
    <li class="profile-list__item">
      <span class="profile-list__date">2026/05</span>
      <span class="profile-list__content">Second Prize, TI Cup Shaanxi Intercollegiate Engineering League</span>
    </li>
    <li class="profile-list__item">
      <span class="profile-list__date">2026/05</span>
      <span class="profile-list__content">Grand Prize, TI Cup Electronic Design Competition, Xidian University</span>
    </li>
    <li class="profile-list__item">
      <span class="profile-list__date">2026</span>
      <span class="profile-list__content">First Prize, Northwest Region, China Collegiate Computing Competition</span>
    </li>
    <li class="profile-list__item">
      <span class="profile-list__date">2026</span>
      <span class="profile-list__content">Grand Prize, Xinghuo Cup, School of Telecommunications Engineering</span>
    </li>
  </ul>
</section>

Skills
--------
<section class="profile-list-section">
  <ul class="profile-list">
    <li class="profile-list__item"><span class="profile-list__date">Code</span><span class="profile-list__content">Python, C, PyTorch, OpenCV</span></li>
    <li class="profile-list__item"><span class="profile-list__date">AI</span><span class="profile-list__content">Model training and evaluation, object detection, data annotation</span></li>
    <li class="profile-list__item"><span class="profile-list__date">System</span><span class="profile-list__content">Ubuntu, command-line tools, embedded development, hardware debugging</span></li>
    <li class="profile-list__item"><span class="profile-list__date">Robot</span><span class="profile-list__content">Assembly, sensor setup, calibration, closed-loop control, deployment</span></li>
  </ul>
</section>
