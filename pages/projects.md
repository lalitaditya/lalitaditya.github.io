---
layout: page
title: "Projects"
permalink: /projects/
---

<style>
  .page-content { max-width: 775px; }
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

  .projects-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 25px;
    margin-top: 1.5rem;
  }

  .proj-tile {
    background: white;
    border-radius: 16px;
    padding: 18px 20px;
    box-shadow: 0 4px 24px rgba(0,0,0,0.07), 0 1px 4px rgba(0,0,0,0.04);
    position: relative;
    overflow: hidden;
    transition: transform 0.2s ease, box-shadow 0.2s ease;
    display: flex;
    flex-direction: column;
  }
  .proj-tile-desc { flex: 1; }
  .proj-tile-foot-end {
    margin-top: auto;
  }

  .proj-tile h3 {
    font-size: 0.95rem;
    font-weight: 700;
    color: #2c2c2c;
    margin: 0 0 4px;
  }
  .proj-tile-tags {
    font-size: 9px;
    font-weight: 700;
    letter-spacing: 1.5px;
    text-transform: uppercase;
    color: #7c6ff7;
    margin-bottom: 10px;
    display: block;
  }
  .proj-tile-desc {
    font-size: 0.8rem;
    color: #6b6b6b;
    line-height: 1.6;
    margin: 0;
    display: block;
  }
  .proj-tile-icon {
    position: absolute;
    right: -10px;
    bottom: -10px;
    font-size: 150px;
    opacity: 0.12;
    line-height: 1;
    pointer-events: none;
    user-select: none;
  }
  .proj-tile-foot {
    display: inline-flex;
    align-items: center;
    gap: 6px;
    margin-top: 12px;
    font-size: 0.85rem;
    font-weight: 600;
  }
  .proj-tile-foot i {
    font-size: 1.5rem;
    color: #2c2c2c;
  }
  .proj-tile-cta {
    color: #5bc8af;
    text-decoration: none;
    transition: color 0.15s ease, transform 0.15s ease;
    display: inline-block;
  }
  .proj-tile-cta:hover {
    color: #3fa88f;
    transform: translateX(2px);
  }
  .proj-tile-desc ul {
    margin: 0;
    padding-left: 18px;
  }
  .proj-tile-desc li {
    font-size: 0.8rem;
    color: #6b6b6b;
    line-height: 1.6;
    margin-bottom: 4px;
  }

</style>

<p class="exp-label">04 / Build</p>
<p class="exp-intro">Research prototypes, testbeds, and systems that started on a whiteboard and ended up running on real hardware. Most of these lived at the boundary of simulation and the physical world, and the most useful ones taught me something when they broke.</p>

<div class="projects-grid" markdown="0">
  <div class="proj-tile">
    <h3>NextGDT: Ray-Tracing Digital Twin</h3>
    <span class="proj-tile-tags">NVIDIA Sionna &middot; Ray Tracing &middot; 5G/NextG &middot; Digital Twin</span>
    <div class="proj-tile-desc">
      <ul>
        <li>Leading Sony-sponsored project building AI-driven 3D mapping and ray-tracing digital twins for 5G/NextG network optimization</li>
        <li>Dynamic scene reconstruction with multi-sensor validation using NVIDIA Sionna</li>
        <li>Physically accurate channel modeling for in-the-loop sensor-environment simulation</li>
      </ul>
    </div>
  </div>
  <div class="proj-tile">
    <h3>C-V2X Testbed for Rural Intersections</h3>
    <span class="proj-tile-tags">C-V2X &middot; PC5 &middot; OBU/RSU &middot; Conflict Detection &middot; Safety</span>
    <div class="proj-tile-desc">
      <ul>
        <li>Engineered low-cost C-V2X prototype (OBU-RSU, PC5) for conflict detection and priority warnings</li>
        <li>Profiled latency, PRR, and jitter under varied traffic loads for scalable crash-risk reduction</li>
        <li>Designed for rural intersection deployment with minimal infrastructure</li>
      </ul>
    </div>
  </div>
  <div class="proj-tile">
    <h3>5G Teleoperation Pipeline for AVs</h3>
    <span class="proj-tile-tags">5G NR &middot; Teleoperation &middot; ROS 2 &middot; Autoware &middot; QoS</span>
    <div class="proj-tile-desc">
      <ul>
        <li>Built end-to-end teleoperation pipeline streaming multi-camera AV data to remote operators over 5G</li>
        <li>Measured latency/QoS during mobility and handovers on commercial networks</li>
        <li>Developed safety layer for seamless switchover between autonomy and human-in-loop control</li>
      </ul>
    </div>
  </div>
  <div class="proj-tile">
    <h3>AutoMap: Autonomous Factory Mapping</h3>
    <span class="proj-tile-tags">ROS &middot; Gazebo &middot; SLAM &middot; TurtleBot &middot; Nokia</span>
    <div class="proj-tile-desc">
      <ul>
        <li>Led ROS/Gazebo-driven SLAM system using TurtleBot with LiDAR and camera for autonomous mapping</li>
        <li>Navigation stack tuning and autonomous SLAM to remove manual mapping workflows</li>
        <li>Produced DT-ready point clouds for site-scale planning, deployed in Nokia factories</li>
      </ul>
    </div>
  </div>
</div>
