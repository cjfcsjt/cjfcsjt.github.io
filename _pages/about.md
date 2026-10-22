---
layout: about
title: about
permalink: /
subtitle: Ph.D. Student @ <a href="https://www.polyu.edu.hk/">The Hong Kong Polytechnic University</a>

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <div class="contact-icons jc-profile-icons">
      <a href="mailto:jingfan.chen@connect.polyu.hk" title="email"><i class="fa-solid fa-envelope"></i></a>
      <a href="https://scholar.google.com/citations?user=KSafcUUAAAAJ" title="Google Scholar" target="_blank" rel="noopener"><i class="ai ai-google-scholar"></i></a>
      <a href="https://github.com/cjfcsjt" title="GitHub" target="_blank" rel="noopener"><i class="fa-brands fa-github"></i></a>
    </div>
    <p class="jc-profile-note">jingfan.chen [at] connect.polyu.hk</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: false # contact icons are shown under the profile photo instead

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 6 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
---

<style>
  .jc-profile-icons{font-size:1.6rem;text-align:center;margin-top:.4rem}
  .jc-profile-icons a{margin:0 .35rem}
  .jc-profile-note{text-align:center;font-size:.85rem;opacity:.75;margin:.2rem 0 0}
  html[data-theme="dark"] .jc-exp img{background:#fff;border-radius:6px;padding:3px}

  .jc-flow{clear:both;display:flex;align-items:stretch;gap:.5rem;margin:1.4rem 0 .4rem}
  .jc-step{flex:1;min-width:0;display:flex;flex-direction:column;gap:.15rem;border:1.5px solid var(--global-divider-color);border-radius:10px;background:var(--global-card-bg-color);padding:.6rem .8rem;color:var(--global-text-color)!important;text-decoration:none!important;transition:border-color .15s,transform .15s,box-shadow .15s}
  .jc-step:hover{border-color:var(--global-theme-color);transform:translateY(-2px);box-shadow:0 4px 12px rgba(0,0,0,.08)}
  .jc-step .jc-num{font-size:.72rem;font-weight:700;letter-spacing:.08em;color:var(--global-theme-color)}
  .jc-step strong{font-size:.98rem;font-weight:600;line-height:1.2}
  .jc-step small{font-size:.78rem;opacity:.75;line-height:1.25}
  .jc-flow-arrow{align-self:center;font-size:1.3rem;color:var(--global-theme-color)}
  @media (max-width:640px){.jc-flow{flex-direction:column}.jc-flow-arrow{transform:rotate(90deg);margin:-.2rem 0}}

  .jc-wrap{display:grid;grid-template-columns:minmax(0,1.1fr) minmax(0,1fr);gap:1.4rem;align-items:start;margin:.6rem 0 1.8rem;font-size:.95rem}
  .jc-left{min-width:0}
  .jc-right{position:sticky;top:80px;min-width:0}
  @media (max-width:820px){.jc-wrap{grid-template-columns:1fr}.jc-right{position:static}}

  details.jc-card{border:1px solid var(--global-divider-color);border-radius:10px;background:var(--global-card-bg-color);margin:.6rem 0;padding:0 1rem;transition:border-color .15s}
  details.jc-card[open]{border-color:var(--global-theme-color)}
  .jc-card>summary{list-style:none;cursor:pointer;padding:.72rem 0;font-weight:600;font-size:1rem;display:flex;justify-content:space-between;align-items:center;gap:.6rem}
  .jc-card>summary::-webkit-details-marker{display:none}
  .jc-card>summary::after{content:'+';font-size:1.3rem;color:var(--global-theme-color)}
  .jc-card[open]>summary::after{content:'–'}
  .jc-card summary small{font-weight:400;opacity:.7}
  .jc-body{padding:.75rem 0 .95rem;border-top:1px solid var(--global-divider-color)}
  .jc-body h4{font-size:.8rem;text-transform:uppercase;letter-spacing:.05em;color:var(--global-theme-color);margin:.55rem 0 .4rem}
  .jc-body ul{margin:0 0 .6rem 1.1rem;padding:0}
  .jc-body li{margin-bottom:.3rem}
  .jc-body a{color:inherit;text-decoration:underline;text-decoration-thickness:1px;text-underline-offset:2px}
  .jc-body a:hover{color:var(--global-theme-color)}
  .jc-venue{font-size:.8rem;opacity:.75;white-space:nowrap}
  .jc-domain{font-size:.75rem;font-weight:600;text-transform:uppercase;letter-spacing:.04em;opacity:.7;margin:.45rem 0 .2rem}
  .jc-ongoing{opacity:.75;font-style:italic}
  .jc-why{display:block;font-size:.85rem;line-height:1.45;opacity:.78;margin-top:.1rem}
  .jc-tags{display:flex;flex-wrap:wrap;gap:.35rem;margin:.1rem 0 .5rem}
  .jc-tags span{font-size:.78rem;padding:.12rem .6rem;border:1px solid var(--global-divider-color);border-radius:999px;color:var(--global-theme-color)}

  .jc-figure{margin:0}
  .jc-figure svg{display:block;width:100%;height:auto;max-width:520px;margin:0 auto}
  .jc-figure .cf-row{fill:var(--global-text-color);fill-opacity:.05}
  .jc-figure .cf-mid{fill:var(--global-card-bg-color);stroke:var(--global-divider-color);stroke-width:.5}
  .jc-figure .cf-t{fill:var(--global-text-color)}
  .jc-figure .cf-muted{fill:var(--global-text-color);fill-opacity:.7}
  .jc-figure figcaption{font-size:.82rem;line-height:1.45;opacity:.85;margin-top:.5rem}
  .jc-figure figcaption .c-int{color:#1F5F8B;font-weight:600}
  .jc-figure figcaption .c-comp{color:#B45309;font-weight:600}
  .jc-figure .cf-int{fill:#1F5F8B}.jc-figure .cf-comp{fill:#B45309}.jc-figure .cf-upd{fill:#7A3A05}
  .jc-figure .cf-int-s{stroke:#1F5F8B}.jc-figure .cf-upd-s{stroke:#7A3A05}
  html[data-theme="dark"] .jc-figure .cf-int{fill:#7DB3DD}html[data-theme="dark"] .jc-figure .cf-comp,html[data-theme="dark"] .jc-figure .cf-upd{fill:#EDA463}
  html[data-theme="dark"] .jc-figure .cf-int-s{stroke:#7DB3DD}html[data-theme="dark"] .jc-figure .cf-upd-s{stroke:#EDA463}
  html[data-theme="dark"] .jc-figure figcaption .c-int{color:#7DB3DD}html[data-theme="dark"] .jc-figure figcaption .c-comp{color:#EDA463}
  .jc-exp{display:grid;grid-template-columns:72px minmax(0,1fr);gap:1rem 1.1rem;align-items:start;margin:.6rem 0 1.6rem}
  .jc-exp img{width:72px;max-height:44px;object-fit:contain;margin-top:.15rem}
  .jc-exp .jc-when{float:right;font-size:.85rem;opacity:.7;margin-left:.6rem}
  .jc-exp p{margin:.15rem 0 0;font-size:.92rem}
</style>

I am a Ph.D. student at [The Hong Kong Polytechnic University](https://www.polyu.edu.hk/) (PolyU), advised by [Prof. Qing Li](https://www4.comp.polyu.edu.hk/~csqli/) (IEEE Fellow), [Prof. Zhen Lei](http://www.cbsr.ia.ac.cn/users/zlei/) (IEEE Fellow) and [Prof. Zhaoxiang Zhang](https://zhaoxiangzhang.net/) (Changjiang Scholar). Before that, I received my M.S. in Computer Science from Nanjing University and my B.S. in Software Engineering from Shandong University. I have also been a research intern on the post-training team at [Shanghai AI Laboratory](https://www.shlab.org.cn/) and at Tencent Game AI Lab.

My research focuses on **Efficient LLM Agents**, **Agentic Computer Use** and **Recursive Self-Improvement (RSI)**. My earlier work focused on **information retrieval**.

<div class="jc-flow">
  <a class="jc-step" data-target="rf-eff" href="#rf-eff"><span class="jc-num">01</span><strong>Efficient LLM Agents</strong><small>from SI to RSI</small></a>
  <span class="jc-flow-arrow" aria-hidden="true">→</span>
  <a class="jc-step" data-target="rf-cu" href="#rf-cu"><span class="jc-num">02</span><strong>Computer Use</strong><small>GUI · CLI · coding agents</small></a>
  <span class="jc-flow-arrow" aria-hidden="true">→</span>
  <a class="jc-step" data-target="rf-app" href="#rf-app"><span class="jc-num">03</span><strong>Applications</strong><small>coding · office · visual creation · embodied AI</small></a>
</div>

<div class="jc-wrap">
  <div class="jc-left">
    <details class="jc-card" id="rf-eff" open>
      <summary><span>Efficient LLM Agents <small>— from SI to RSI</small></span></summary>
      <div class="jc-body">
        <h4>Research Questions</h4>
        <ul>
          <li><strong>How</strong> can an agent improve from its own experience while spending compute, observations and supervision only where they matter?</li>
          <li><strong>How</strong> do we go from self-improvement (SI), where a fixed improver updates the agent, to recursive self-improvement (RSI), where the improver itself gets better, and show the gain at the same budget?</li>
        </ul>
        <h4>Representative Works</h4>
        <ul>
          <li><a href="/publications/#chen2026warmup">Warm Up with a Rubric, Then Merge: Decoupling Grounding Gains from Reasoning Costs in Vision-Language Models</a> <span class="jc-venue">(EMNLP 2026)</span><span class="jc-why">Spends supervision where it pays off: a short rubric warm-up captures the grounding gain, then outcome-only RL continues at a fraction of the verifier cost.</span></li>
          <li><a href="/publications/#chen2026foveaui">FoveaUI: Foveated On-demand Visual Evidence Acquisition for GUI Grounding</a> <span class="jc-venue">(ACM MM 2026)</span><span class="jc-why">Spends observation compute where it pays off: the agent requests high-resolution crops only when fine detail is needed, cutting visual tokens while keeping grounding strong.</span></li>
          <li><a href="https://x.com/XGEN_labs/article/2103137462008844442" target="_blank" rel="noopener">Dual Exam: Controlled Evaluation of Multimodal Agents and World Models</a> <span class="jc-venue">(XGEN Labs Tech Report 2026, as core contributor)</span><span class="jc-why">Its world-model track checks whether generated worlds faithfully realize action effects, a precondition for trading costly real interaction for cheaper simulated experience.</span></li>
          <li class="jc-ongoing">Ongoing work on recursive self-improvement for agents.</li>
        </ul>
      </div>
    </details>
    <details class="jc-card" id="rf-cu">
      <summary><span>Computer Use <small>— GUI · CLI · Coding Agents</small></span></summary>
      <div class="jc-body">
        <h4>Research Questions</h4>
        <ul>
          <li><strong>How</strong> can agents ground instructions and act reliably on real software, through graphical interfaces and the command line?</li>
          <li><strong>How</strong> can GUI data and action spaces scale across platforms without human labels?</li>
          <li><strong>How</strong> can coding agents act through code, writing, running and debugging programs in the terminal, so that a long chain of GUI clicks becomes a few verifiable steps?</li>
        </ul>
        <h4>Representative Works</h4>
        <ul>
          <li><a href="https://arxiv.org/abs/2509.17328" target="_blank" rel="noopener">UIPro: Unleashing Superior Interaction Capability For GUI Agents</a> <span class="jc-venue">(ICCV 2025)</span><span class="jc-why">A generalist GUI agent that acts across platforms by mapping heterogeneous action formats into one shared action space.</span></li>
          <li><a href="https://aclanthology.org/2025.acl-long.510" target="_blank" rel="noopener">AutoGUI: Scaling GUI Grounding with Automatic Functionality Annotations from LLMs</a> <span class="jc-venue">(ACL 2025)</span><span class="jc-why">Scales GUI grounding data without human labels: LLMs infer what each element does from how the interface changes when it is used.</span></li>
          <li><a href="/publications/#chen2026foveaui">FoveaUI: Foveated On-demand Visual Evidence Acquisition for GUI Grounding</a> <span class="jc-venue">(ACM MM 2026)</span><span class="jc-why">Grounds instructions precisely on dense, high-resolution screens by looking closely only at the regions that matter.</span></li>
          <li><a href="https://x.com/XGEN_labs/article/2103137462008844442" target="_blank" rel="noopener">Dual Exam: Controlled Evaluation of Multimodal Agents and World Models</a> <span class="jc-venue">(XGEN Labs Tech Report 2026, as core contributor)</span><span class="jc-why">Covers digital-world agentic tasks and judges success from execution evidence rather than the agent's own claim of completion.</span></li>
        </ul>
      </div>
    </details>
    <details class="jc-card" id="rf-app">
      <summary><span>Applications <small>— where agents do real work</small></span></summary>
      <div class="jc-body">
        <div class="jc-tags"><span>Coding</span><span>Office</span><span>Visual Creation</span><span>World Models for Embodied AI</span></div>
        <h4>Research Questions</h4>
        <ul>
          <li><strong>What</strong> does it cost an agent to finish real work in coding, office and visual-creation software, and how can it reach the same success with fewer interactions, tokens and verifier calls?</li>
          <li><strong>Can</strong> world models let embodied agents imagine before they act, turning costly real-world interaction into cheaper computation without losing reliability?</li>
        </ul>
        <h4>Representative Works</h4>
        <ul>
          <li><a href="https://x.com/XGEN_labs/article/2103137462008844442" target="_blank" rel="noopener">Dual Exam: Controlled Evaluation of Multimodal Agents and World Models</a> <span class="jc-venue">(XGEN Labs Tech Report 2026, as core contributor)</span><span class="jc-why">Spans physical, digital, social and scientific tasks, and evaluates world models on their own, the component embodied agents would rely on to imagine before they act.</span></li>
        </ul>
      </div>
    </details>
  </div>

  <div class="jc-right">
    <figure class="jc-figure">
      <svg viewBox="0 0 150 98" role="img" aria-label="Where an agent's cost comes from while it learns. Interaction cost, charged by the environment: rollout steps, rewards, verifier queries. Computation cost, charged by the infrastructure: rollout inference generating trajectories, experience stored as trajectories and rewards, and internalizing it through weight updates or rewriting code and prompts, which updates the agent system (harness plus model).">
        <defs>
          <marker id="cf-h1" viewBox="0 0 10 10" refX="8" refY="5" markerWidth="4" markerHeight="4" orient="auto-start-reverse"><path d="M0 0L10 5L0 10z" fill="#B45309"></path></marker>
          <marker id="cf-h2" viewBox="0 0 10 10" refX="8" refY="5" markerWidth="4" markerHeight="4" orient="auto-start-reverse"><path d="M0 0L10 5L0 10z" class="cf-upd"></path></marker>
        </defs>
        <text x="22" y="9" text-anchor="middle" font-size="6" font-weight="600" class="cf-int">Interaction</text>
        <text x="22" y="14" text-anchor="middle" font-size="2.9" class="cf-t">charged by the environment</text>
        <text x="75" y="8" text-anchor="middle" font-size="4.2" class="cf-muted">Agent system</text>
        <text x="75" y="12.6" text-anchor="middle" font-size="2.9" class="cf-t">decides what to request</text>
        <text x="75" y="16.2" text-anchor="middle" font-size="2.9" class="cf-t">and what to compute</text>
        <text x="128" y="9" text-anchor="middle" font-size="6" font-weight="600" class="cf-comp">Computation</text>
        <text x="128" y="14" text-anchor="middle" font-size="2.8" class="cf-t">charged by the infrastructure</text>
        <rect x="0" y="19" width="150" height="79" rx="4" class="cf-row"></rect>
        <rect x="3" y="23" width="38" height="71" rx="3" fill="#DCEAF4" stroke="#1F5F8B" stroke-width=".7"></rect>
        <g fill="none" stroke="#1F5F8B" stroke-width=".45"><circle cx="22" cy="47" r="3"></circle><path d="M19 47h6M22 44c1.4 1.6 1.4 4.4 0 6c-1.4-1.6-1.4-4.4 0-6z"></path></g>
        <text x="22" y="57" text-anchor="middle" font-size="4.3" font-weight="600" fill="#164A6E">Interaction cost</text>
        <text x="22" y="62.5" text-anchor="middle" font-size="3.2" fill="#1F4E70">rollout steps,</text>
        <text x="22" y="66.6" text-anchor="middle" font-size="3.2" fill="#1F4E70">rewards, verifier</text>
        <text x="22" y="70.7" text-anchor="middle" font-size="3.2" fill="#1F4E70">queries</text>
        <circle cx="36.5" cy="27.5" r="2.6" fill="#1F5F8B"></circle><text x="36.5" y="28.7" text-anchor="middle" font-size="3.2" font-weight="600" fill="#fff">$</text>
        <rect x="55" y="23" width="40" height="71" rx="3" class="cf-mid"></rect>
        <text x="75" y="55" text-anchor="middle" font-size="4.2" class="cf-muted">Agent system,</text>
        <text x="75" y="60" text-anchor="middle" font-size="4.2" class="cf-muted">learning</text>
        <text x="75" y="66" text-anchor="middle" font-size="3.2" class="cf-t">harness + model</text>
        <line x1="41.4" y1="58" x2="55" y2="58" stroke-width=".9" class="cf-int-s"></line>
        <line x1="95" y1="32" x2="109" y2="32" stroke="#B45309" stroke-width=".9"></line>
        <rect x="109" y="23" width="38" height="19" rx="3" fill="#FAE3C8" stroke="#B45309" stroke-width=".7"></rect>
        <text x="112" y="30.5" font-size="3.9" font-weight="600" fill="#7A3A05">Rollout inference</text>
        <text x="112" y="36" font-size="3" fill="#7A3A05">generating trajectories</text>
        <circle cx="146" cy="24.5" r="2.4" fill="#B45309"></circle><text x="146" y="25.6" text-anchor="middle" font-size="3" font-weight="600" fill="#fff">$</text>
        <line x1="128" y1="42.4" x2="128" y2="48.4" stroke="#B45309" stroke-width=".7" marker-end="url(#cf-h1)"></line>
        <rect x="109" y="49" width="38" height="19" rx="3" fill="#FAE3C8" stroke="#B45309" stroke-width=".7"></rect>
        <text x="112" y="56" font-size="3.9" font-weight="600" fill="#7A3A05">Experience</text>
        <text x="112" y="61.2" font-size="3" fill="#7A3A05">stored trajectories</text>
        <text x="112" y="65" font-size="3" fill="#7A3A05">and rewards</text>
        <circle cx="146" cy="50.5" r="2.4" fill="#B45309"></circle><text x="146" y="51.6" text-anchor="middle" font-size="3" font-weight="600" fill="#fff">$</text>
        <line x1="128" y1="68.4" x2="128" y2="74.4" stroke="#B45309" stroke-width=".7" marker-end="url(#cf-h1)"></line>
        <rect x="109" y="75" width="38" height="19" rx="3" fill="#B45309" stroke="#7A3A05" stroke-width=".7"></rect>
        <text x="112" y="82" font-size="4.2" font-weight="600" fill="#fff">Internalize</text>
        <text x="112" y="87.2" font-size="2.9" fill="#FDEBDD">weight updates,</text>
        <text x="112" y="91" font-size="2.9" fill="#FDEBDD">rewriting code, prompts</text>
        <circle cx="146" cy="76.5" r="2.4" fill="#fff"></circle><text x="146" y="77.6" text-anchor="middle" font-size="3" font-weight="600" fill="#B45309">$</text>
        <line x1="108.6" y1="85" x2="96" y2="85" stroke-width=".8" marker-end="url(#cf-h2)" class="cf-upd-s"></line>
        <text x="102" y="82.6" text-anchor="middle" font-size="2.9" font-weight="600" class="cf-upd">update</text>
      </svg>
      <figcaption>
        Where an agent's cost comes from while it learns: <span class="c-int">interaction</span> is charged by the environment, <span class="c-comp">computation</span> by the infrastructure, and internalizing experience turns per-task cost into a one-time cost.
      </figcaption>
    </figure>
  </div>
</div>

<script>
  (function () {
    document.querySelectorAll(".jc-step[data-target]").forEach(function (el) {
      el.addEventListener("click", function (e) {
        e.preventDefault();
        var target = document.getElementById(el.getAttribute("data-target"));
        if (!target) return;
        target.open = true;
        target.scrollIntoView({ behavior: "smooth", block: "start" });
      });
    });
  })();
</script>

## experience

<div class="jc-exp">
  <img src="/assets/img/logos/tencent.png" alt="Tencent">
  <div>
    <span class="jc-when">Jan 2026 – May 2026</span>
    <strong>Tencent</strong>, LightSpeed Studios · Game AI Lab
    <p>Research Intern (Qingyun Program). Post-training VLMs for spatial reasoning with programmatically synthesized 3D-scene QA data.</p>
  </div>
  <img src="/assets/img/logos/shlab.png" alt="Shanghai AI Laboratory">
  <div>
    <span class="jc-when">Feb 2025 – Oct 2025</span>
    <strong>Shanghai AI Laboratory</strong>, Post-training Team
    <p>Research Intern, with Wenwei Zhang and Kai Chen. End-to-end agentic RL for long-horizon deep-search agents, RL infrastructure, and evaluation data for Intern-S1.</p>
  </div>
</div>
