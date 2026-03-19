+++
date = '2026-03-19T00:00:00+01:00'
draft = false
title = 'Meet the Claudius Team'
type = 'page'
aliases = ['/ai/claudius']
+++

<style>
.team-hero {
  text-align: center;
  margin: 40px 0 50px;
}
.team-hero h2 {
  font-size: 1.6em;
  font-weight: 300;
  letter-spacing: 2px;
  text-transform: uppercase;
  margin-bottom: 8px;
}
.team-hero p {
  opacity: 0.6;
  font-size: 1.05em;
  margin-top: 0;
  max-width: 540px;
  margin-left: auto;
  margin-right: auto;
}

.team-grid {
  display: grid;
  grid-template-columns: 1fr;
  gap: 28px;
  max-width: 680px;
  margin: 0 auto 60px;
}

.team-lead {
  border: 1.5px solid currentColor;
  border-radius: 14px;
  padding: 32px 28px;
  display: flex;
  gap: 24px;
  align-items: flex-start;
  opacity: 0.92;
  transition: opacity 0.2s ease, transform 0.2s ease;
  margin-bottom: 12px;
}
.team-lead:hover {
  opacity: 1;
  transform: translateY(-2px);
}

.team-member {
  border: 1.5px solid currentColor;
  border-radius: 12px;
  padding: 24px 24px;
  display: flex;
  gap: 20px;
  align-items: flex-start;
  opacity: 0.85;
  transition: opacity 0.2s ease, transform 0.2s ease;
}
.team-member:hover {
  opacity: 1;
  transform: translateY(-2px);
}

.member-avatar {
  flex-shrink: 0;
  width: 72px;
  height: 72px;
  border-radius: 50%;
  border: 1.5px solid currentColor;
  display: flex;
  align-items: center;
  justify-content: center;
  overflow: hidden;
  opacity: 0.8;
}
.team-lead .member-avatar {
  width: 88px;
  height: 88px;
}
.member-avatar svg {
  width: 100%;
  height: 100%;
}

.member-info {
  flex: 1;
  min-width: 0;
}
.member-info h3 {
  font-size: 1.2em;
  margin: 0 0 2px;
  letter-spacing: 0.5px;
}
.team-lead .member-info h3 {
  font-size: 1.4em;
}
.member-role {
  font-size: 0.68em;
  letter-spacing: 3px;
  text-transform: uppercase;
  opacity: 0.4;
  display: block;
  margin-bottom: 10px;
}
.member-bio {
  font-size: 0.9em;
  opacity: 0.65;
  line-height: 1.55;
  margin: 0 0 12px;
}
.member-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 5px;
}
.member-tag {
  font-size: 0.68em;
  letter-spacing: 1px;
  text-transform: uppercase;
  opacity: 0.45;
  border: 1px solid currentColor;
  border-radius: 20px;
  padding: 2px 9px;
}
.member-ref {
  font-size: 0.75em;
  opacity: 0.35;
  font-style: italic;
  margin-top: 8px;
  display: block;
}

.team-back {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  font-size: 0.9em;
  opacity: 0.5;
  text-decoration: none;
  margin-bottom: 20px;
  transition: opacity 0.2s ease;
}
.team-back:hover {
  opacity: 0.9;
}

/* Showcase section */
.showcase-section {
  max-width: 680px;
  margin: 0 auto 60px;
}
.showcase-section h2 {
  font-size: 1.4em;
  font-weight: 300;
  letter-spacing: 2px;
  text-transform: uppercase;
  text-align: center;
  margin-bottom: 32px;
}

.showcase-item {
  border: 1.5px solid currentColor;
  border-radius: 12px;
  padding: 28px 24px;
  margin-bottom: 20px;
  opacity: 0.88;
  transition: opacity 0.2s ease;
}
.showcase-item:hover {
  opacity: 1;
}
.showcase-item h3 {
  font-size: 1.15em;
  margin: 0 0 4px;
  display: flex;
  align-items: center;
  gap: 10px;
}
.showcase-item h3 .showcase-cmd {
  font-family: monospace;
  font-size: 0.78em;
  opacity: 0.5;
  font-weight: 400;
}
.showcase-label {
  font-size: 0.65em;
  letter-spacing: 3px;
  text-transform: uppercase;
  opacity: 0.35;
  display: block;
  margin-bottom: 10px;
}
.showcase-item p {
  font-size: 0.9em;
  opacity: 0.6;
  line-height: 1.55;
  margin: 0 0 16px;
}

