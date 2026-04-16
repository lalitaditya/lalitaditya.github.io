---
layout: page
title: "Education"
permalink: /education/
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
    align-items: center;
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
    opacity: 0.12;
    line-height: 1;
    pointer-events: none;
    user-select: none;
  }
</style>

<p class="exp-label">03 / Foundation</p>
<p class="exp-intro">From electronics engineering in India to robotics and now a Ph.D. in computer science at Minnesota, each step deepened my understanding of how machines perceive, decide, and communicate. The throughline: building systems that bridge the physical and digital worlds.</p>

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

    <!-- ── PES University: above the wave, dot at left trough (16.6%) ── -->
    <div class="wave-entry wave-above" style="left: 16.6%; top: 500px;">
      <div class="tl-card">
        <div class="tl-card-header">
          <h3>PES University</h3>
          <span class="tl-location">Bengaluru, India</span>
        </div>
        <span class="tl-role">Bachelor of Technology in Electronics and Communication Engineering</span>
        <ul class="tl-desc">
          <li><em>Relevant coursework: Embedded Systems, Signal Processing, Digital Communications, IoT, Python, C++</em></li>
        </ul>
      </div>
      <span class="tl-date">Aug 2019 — May 2023</span>
      <div class="we-stem"></div>
      <div class="we-dot"></div>
    </div>

    <!-- ── UMN MS: below the wave, dot at center peak (50%) ── -->
    <div class="wave-entry wave-below" style="left: 50%; top: 300px;">
      <div class="we-dot"></div>
      <div class="we-stem"></div>
      <span class="tl-date">Sep 2023 — May 2025</span>
      <div class="tl-card">
        <div class="tl-card-header">
          <h3>University of Minnesota</h3>
          <span class="tl-location">Twin Cities, MN</span>
        </div>
        <span class="tl-role">Master of Science in Robotics</span>
        <ul class="tl-desc">
          <li><em>Relevant coursework: Robot Motion Planning, Computer Vision, Machine Learning, Control Systems, ROS/ROS 2</em></li>
        </ul>
      </div>
    </div>

    <!-- ── UMN PhD: above the wave, dot at right trough (83.3%) ── -->
    <div class="wave-entry wave-above" style="left: 83.3%; top: 500px;">
      <div class="tl-card">
        <div class="tl-card-header">
          <h3>University of Minnesota</h3>
          <span class="tl-location">Twin Cities, MN</span>
        </div>
        <span class="tl-role">Doctor of Philosophy in Computer Science</span>
        <ul class="tl-desc">
          <li>Advisor: Dr. Zhi-Li Zhang</li>
          <li>Developing an AI-powered digital twin for CAVs that leverages ray tracing to predict network behavior, ensuring safe, reliable, real-time remote and cooperative driving over 5G/NextG and C-V2X.</li>
        </ul>
      </div>
      <span class="tl-date">Jan 2025 — Dec 2027</span>
      <div class="we-stem"></div>
      <div class="we-dot"></div>
    </div>

  </div>
</div>
