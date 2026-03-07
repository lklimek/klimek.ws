+++
date = '2026-03-07T00:00:00+01:00'
draft = false
title = 'AI Ecosystem'
type = 'page'
aliases = ['/ai']
+++

<style>
.ai-hero {
  text-align: center;
  margin: 40px 0 60px;
}
.ai-hero h2 {
  font-size: 1.6em;
  font-weight: 300;
  letter-spacing: 2px;
  text-transform: uppercase;
  margin-bottom: 8px;
}
.ai-hero p {
  opacity: 0.6;
  font-size: 1.05em;
  margin-top: 0;
}

.ai-projects {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 30px;
  margin: 0 auto 60px;
  max-width: 700px;
}

.ai-card {
  border: 1.5px solid currentColor;
  border-radius: 12px;
  padding: 32px 28px 28px;
  opacity: 0.9;
  transition: opacity 0.2s ease, transform 0.2s ease;
  position: relative;
}
.ai-card:hover {
  opacity: 1;
  transform: translateY(-3px);
}

.ai-card .card-label {
  font-size: 0.7em;
  letter-spacing: 3px;
  text-transform: uppercase;
  opacity: 0.45;
  margin: 0 0 12px;
}

.ai-card h3 {
  font-size: 1.5em;
  margin: 0 0 10px;
  letter-spacing: 0.5px;
}

.ai-card .card-desc {
  opacity: 0.7;
  font-size: 0.95em;
  line-height: 1.5;
  margin: 0 0 20px;
}

.ai-card .card-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 6px;
  margin-bottom: 20px;
}
.ai-card .card-tag {
  font-size: 0.72em;
  letter-spacing: 1px;
  text-transform: uppercase;
  opacity: 0.5;
  border: 1px solid currentColor;
  border-radius: 20px;
  padding: 3px 10px;
}

.ai-card .card-link {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  font-size: 0.9em;
  text-decoration: none;
  opacity: 0.7;
  transition: opacity 0.2s ease;
}
.ai-card .card-link:hover {
  opacity: 1;
}
.ai-card .card-link svg {
  width: 16px;
  height: 16px;
  stroke: currentColor;
  stroke-width: 2;
  fill: none;
  stroke-linecap: round;
  stroke-linejoin: round;
}
</style>

<div class="ai-hero">
  <h2>Building with AI</h2>
  <p>Open source projects pushing the boundaries of what's possible.</p>
</div>

<div class="ai-projects">

  <div class="ai-card">
    <div class="card-label">Tooling</div>
    <h3>Claudius</h3>
    <p class="card-desc">AI assistant framework. Streamlined tooling for building with LLMs.</p>
    <div class="card-tags">
      <span class="card-tag">LLM</span>
      <span class="card-tag">CLI</span>
      <span class="card-tag">Agents</span>
    </div>
    <a href="https://github.com/lklimek/claudius" class="card-link" target="_blank">
      <svg viewBox="0 0 24 24"><path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"></path></svg>
      GitHub
    </a>
  </div>

  <div class="ai-card">
    <div class="card-label">Platform</div>
    <h3>Mindojo</h3>
    <p class="card-desc">AI-powered adaptive learning platform. Personalized education at scale.</p>
    <div class="card-tags">
      <span class="card-tag">EdTech</span>
      <span class="card-tag">AI</span>
      <span class="card-tag">Learning</span>
    </div>
    <a href="https://github.com/mindojo" class="card-link" target="_blank">
      <svg viewBox="0 0 24 24"><path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"></path></svg>
      GitHub
    </a>
  </div>

</div>
