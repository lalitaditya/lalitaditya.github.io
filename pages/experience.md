---
layout: page
title: "Experience"
permalink: /experience/
---

<style>
  .page-content { max-width: 775px !important; }
  .page-content h1 { display: none; }

  .exp-label {
    font-size: 18px;
    font-weight: 800;
    letter-spacing: 3px;
    background: linear-gradient(to right, #5bc8af, #7c6ff7);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
    text-transform: uppercase;
    margin-bottom: 6px;
    display: inline-block;
  }
  .exp-intro {
    font-size: 1rem;
    color: #6b6b6b;
    max-width: 1000px;
    line-height: 1.5;
    margin: 0 0 1.5rem;
    text-align: justify;
  }

  /* ── Full-width breakout for wave timeline ───────── */
  .wave-wrap {
    width: 100vw;
    margin-left: calc(-50vw + 50%);
    padding: 0 40px;
    box-sizing: border-box;
    overflow-x: auto;
  }

  /* ── Wave timeline container ─────────────────────── */
  .wave-timeline {
    position: relative;
    width: 100%;
    min-width: 1300px;
    height: 720px;
    margin: -100px 0px 0px;
  }

  .wave-svg {
    position: absolute;
    top: 280px;
    left: 0;
    width: 100%;
    height: 240px;
    pointer-events: none;
    z-index: 1;
  }

  .wave-entry {
    position: absolute;
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 480px;
    z-index: 2;
  }
  .wave-above {
    transform: translate(-50%, calc(-100% + 7px));
  }
  .wave-below {
    transform: translate(-50%, -7px);
  }

  .we-dot {
    width: 14px;
    height: 14px;
    background: #7c6ff7;
    border-radius: 50%;
    border: 3px solid #f7f7f5;
    box-shadow: 0 0 0 2px #7c6ff7;
    flex-shrink: 0;
    z-index: 3;
  }

  .we-stem {
    width: 2px;
    height: 100px;
    background: #7c6ff7;
    flex-shrink: 0;
  }

  .tl-date {
    display: inline-flex;
    align-items: center;
    background: linear-gradient(90deg, #7c6ff7, #8b84f8);
    color: white;
    font-size: 11px;
    font-weight: 700;
    padding: 6px 16px;
    border-radius: 50px;
    white-space: nowrap;
    letter-spacing: 0.4px;
    box-shadow: 0 3px 10px rgba(124, 111, 247, 0.3);
    position: absolute;
    left: 50%;
    transform: translateX(-50%);
    z-index: 4;
  }
  .wave-above .tl-date {
    top: calc(100% + 8px);
  }
  .wave-below .tl-date {
    bottom: calc(100% + 8px);
  }

  .tl-card {
    background: white;
    border-radius: 16px;
    padding: 22px 26px;
    box-shadow: 0 4px 24px rgba(0,0,0,0.07), 0 1px 4px rgba(0,0,0,0.04);
    position: relative;
    overflow: hidden;
    width: 100%;
    box-sizing: border-box;
  }
  .tl-card-header {
    display: flex;
    justify-content: space-between;
    align-items: baseline;
    gap: 8px;
    margin-bottom: 3px;
  }
  .tl-card h3 {
    font-size: 0.95rem;
    font-weight: 700;
    color: #2c2c2c;
    margin: 0;
  }
  .tl-location {
    font-size: 0.8rem;
    color: #aaa;
    white-space: nowrap;
    flex-shrink: 0;
  }
  .tl-role {
    font-size: 9px;
    font-weight: 700;
    letter-spacing: 1.5px;
    text-transform: uppercase;
    color: #7c6ff7;
    display: block;
    margin-bottom: 10px;
  }
  .tl-desc {
    font-size: 0.78rem;
    color: #6b6b6b;
    line-height: 1.65;
    margin: 0;
    padding-left: 14px;
  }
  .tl-desc li { margin-bottom: 5px; }
  .tl-card-icon {
    position: absolute;
    right: -10px;
    bottom: -10px;
    font-size: 110px;
    opacity: 0.22;
    line-height: 1;
    pointer-events: none;
    user-select: none;
  }
  .tl-card-img-icon {
    position: absolute;
    right: -10px;
    bottom: -10px;
    width: 150px;
    height: 150px;
    object-fit: contain;
    opacity: 0.22;
    pointer-events: none;
    user-select: none;
  }
</style>

<p class="exp-label">02 / Journey</p>
<p class="exp-intro">From autonomous factory mapping at Nokia to building C-V2X testbeds and 5G teleoperation pipelines at the University of Minnesota, I've been engineering systems at the intersection of robotics, networking, and real-time autonomy. Each role taught me something different about making machines perceive, decide, and communicate in the physical world.</p>

<div class="wave-wrap">
  <div class="wave-timeline">

    <svg class="wave-svg" viewBox="0 0 1000 240" preserveAspectRatio="none">
      <defs>
        <linearGradient id="waveGrad" x1="0%" y1="0%" x2="100%" y2="0%">
          <stop offset="0%" stop-color="#5bc8af"/>
          <stop offset="100%" stop-color="#7c6ff7"/>
        </linearGradient>
      </defs>
      <path d="M 0 120 Q 166 320 333 120 Q 500 -80 666 120 Q 833 320 1000 120"
            stroke="url(#waveGrad)" stroke-width="3" fill="none" stroke-linecap="round"/>
    </svg>

    <!-- ── Nokia: above the wave, dot at left trough (16.6%) ── -->
    <div class="wave-entry wave-above" style="left: 16.6%; top: 500px;">
      <div class="tl-card">
        <div class="tl-card-header">
          <h3>NOKIA / NOKIA Bell Labs</h3>
          <span class="tl-location">Bengaluru, India</span>
        </div>
        <span class="tl-role">Student Project Intern</span>
        <ul class="tl-desc">
          <li>Led development of AutoMap, a ROS/Gazebo-driven SLAM system using TurtleBot, LiDAR, and camera data for autonomous mapping and navigation.</li>
          <li>Produced DT-ready point clouds for site-scale planning and 3D environment modeling, deployed in Nokia factories.</li>
        </ul>
      </div>
      <span class="tl-date">Feb 2021 — Dec 2022</span>
      <div class="we-stem"></div>
      <div class="we-dot"></div>
    </div>

    <!-- ── PwC: below the wave, dot at center peak (50%) ── -->
    <div class="wave-entry wave-below" style="left: 50%; top: 300px;">
      <div class="we-dot"></div>
      <div class="we-stem"></div>
      <span class="tl-date">Jan 2023 — Jul 2023</span>
      <div class="tl-card">
        <div class="tl-card-header">
          <h3>PricewaterhouseCoopers (PwC)</h3>
          <span class="tl-location">Kolkata, India</span>
        </div>
        <span class="tl-role">Intern — Technology Consulting</span>
        <ul class="tl-desc">
          <li>Engineered Metaverse POCs using Unreal, Unity, and Blender to create immersive client experiences.</li>
          <li>Pioneered Python automation in Blender with LLMs to generate 3D models from text inputs, boosting efficiency through GenAI tools.</li>
        </ul>
        <img src="/assets/img/pwc.png" class="tl-card-img-icon" alt="">
      </div>
    </div>

    <!-- ── UMN GRA: above the wave, dot at right trough (83.3%) ── -->
    <div class="wave-entry wave-above" style="left: 83.3%; top: 500px;">
      <div class="tl-card">
        <div class="tl-card-header">
          <h3>University of Minnesota</h3>
          <span class="tl-location">Minneapolis, MN</span>
        </div>
        <span class="tl-role">Graduate Research Assistant</span>
        <ul class="tl-desc">
          <li>Leading Sony Digital Twin (NextGDT) project developing AI-driven 3D mapping and ray-tracing digital twins to optimize 5G/NextG networks with NVIDIA Sionna.</li>
          <li>Engineered C-V2X prototypes (OBU-RSU, PC5) for conflict detection, priority warnings; profiled latency, PRR, and jitter.</li>
          <li>Built AV testbeds (ROS 2 + Autoware) with LiDAR-camera-GNSS fusion, HD maps (SLAM), and planning-focused autonomy.</li>
          <li>Developed a 5G/NextG teleoperation pipeline with latency/QoS measurements under mobility and handovers.</li>
        </ul>
      </div>
      <span class="tl-date">May 2024 — Present</span>
      <div class="we-stem"></div>
      <div class="we-dot"></div>
    </div>

  </div>
</div>