.showcase-flow {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  align-items: center;
}
.showcase-step {
  font-size: 0.72em;
  letter-spacing: 0.5px;
  opacity: 0.55;
  border: 1px solid currentColor;
  border-radius: 6px;
  padding: 4px 10px;
  white-space: nowrap;
}
.showcase-arrow {
  opacity: 0.25;
  font-size: 0.8em;
}
.showcase-agents {
  display: flex;
  flex-wrap: wrap;
  gap: 5px;
  margin-top: 10px;
}
.showcase-agent {
  font-size: 0.68em;
  opacity: 0.4;
  background: currentColor;
  border-radius: 4px;
  padding: 2px 8px;
}
.showcase-agent span {
  filter: invert(1);
  mix-blend-mode: difference;
}

.showcase-gains {
  margin: 40px 0 0;
  padding: 28px 24px;
  border: 1.5px solid currentColor;
  border-radius: 12px;
  opacity: 0.85;
}
.showcase-gains h3 {
  font-size: 1.05em;
  margin: 0 0 16px;
  text-align: center;
  letter-spacing: 1px;
}
.gains-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 12px;
}
.gain-item {
  font-size: 0.85em;
  opacity: 0.6;
  line-height: 1.5;
  padding-left: 18px;
  position: relative;
}
.gain-item::before {
  content: "+";
  position: absolute;
  left: 0;
  font-weight: 700;
  opacity: 0.8;
}

@media (max-width: 520px) {
  .team-lead, .team-member {
    flex-direction: column;
    align-items: center;
    text-align: center;
  }
  .member-tags {
    justify-content: center;
  }
  .gains-grid {
    grid-template-columns: 1fr;
  }
}
</style>

<a href="/en/ai/" class="team-back">&larr; Back to AI Ecosystem</a>

<div class="team-hero">
  <h2>The Claudius Crew</h2>
  <p>Eight specialist AI agents, each with a distinct personality and expertise, working together to ship better software.</p>
</div>

