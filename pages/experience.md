---
layout: page
title: "Experience"
permalink: /experience/
---

<style>
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
    font-size: 0.87rem;
    color: #6b6b6b;
    max-width: 600px;
    line-height: 1.5;
    margin: 0 0 3.5rem;
    text-align: justify;
  }

  /* ── Full-width breakout ─────────────────────────── */
  .timeline-h-wrap {
    overflow-x: auto;
    padding-bottom: 24px;
    width: 100vw;
    margin-left: calc(-50vw + 50%);
    padding-left: 40px;
    padding-right: 40px;
    box-sizing: border-box;
  }

  .timeline-h {
    display: flex;
    flex-direction: column;
    min-width: 700px;
  }

  /* ── Above row ───────────────────────────────────── */
  /* All content that sits above the axis (cards + dates for above-items,
     just dates for below-items). justify-content: flex-end anchors
     everything to the bottom so dates always land right above the dots. */
  .tl-above-row {
    display: flex;
  }
  .tl-above-item {
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: flex-end;
    padding: 0 10px;
  }

  /* ── Axis row (line + dots) ──────────────────────── */
  .tl-axis-row {
    display: flex;
    position: relative;
    height: 14px;
    z-index: 1;
  }
  /* The gradient line — sits behind the dots */
  .tl-axis-row::before {
    content: '';
    position: absolute;
    left: 0; right: 0;
    top: 50%;
    height: 2px;
    transform: translateY(-50%);
    background: linear-gradient(to right, #5bc8af, #7c6ff7);
    z-index: 1;
  }
  .tl-axis-dot {
    flex: 1;
    display: flex;
    justify-content: center;
    align-items: center;
    z-index: 2; /* dots sit on top of the line */
  }

  /* ── Below row ───────────────────────────────────── */
  .tl-below-row {
    display: flex;
  }
  .tl-below-item {
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: flex-start;
    padding: 0 10px;
  }

  /* ── Stem ────────────────────────────────────────── */
  .tl-stem {
    width: 2px;
    height: 36px;
    background: #7c6ff7;
    flex-shrink: 0;
  }

  /* ── Dot ─────────────────────────────────────────── */
  .tl-dot {
    width: 14px;
    height: 14px;
    background: #7c6ff7;
    border-radius: 50%;
    border: 3px solid #f7f7f5;
    box-shadow: 0 0 0 2px #7c6ff7;
    flex-shrink: 0;
  }

  /* ── Date pill ───────────────────────────────────── */
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
    margin-bottom: 8px;
  }

  /* ── Card ────────────────────────────────────────── */
  .tl-card {
    background: white;
    border-radius: 16px;
    padding: 22px 26px;
    box-shadow: 0 4px 24px rgba(0,0,0,0.07), 0 1px 4px rgba(0,0,0,0.04);
    position: relative;
    overflow: hidden;
    width: 100%;
    box-sizing: border-box;
    margin-bottom: 12px;
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
    right: -6px;
    bottom: -6px;
    font-size: 60px;
    opacity: 0.05;
    line-height: 1;
    pointer-events: none;
    user-select: none;
  }
</style>

<p class="exp-label">01 / Journey</p>
<p class="exp-intro">I've shipped AI products, defined requirements, run user feedback sessions, and written the pipelines that powered them, sometimes all in the same week. At Stanford, I built data infrastructure from scratch and had to sell it before it existed. That combination of knowing what to build and how to build it tends to follow me everywhere. Still not sure if that's a skill or a personality flaw.</p>

<div class="timeline-h-wrap">
  <div class="timeline-h">

    <!-- ── Above row ── -->
    <div class="tl-above-row">

      <!-- PwC: card → date → stem (all anchored to bottom) -->
      <div class="tl-above-item">
        <div class="tl-card">
          <div class="tl-card-header">
            <h3>PricewaterhouseCoopers (PwC)</h3>
            <span class="tl-location">Kolkata, India</span>
          </div>
          <span class="tl-role">Associate, One Consulting – Emerging Tech</span>
          <ul class="tl-desc">
            <li>Deployed production RAG-based LLM product; launched MVP in 3 weeks, saving ~$180K annually.</li>
            <li>Owned backend dev and prompt engineering; designed agentic workflows across multiple LLM APIs.</li>
            <li>Drove user adoption via feedback sessions; shipped features improving output accuracy by ~40%.</li>
            <li>Authored PRDs and conducted competitive analysis across 20+ industries to validate GenAI use cases.</li>
          </ul>
          <span class="tl-card-icon">💼</span>
        </div>
        <span class="tl-date">Jan 2023 — Aug 2024</span>
        <div class="tl-stem"></div>
      </div>

      <!-- HEAL Lab: just date (anchored to bottom, right above dot) -->
      <div class="tl-above-item">
        <span class="tl-date">Oct 2024 — May 2025</span>
      </div>

      <!-- Haas: card → date → stem -->
      <div class="tl-above-item">
        <div class="tl-card">
          <div class="tl-card-header">
            <h3>Haas Center for Public Service</h3>
            <span class="tl-location">Stanford, CA</span>
          </div>
          <span class="tl-role">Data Analyst</span>
          <ul class="tl-desc">
            <li>Built SQL/Python pipelines and Tableau dashboards across 15 programs serving 1,500+ students.</li>
            <li>Applied crawl-walk-run model to drive adoption; secured stakeholder buy-in for program-wide migration.</li>
            <li>Developed Airtable matching system with Airflow orchestration; reduced manual effort across 1,500+ records.</li>
          </ul>
          <span class="tl-card-icon">📊</span>
        </div>
        <span class="tl-date">Dec 2025 — Present</span>
        <div class="tl-stem"></div>
      </div>

    </div>

    <!-- ── Axis row (dots on the line) ── -->
    <div class="tl-axis-row">
      <div class="tl-axis-dot"><div class="tl-dot"></div></div>
      <div class="tl-axis-dot"><div class="tl-dot"></div></div>
      <div class="tl-axis-dot"><div class="tl-dot"></div></div>
    </div>

    <!-- ── Below row ── -->
    <div class="tl-below-row">

      <!-- PwC: nothing below -->
      <div class="tl-below-item"></div>

      <!-- HEAL Lab: stem → card -->
      <div class="tl-below-item">
        <div class="tl-stem"></div>
        <div class="tl-card">
          <div class="tl-card-header">
            <h3>HEAL Lab, School of Medicine</h3>
            <span class="tl-location">Stanford, CA</span>
          </div>
          <span class="tl-role">Research Associate</span>
          <ul class="tl-desc">
            <li>Built NLP pipelines analyzing 500+ unstructured clinical records; reduced manual review effort at scale.</li>
            <li>Synthesized behavioral insights for interdisciplinary teams, informing improvements in care delivery workflows.</li>
          </ul>
          <span class="tl-card-icon">🧬</span>
        </div>
      </div>

      <!-- Haas: nothing below -->
      <div class="tl-below-item"></div>

    </div>

  </div>
</div>
