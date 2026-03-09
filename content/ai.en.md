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
  display: flex;
  flex-direction: column;
  gap: 40px;
  margin: 0 auto 60px;
  max-width: 640px;
}

.ai-card {
  border: 1.5px solid currentColor;
  border-radius: 12px;
  padding: 32px 28px 28px;
  opacity: 0.88;
  transition: opacity 0.2s ease, transform 0.2s ease;
  position: relative;
}
.ai-card:hover {
  opacity: 1;
  transform: translateY(-3px);
}

.ai-card .card-header {
  display: flex;
  align-items: baseline;
  justify-content: space-between;
  flex-wrap: wrap;
  gap: 8px;
  margin-bottom: 14px;
}
.ai-card .card-header h3 {
  font-size: 1.5em;
  margin: 0;
  letter-spacing: 0.5px;
}
.ai-card .card-label {
  font-size: 0.68em;
  letter-spacing: 3px;
  text-transform: uppercase;
  opacity: 0.4;
  white-space: nowrap;
}

.ai-card .card-desc {
  opacity: 0.7;
  font-size: 0.95em;
  line-height: 1.55;
  margin: 0 0 18px;
}

.ai-card .card-features {
  list-style: none;
  padding: 0;
  margin: 0 0 20px;
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 6px 16px;
}
.ai-card .card-features li {
  font-size: 0.82em;
  opacity: 0.55;
  padding-left: 14px;
  position: relative;
}
.ai-card .card-features li::before {
  content: "—";
  position: absolute;
  left: 0;
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

@media (max-width: 480px) {
  .ai-card .card-features {
    grid-template-columns: 1fr;
  }
  .ai-card .card-header {
    flex-direction: column;
    gap: 4px;
  }
}
</style>

<div class="ai-hero">
  <h2>Building with AI</h2>
  <p>Open source projects pushing the boundaries of what's possible.</p>
</div>

<div class="ai-projects">

  <div class="ai-card">
    <div class="card-header">
      <h3>Claudius <span style="font-size:0.5em; opacity:0.5;">the Magnificent</span></h3>
      <span class="card-label">Dev Companion</span>
    </div>
    <p class="card-desc">A magnificently arrogant Claude Code plugin that manages your development workflow. Drives implementation, spawns specialist agents for grumpy code reviews, and lets you triage the findings like a civilized human.</p>
    <ul class="card-features">
      <li>Multi-agent code review</li>
      <li>Automated triage workflow</li>
      <li>Session hooks integration</li>
      <li>Opinionated best practices</li>
    </ul>
    <div class="card-tags">
      <span class="card-tag">Claude Code</span>
      <span class="card-tag">Multi-Agent</span>
      <span class="card-tag">Code Review</span>
    </div>
    <a href="https://github.com/lklimek/claudius" class="card-link" target="_blank">
      <svg viewBox="0 0 24 24"><path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"></path></svg>
      GitHub
    </a>
  </div>

  <div class="ai-card">
    <div class="card-header">
      <h3>MemCan</h3>
      <span class="card-label">Persistent Memory</span>
    </div>
    <p class="card-desc">A Rust MCP server that gives Claude Code a long-term memory. Stores learnings, decisions, and preferences in an embedded LanceDB vector database with Ollama-powered semantic search — no external infrastructure required.</p>
    <ul class="card-features">
      <li>Embedded vector DB (LanceDB)</li>
      <li>Semantic search via Ollama</li>
      <li>Project-scoped memories</li>
      <li>LLM-distilled fact extraction</li>
      <li>Code &amp; standards indexing</li>
      <li>Zero-config plugin install</li>
    </ul>
    <div class="card-tags">
      <span class="card-tag">Rust</span>
      <span class="card-tag">MCP</span>
      <span class="card-tag">LanceDB</span>
      <span class="card-tag">Ollama</span>
    </div>
    <a href="https://github.com/lklimek/memcan" class="card-link" target="_blank">
      <svg viewBox="0 0 24 24"><path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"></path></svg>
      GitHub
    </a>
  </div>

</div>