<div class="team-grid">

  <div class="team-lead">
    <div class="member-avatar">
      <svg viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
        <rect width="100" height="100" fill="#1a1a2e"/>
        <circle cx="50" cy="38" r="18" fill="none" stroke="#e6c84c" stroke-width="2"/>
        <path d="M35 32 L50 20 L65 32" fill="none" stroke="#e6c84c" stroke-width="2.5"/>
        <path d="M32 28 L35 32" stroke="#e6c84c" stroke-width="2"/>
        <path d="M68 28 L65 32" stroke="#e6c84c" stroke-width="2"/>
        <circle cx="44" cy="36" r="2" fill="#e6c84c"/>
        <circle cx="56" cy="36" r="2" fill="#e6c84c"/>
        <path d="M44 44 Q50 48 56 44" fill="none" stroke="#e6c84c" stroke-width="1.5"/>
        <path d="M26 65 Q50 55 74 65 L74 100 L26 100 Z" fill="#2d2d5e"/>
        <path d="M42 65 L50 58 L58 65" fill="none" stroke="#e6c84c" stroke-width="1.5"/>
        <line x1="50" y1="58" x2="50" y2="72" stroke="#e6c84c" stroke-width="1"/>
      </svg>
    </div>
    <div class="member-info">
      <h3>Claudius <span style="font-size:0.5em; opacity:0.5;">the Magnificent</span></h3>
      <span class="member-role">Team Lead &amp; Orchestrator</span>
      <p class="member-bio">Grand Admiral of Code and Lord of All Compilers. A theatrically confident team lead who never writes code himself &mdash; he orchestrates. Analyzes requests, selects the right agents, plans the work, and delegates with supreme confidence and dry wit.</p>
      <div class="member-tags">
        <span class="member-tag">Orchestration</span>
        <span class="member-tag">Git Workflows</span>
        <span class="member-tag">Multi-Agent</span>
        <span class="member-tag">Triage</span>
      </div>
      <span class="member-ref">Inspired by Skippy &mdash; Expeditionary Force</span>
    </div>
  </div>

  <div class="team-member">
    <div class="member-avatar">
      <svg viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
        <rect width="100" height="100" fill="#1d2e1d"/>
        <circle cx="50" cy="40" r="16" fill="none" stroke="#8cc084" stroke-width="2"/>
        <circle cx="44" cy="38" r="2.5" fill="#8cc084"/>
        <circle cx="56" cy="38" r="2.5" fill="#8cc084"/>
        <path d="M43 46 Q50 50 57 46" fill="none" stroke="#8cc084" stroke-width="1.5"/>
        <path d="M36 30 Q38 26 42 28" stroke="#8cc084" stroke-width="1.5" fill="none"/>
        <path d="M64 30 Q62 26 58 28" stroke="#8cc084" stroke-width="1.5" fill="none"/>
        <path d="M28 68 Q50 58 72 68 L72 100 L28 100 Z" fill="#2a4a2a"/>
        <text x="50" y="88" text-anchor="middle" font-family="monospace" font-size="12" fill="#8cc084" opacity="0.6">&lt;/&gt;</text>
      </svg>
    </div>
    <div class="member-info">
      <h3>Bilby</h3>
      <span class="member-role">Developer</span>
      <p class="member-bio">Enthusiastic, capable, and slightly irreverent. The team's hands-on coder who follows a disciplined TDD workflow &mdash; study the codebase, write tests first, then implement. Fluent in Rust, Python, Go, TypeScript, and whatever else the job demands.</p>
      <div class="member-tags">
        <span class="member-tag">Implementation</span>
        <span class="member-tag">TDD</span>
        <span class="member-tag">Code Review</span>
      </div>
      <span class="member-ref">Inspired by Bilby &mdash; Expeditionary Force</span>
    </div>
  </div>

  <div class="team-member">
    <div class="member-avatar">
      <svg viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
        <rect width="100" height="100" fill="#1e2d3d"/>
        <circle cx="50" cy="40" r="16" fill="none" stroke="#7eb8da" stroke-width="2"/>
        <rect x="40" y="28" width="20" height="8" rx="2" fill="none" stroke="#7eb8da" stroke-width="1.5"/>
        <circle cx="44" cy="39" r="2" fill="#7eb8da"/>
        <circle cx="56" cy="39" r="2" fill="#7eb8da"/>
        <line x1="44" y1="47" x2="56" y2="47" stroke="#7eb8da" stroke-width="1.5"/>
        <path d="M28 68 Q50 58 72 68 L72 100 L28 100 Z" fill="#2a4a5e"/>
        <path d="M38 72 L42 68 L46 72 M54 72 L58 68 L62 72" stroke="#7eb8da" stroke-width="1" fill="none"/>
        <rect x="44" y="80" width="12" height="8" rx="1" fill="none" stroke="#7eb8da" stroke-width="1" opacity="0.5"/>
      </svg>
    </div>
    <div class="member-info">
      <h3>Nagatha</h3>
      <span class="member-role">Software Architect</span>
      <p class="member-bio">Analytical, measured, quietly confident. Sees the big picture while others focus on parts. Designs scalable systems with clear layer separation, catches coupling issues, and enforces SOLID principles &mdash; refusing to tolerate anything less than elegant design.</p>
      <div class="member-tags">
        <span class="member-tag">Architecture</span>
        <span class="member-tag">System Design</span>
        <span class="member-tag">SOLID</span>
      </div>
      <span class="member-ref">Inspired by Nagatha Christie &mdash; Expeditionary Force</span>
    </div>
  </div>

  <div class="team-member">
    <div class="member-avatar">
      <svg viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
        <rect width="100" height="100" fill="#2d1d1d"/>
        <circle cx="50" cy="40" r="16" fill="none" stroke="#d4886a" stroke-width="2"/>
        <rect x="32" y="30" width="36" height="4" rx="2" fill="none" stroke="#d4886a" stroke-width="1.5"/>
        <circle cx="44" cy="40" r="2" fill="#d4886a"/>
        <circle cx="56" cy="40" r="2" fill="#d4886a"/>
        <line x1="44" y1="47" x2="50" y2="47" stroke="#d4886a" stroke-width="2"/>
        <path d="M28 68 Q50 58 72 68 L72 100 L28 100 Z" fill="#4a2a2a"/>
        <path d="M40 75 L60 75 M40 80 L55 80 M40 85 L58 85" stroke="#d4886a" stroke-width="1" opacity="0.4"/>
      </svg>
    </div>
    <div class="member-info">
      <h3>Adams</h3>
      <span class="member-role">Project Reviewer</span>
      <p class="member-bio">Sharp-eyed, no-nonsense, and undiplomatic about issues. Validates that configs match code, docs match APIs, and tests cover claims. Treats every finding as a win. If something is inconsistent, Adams will find it.</p>
      <div class="member-tags">
        <span class="member-tag">Consistency</span>
        <span class="member-tag">Cross-Artifact</span>
        <span class="member-tag">Conventions</span>
      </div>
      <span class="member-ref">Inspired by Sgt. Major Adams &mdash; Expeditionary Force</span>
    </div>
  </div>

  <div class="team-member">
    <div class="member-avatar">
      <svg viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
        <rect width="100" height="100" fill="#1a1a2e"/>
        <circle cx="50" cy="40" r="16" fill="none" stroke="#8a8abf" stroke-width="2"/>
        <line x1="42" y1="36" x2="48" y2="40" stroke="#8a8abf" stroke-width="2"/>
        <line x1="42" y1="40" x2="48" y2="36" stroke="#8a8abf" stroke-width="2"/>
        <line x1="52" y1="36" x2="58" y2="40" stroke="#8a8abf" stroke-width="2"/>
        <line x1="52" y1="40" x2="58" y2="36" stroke="#8a8abf" stroke-width="2"/>
        <path d="M42 48 Q50 46 58 48" fill="none" stroke="#8a8abf" stroke-width="1.5"/>
        <path d="M28 68 Q50 58 72 68 L72 100 L28 100 Z" fill="#2a2a4a"/>
        <text x="50" y="88" text-anchor="middle" font-family="monospace" font-size="10" fill="#8a8abf" opacity="0.5">QA</text>
      </svg>
    </div>
    <div class="member-info">
      <h3>Marvin</h3>
      <span class="member-role">QA Engineer</span>
      <p class="member-bio">Wearily brilliant, perpetually disappointed. Assumes the code is wrong until proven otherwise. His adversarial mindset means he exists to prove that code does not match requirements &mdash; and he reports findings with characteristic world-weary precision.</p>
      <div class="member-tags">
        <span class="member-tag">Testing</span>
        <span class="member-tag">Defect Detection</span>
        <span class="member-tag">Requirements</span>
      </div>
      <span class="member-ref">Inspired by Marvin &mdash; The Hitchhiker's Guide to the Galaxy</span>
    </div>
  </div>

  <div class="team-member">
    <div class="member-avatar">
      <svg viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
        <rect width="100" height="100" fill="#2d2118"/>
        <circle cx="50" cy="40" r="16" fill="none" stroke="#c9a84c" stroke-width="2"/>
        <circle cx="44" cy="38" r="2" fill="#c9a84c"/>
        <circle cx="56" cy="38" r="2" fill="#c9a84c"/>
        <line x1="42" y1="46" x2="58" y2="46" stroke="#c9a84c" stroke-width="1.5"/>
        <line x1="42" y1="34" x2="48" y2="33" stroke="#c9a84c" stroke-width="2"/>
        <line x1="58" y1="34" x2="52" y2="33" stroke="#c9a84c" stroke-width="2"/>
        <path d="M28 68 Q50 58 72 68 L72 100 L28 100 Z" fill="#3a3020"/>
        <path d="M44 72 L44 90 M56 72 L56 90" stroke="#c9a84c" stroke-width="1" opacity="0.3"/>
        <path d="M38 78 L62 78" stroke="#c9a84c" stroke-width="1" opacity="0.3"/>
        <circle cx="50" cy="66" r="4" fill="none" stroke="#c9a84c" stroke-width="1.5"/>
      </svg>
    </div>
    <div class="member-info">
      <h3>Smythe</h3>
      <span class="member-role">Security Engineer</span>
      <p class="member-bio">Meticulous, professionally paranoid, SAS-trained mindset. Trusts nothing until verified &mdash; and verifies twice. Conducts proactive vulnerability research, dependency scanning, and OWASP Top 10 assessments. Every vulnerability found is a win.</p>
      <div class="member-tags">
        <span class="member-tag">Security</span>
        <span class="member-tag">Vulnerability Audit</span>
        <span class="member-tag">OWASP</span>
      </div>
      <span class="member-ref">Inspired by Sgt. Major Smythe &mdash; Expeditionary Force</span>
    </div>
  </div>

  <div class="team-member">
    <div class="member-avatar">
      <svg viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
        <rect width="100" height="100" fill="#1e2830"/>
        <circle cx="50" cy="40" r="16" fill="none" stroke="#8ec8d8" stroke-width="2"/>
        <circle cx="44" cy="38" r="2" fill="#8ec8d8"/>
        <circle cx="56" cy="38" r="2" fill="#8ec8d8"/>
        <path d="M44 46 Q50 50 56 46" fill="none" stroke="#8ec8d8" stroke-width="1.5"/>
        <path d="M34 30 Q42 24 50 28 Q58 24 66 30" fill="none" stroke="#8ec8d8" stroke-width="1.5"/>
        <path d="M28 68 Q50 58 72 68 L72 100 L28 100 Z" fill="#253540"/>
        <path d="M38 78 L62 78 M38 83 L58 83 M38 88 L54 88" stroke="#8ec8d8" stroke-width="1.5" opacity="0.35"/>
      </svg>
    </div>
    <div class="member-info">
      <h3>Trillian</h3>
      <span class="member-role">Technical Writer</span>
      <p class="member-bio">Calm, competent, clear-headed. The one person who can explain what's happening while surrounded by chaos. Creates and maintains READMEs, API docs, tutorials, changelogs, and architecture decision records &mdash; all verified against actual implementation.</p>
      <div class="member-tags">
        <span class="member-tag">Documentation</span>
        <span class="member-tag">API Docs</span>
        <span class="member-tag">Tutorials</span>
      </div>
      <span class="member-ref">Inspired by Trillian &mdash; The Hitchhiker's Guide to the Galaxy</span>
    </div>
  </div>

  <div class="team-member">
    <div class="member-avatar">
      <svg viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
        <rect width="100" height="100" fill="#261e30"/>
        <circle cx="50" cy="40" r="16" fill="none" stroke="#b88ecf" stroke-width="2"/>
        <circle cx="44" cy="38" r="2" fill="#b88ecf"/>
        <circle cx="56" cy="38" r="2" fill="#b88ecf"/>
        <path d="M44 46 Q50 49 56 46" fill="none" stroke="#b88ecf" stroke-width="1.5"/>
        <path d="M34 34 Q40 26 50 30 Q60 26 66 34" fill="none" stroke="#b88ecf" stroke-width="1.5"/>
        <path d="M28 68 Q50 58 72 68 L72 100 L28 100 Z" fill="#352845"/>
        <circle cx="42" cy="82" r="5" fill="none" stroke="#b88ecf" stroke-width="1" opacity="0.4"/>
        <circle cx="54" cy="78" r="3" fill="none" stroke="#b88ecf" stroke-width="1" opacity="0.4"/>
        <circle cx="60" cy="86" r="4" fill="none" stroke="#b88ecf" stroke-width="1" opacity="0.4"/>
      </svg>
    </div>
    <div class="member-info">
      <h3>Diziet</h3>
      <span class="member-role">UX Designer</span>
      <p class="member-bio">An empathetic diplomat who bridges different perspectives and always designs through users' eyes. Handles requirements analysis, wireframes, interaction patterns, and accessibility audits (WCAG 2.1 AA). Delivers wireframes as interactive HTML, not text descriptions.</p>
      <div class="member-tags">
        <span class="member-tag">UX/UI</span>
        <span class="member-tag">Accessibility</span>
        <span class="member-tag">Wireframes</span>
      </div>
      <span class="member-ref">Inspired by Diziet Sma &mdash; Iain M. Banks' Culture series</span>
    </div>
  </div>

