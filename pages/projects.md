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
  }
  .proj-tile:hover {
    transform: translateY(-4px);
    box-shadow: 0 8px 32px rgba(0,0,0,0.10), 0 2px 8px rgba(0,0,0,0.06);
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
    right: -6px;
    bottom: -6px;
    font-size: 60px;
    opacity: 0.05;
    line-height: 1;
    pointer-events: none;
    user-select: none;
  }

</style>

<p class="exp-label">04 / Build</p>
<p class="exp-intro">A selection of things I've built, broken, and occasionally shipped.</p>

<div class="projects-grid" markdown="0">
  <div class="proj-tile">
    <h3>Project One</h3>
    <span class="proj-tile-tags">Python · NLP · BERTopic</span>
    <span class="proj-tile-desc">Placeholder description for the first project. Details coming soon.</span>
    <span class="proj-tile-icon">🔬</span>
  </div>
  <div class="proj-tile">
    <h3>Project Two</h3>
    <span class="proj-tile-tags">RAG · LLMs · FastAPI</span>
    <span class="proj-tile-desc">Placeholder description for the second project. Details coming soon.</span>
    <span class="proj-tile-icon">🤖</span>
  </div>
  <div class="proj-tile">
    <h3>Project Three</h3>
    <span class="proj-tile-tags">SQL · Tableau · Airflow</span>
    <span class="proj-tile-desc">Placeholder description for the third project. Details coming soon.</span>
    <span class="proj-tile-icon">📊</span>
  </div>
  <div class="proj-tile">
    <h3>Project Four</h3>
    <span class="proj-tile-tags">React · Flask · Vercel</span>
    <span class="proj-tile-desc">Placeholder description for the fourth project. Details coming soon.</span>
    <span class="proj-tile-icon">🚀</span>
  </div>
</div>
