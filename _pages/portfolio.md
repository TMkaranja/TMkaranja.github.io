---
layout: single
title: "Selected Work"
permalink: /portfolio/
classes: wide
author_profile: true
---

<div class="portfolio-filter">
  <button class="btn btn--primary filter-btn active" data-filter="all">All</button>
  <button class="btn btn--primary filter-btn" data-filter="development">Development</button>
  <button class="btn btn--primary filter-btn" data-filter="design">Design</button>
  <button class="btn btn--primary filter-btn" data-filter="mobile">Mobile</button>
</div>

<style>
.portfolio-filter {
  display: flex;
  gap: 10px;
  justify-content: center;
  margin-bottom: 40px;
  flex-wrap: wrap;
}
.filter-btn {
  transition: all 0.3s ease;
}
.filter-btn.active {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  transform: scale(1.05);
}
</style>

## 🚀 Featured Projects

<div class="projects-grid" markdown="1">

<div class="project-card" data-category="development design">
  <img src="/assets/images/project1-thumb.jpg" alt="E-Commerce Platform">
  <div class="project-overlay">
    <h3>E-Commerce Platform</h3>
    <p>Full-stack solution with React, Node.js & Stripe</p>
    <div class="project-stats">
      <span>⭐ 245</span>
      <span>🔀 67</span>
    </div>
    <div class="project-links">
      <a href="https://github.com/yourusername/project1" class="btn btn--small">Code</a>
      <a href="https://project1-demo.com" class="btn btn--small btn--primary">Live Demo</a>
    </div>
  </div>
</div>

<div class="project-card" data-category="mobile design">
  <img src="/assets/images/project2-thumb.jpg" alt="Fitness App">
  <div class="project-overlay">
    <h3>FitTrack Pro</h3>
    <p>React Native fitness app with AI-powered workouts</p>
    <div class="project-stats">
      <span>⭐ 189</span>
      <span>🔀 45</span>
    </div>
    <div class="project-links">
      <a href="https://github.com/yourusername/project2" class="btn btn--small">Code</a>
      <a href="https://project2-demo.com" class="btn btn--small btn--primary">Live Demo</a>
    </div>
  </div>
</div>

<div class="project-card" data-category="development">
  <img src="/assets/images/project3-thumb.jpg" alt="DevOps Tool">
  <div class="project-overlay">
    <h3>CloudDeploy</h3>
    <p>Automated deployment tool for AWS & Docker</p>
    <div class="project-stats">
      <span>⭐ 312</span>
      <span>🔀 89</span>
    </div>
    <div class="project-links">
      <a href="https://github.com/yourusername/project3" class="btn btn--small">Code</a>
      <a href="https://project3-demo.com" class="btn btn--small btn--primary">Live Demo</a>
    </div>
  </div>
</div>

</div>