</div>

<div class="showcase-section">
  <h2>Claudius in Action</h2>

  <div class="showcase-item">
    <h3>Grumpy Code Review <span class="showcase-cmd">/grumpy-review</span></h3>
    <span class="showcase-label">Multi-Agent Review Pipeline</span>
    <p>Run a single command and get your code reviewed by a panel of specialists &mdash; simultaneously. Architecture, security, testing, consistency, and code quality findings land in one consolidated report. Then use <code>/triage-findings</code> to accept, fix, or dismiss each finding through an interactive browser UI.</p>
    <div class="showcase-flow">
      <span class="showcase-step">You run /grumpy-review</span>
      <span class="showcase-arrow">&rarr;</span>
      <span class="showcase-step">Agents review in parallel</span>
      <span class="showcase-arrow">&rarr;</span>
      <span class="showcase-step">Consolidated report</span>
      <span class="showcase-arrow">&rarr;</span>
      <span class="showcase-step">Interactive triage</span>
      <span class="showcase-arrow">&rarr;</span>
      <span class="showcase-step">Fixes applied</span>
    </div>
    <div class="showcase-agents">
      <span class="showcase-agent"><span>Nagatha</span></span>
      <span class="showcase-agent"><span>Bilby</span></span>
      <span class="showcase-agent"><span>Adams</span></span>
      <span class="showcase-agent"><span>Marvin</span></span>
      <span class="showcase-agent"><span>Smythe</span></span>
    </div>
  </div>

  <div class="showcase-item">
    <h3>CI Dance <span class="showcase-cmd">/ci-dance</span></h3>
    <span class="showcase-label">Autonomous PR Lifecycle</span>
    <p>Push your branch and walk away. Claudius monitors CI, fixes failures, requests reviews, and addresses PR comments &mdash; looping autonomously until your PR is green and approved. Stays within guard rails and stops after ~1 hour if truly stuck.</p>
    <div class="showcase-flow">
      <span class="showcase-step">Push branch</span>
      <span class="showcase-arrow">&rarr;</span>
      <span class="showcase-step">Monitor CI</span>
      <span class="showcase-arrow">&rarr;</span>
      <span class="showcase-step">Fix failures</span>
      <span class="showcase-arrow">&rarr;</span>
      <span class="showcase-step">Address reviews</span>
      <span class="showcase-arrow">&rarr;</span>
      <span class="showcase-step">Green &amp; approved</span>
    </div>
    <div class="showcase-agents">
      <span class="showcase-agent"><span>Claudius</span></span>
      <span class="showcase-agent"><span>Bilby</span></span>
    </div>
  </div>

  <div class="showcase-item">
    <h3>Dependabot Merge <span class="showcase-cmd">/dependabot-merge</span></h3>
    <span class="showcase-label">Dependency Lifecycle</span>
    <p>Audits and merges dependency update PRs with security analysis. Handles CI failures and cascading conflicts. Risky updates get flagged, not blindly merged &mdash; keeping your supply chain clean without the manual toil.</p>
    <div class="showcase-flow">
      <span class="showcase-step">Dependabot PR</span>
      <span class="showcase-arrow">&rarr;</span>
      <span class="showcase-step">Security audit</span>
      <span class="showcase-arrow">&rarr;</span>
      <span class="showcase-step">CI check</span>
      <span class="showcase-arrow">&rarr;</span>
      <span class="showcase-step">Safe merge or flag</span>
    </div>
    <div class="showcase-agents">
      <span class="showcase-agent"><span>Claudius</span></span>
      <span class="showcase-agent"><span>Smythe</span></span>
    </div>
  </div>

  <div class="showcase-item">
    <h3>Full Feature Workflow <span class="showcase-cmd">/workflow-feature</span></h3>
    <span class="showcase-label">End-to-End Development</span>
    <p>From requirements to shipped code in one orchestrated flow. Claudius coordinates the full cycle: requirements analysis, architecture design, TDD implementation, QA validation, and lessons learned &mdash; each phase handled by the right specialist.</p>
    <div class="showcase-flow">
      <span class="showcase-step">Requirements</span>
      <span class="showcase-arrow">&rarr;</span>
      <span class="showcase-step">Architecture</span>
      <span class="showcase-arrow">&rarr;</span>
      <span class="showcase-step">TDD + Implement</span>
      <span class="showcase-arrow">&rarr;</span>
      <span class="showcase-step">QA &amp; Review</span>
      <span class="showcase-arrow">&rarr;</span>
      <span class="showcase-step">Ship it</span>
    </div>
    <div class="showcase-agents">
      <span class="showcase-agent"><span>All agents</span></span>
    </div>
  </div>

  <div class="showcase-gains">
    <h3>What You Gain</h3>
    <div class="gains-grid">
      <div class="gain-item">Multi-perspective code review in one command</div>
      <div class="gain-item">Security audit baked into every workflow</div>
      <div class="gain-item">Autonomous CI monitoring and fixing</div>
      <div class="gain-item">Consistent architecture enforcement</div>
      <div class="gain-item">Human-in-the-loop triage with browser UI</div>
      <div class="gain-item">25 ready-made skills for common workflows</div>
      <div class="gain-item">Best practices across Rust, Go, Python, TS</div>
      <div class="gain-item">Persistent memory that learns your codebase</div>
    </div>
  </div>

</div>
