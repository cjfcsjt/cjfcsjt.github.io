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
  .profile figure.jc-swap{position:relative;cursor:pointer}
  .profile figure.jc-swap .jc-hover-img{position:absolute;top:0;left:0;width:100%;height:100%;object-fit:cover;opacity:0;transition:opacity .6s ease;pointer-events:none}
  .profile figure.jc-swap:hover .jc-hover-img,.profile figure.jc-swap.jc-on .jc-hover-img{opacity:1}
  @media (prefers-reduced-motion:reduce){.profile figure.jc-swap .jc-hover-img{transition:none}}
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
  @media (max-width:760px){.jc-flow{flex-direction:column}.jc-flow-arrow{transform:rotate(90deg);margin:-.2rem 0}}

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

  .jc-figure{margin:0}
  .jc-figure svg{display:block;width:100%;height:auto;max-width:440px;margin:0 auto}
  .jc-figure .box-solver{fill:#2e7d9a}
  .jc-figure .box-improver{fill:#c8553d}
  .jc-figure .box-neutral{fill:var(--global-card-bg-color);stroke:var(--global-divider-color);stroke-width:.5}
  .jc-figure .box-retain{fill:var(--global-card-bg-color);stroke:#c8553d;stroke-width:.6;stroke-dasharray:2 1.4}
  .jc-figure .t-light{fill:#fff}
  .jc-figure .t-dark{fill:var(--global-text-color)}
  .jc-figure .t-title{font-size:5px;font-weight:700}
  .jc-figure .t-sub{font-size:3.3px;opacity:.85}
  .jc-figure .t-label{font-size:3.3px;fill:var(--global-text-color);opacity:.75}
  .jc-figure .t-solver{font-size:3.5px;font-weight:700;fill:#2e7d9a}
  .jc-figure .t-improver{font-size:3.5px;font-weight:700;fill:#c8553d}
  .jc-figure .a-gray{stroke:var(--global-text-color);stroke-opacity:.55;stroke-width:.6;fill:none}
  .jc-figure .a-solver{stroke:#2e7d9a;stroke-width:1.1;fill:none}
  .jc-figure .a-improver{stroke:#c8553d;stroke-width:1.1;stroke-dasharray:2.2 1.4;fill:none}
  .jc-figure .h-gray{fill:var(--global-text-color);fill-opacity:.55}
  .jc-figure .h-solver{fill:#2e7d9a}
  .jc-figure .h-improver{fill:#c8553d}
  .jc-figure figcaption{font-size:.82rem;line-height:1.45;opacity:.85;margin-top:.5rem}
  .jc-figure figcaption .c-solver{color:#2e7d9a;font-weight:600}
  .jc-figure figcaption .c-improver{color:#c8553d;font-weight:600}

  .jc-exp{display:grid;grid-template-columns:72px minmax(0,1fr);gap:1rem 1.1rem;align-items:start;margin:.6rem 0 1.6rem}
  .jc-exp img{width:72px;max-height:44px;object-fit:contain;margin-top:.15rem}
  .jc-exp .jc-when{float:right;font-size:.85rem;opacity:.7;margin-left:.6rem}
  .jc-exp p{margin:.15rem 0 0;font-size:.92rem}
</style>

I am a Ph.D. student at [The Hong Kong Polytechnic University](https://www.polyu.edu.hk/) (PolyU), advised by [Prof. Qing Li](https://www4.comp.polyu.edu.hk/~csqli/) (IEEE Fellow), [Prof. Zhen Lei](http://www.cbsr.ia.ac.cn/users/zlei/) (IEEE Fellow) and [Prof. Zhaoxiang Zhang](https://zhaoxiangzhang.net/). Before that, I received my M.S. in Computer Science from Nanjing University and my B.S. in Software Engineering from Shandong University. I have also been a research intern on the post-training team at [Shanghai AI Laboratory](https://www.shlab.org.cn/) and at Tencent Game AI Lab.

My research focuses on **self-improvement for computer use**.

<div class="jc-flow">
  <a class="jc-step" data-target="rf-rsi" href="#rf-rsi"><span class="jc-num">01</span><strong>Recursive Self-Improvement</strong><small>improve the improver</small></a>
  <span class="jc-flow-arrow" aria-hidden="true">→</span>
  <a class="jc-step" data-target="rf-code" href="#rf-code"><span class="jc-num">02</span><strong>Code as the Substrate</strong><small>target · evidence · verification</small></a>
  <span class="jc-flow-arrow" aria-hidden="true">→</span>
  <a class="jc-step" data-target="rf-cu" href="#rf-cu"><span class="jc-num">03</span><strong>Computer Use</strong><small>GUI agents on real software</small></a>
  <span class="jc-flow-arrow" aria-hidden="true">→</span>
  <a class="jc-step" data-target="rf-app" href="#rf-app"><span class="jc-num">04</span><strong>Applications</strong><small>digital world · physical world</small></a>
</div>

<div class="jc-wrap">
  <div class="jc-left">
    <details class="jc-card" id="rf-rsi" open>
      <summary><span>Recursive Self-Improvement <small>— improve the improver</small></span></summary>
      <div class="jc-body">
        <h4>Research Questions</h4>
        <ul>
          <li><strong>What</strong> makes a computer-use agent's self-improvement recursive, rather than a solver updated by a fixed improver?</li>
          <li><strong>How</strong> can we tell whether an updated improver really makes later rounds of improvement more effective, at the same budget?</li>
        </ul>
        <h4>Representative Works</h4>
        <ul>
          <li class="jc-ongoing">Ongoing work on improver-level self-modification for computer-use agents and how to evaluate it.</li>
        </ul>
      </div>
    </details>
    <details class="jc-card" id="rf-code">
      <summary><span>Code as the Substrate <small>— target · evidence · verification</small></span></summary>
      <div class="jc-body">
        <h4>Research Questions</h4>
        <ul>
          <li><strong>Why</strong> does recursion need code: what makes an improver's own mechanism modifiable, its changes attributable, and its results checkable?</li>
          <li><strong>How</strong> far can executable checks on software state (UI source, DOM, app state) make verifying a new improver affordable, and where must evidence still come from the live environment?</li>
        </ul>
        <h4>Representative Works</h4>
        <ul>
          <li><a href="https://aclanthology.org/2025.acl-long.510" target="_blank" rel="noopener">AutoGUI: Scaling GUI Grounding with Automatic Functionality Annotations from LLMs</a> <span class="jc-venue">(ACL 2025)</span>: infers what a UI element does from how the UI's source code changes after a simulated interaction.</li>
          <li class="jc-ongoing">Ongoing work on code as the substrate for recursive self-improvement.</li>
        </ul>
      </div>
    </details>
    <details class="jc-card" id="rf-cu">
      <summary><span>Computer Use <small>— where the loop meets real software</small></span></summary>
      <div class="jc-body">
        <h4>Research Questions</h4>
        <ul>
          <li><strong>How</strong> does an improvement loop carry over to agents that act on real software, where task success is only partly checkable by code?</li>
          <li><strong>When</strong> is an extra look at the screen, or an extra round of supervision, worth its cost, and how can an agent spend it only where it is needed?</li>
        </ul>
        <h4>Representative Works</h4>
        <p class="jc-domain">GUI grounding &amp; interaction</p>
        <ul>
          <li><a href="/publications/#chen2026foveaui">FoveaUI: Foveated On-demand Visual Evidence Acquisition for GUI Grounding</a> <span class="jc-venue">(ACM MM 2026)</span></li>
          <li><a href="https://arxiv.org/abs/2509.17328" target="_blank" rel="noopener">UIPro: Unleashing Superior Interaction Capability For GUI Agents</a> <span class="jc-venue">(ICCV 2025)</span></li>
          <li><a href="https://aclanthology.org/2025.acl-long.510" target="_blank" rel="noopener">AutoGUI: Scaling GUI Grounding with Automatic Functionality Annotations from LLMs</a> <span class="jc-venue">(ACL 2025)</span></li>
        </ul>
        <p class="jc-domain">Visual perception &amp; reasoning for agents</p>
        <ul>
          <li><a href="/publications/#chen2026warmup">Warm Up with a Rubric, Then Merge: Decoupling Grounding Gains from Reasoning Costs in Vision-Language Models</a> <span class="jc-venue">(EMNLP 2026)</span></li>
          <li><a href="https://aclanthology.org/2025.acl-long.634" target="_blank" rel="noopener">Activation Steering Decoding: Mitigating Hallucination in Large Vision-Language Models through Bidirectional Hidden State Intervention</a> <span class="jc-venue">(ACL 2025)</span></li>
        </ul>
      </div>
    </details>
    <details class="jc-card" id="rf-app">
      <summary><span>Applications <small>— digital world · physical world</small></span></summary>
      <div class="jc-body">
        <h4>Research Questions</h4>
        <ul>
          <li><strong>How</strong> far does an improvement loop built for software reach in the digital world, on long-horizon tasks such as deep search?</li>
          <li><strong>What</strong> changes in the physical world, where outcomes cannot be checked by running code and evidence must come from 3D scenes, simulators or real environments?</li>
        </ul>
        <h4>Representative Works</h4>
        <ul>
          <li><a href="https://x.com/XGEN_labs/article/2103137462008844442" target="_blank" rel="noopener">Dual Exam: Controlled Evaluation of Multimodal Agents and World Models</a> <span class="jc-venue">(XGEN Labs Tech Report 2026)</span>: agent and world-model tracks across physical, digital, social and scientific tasks.</li>
        </ul>
        <p class="jc-domain">Digital world</p>
        <ul>
          <li class="jc-ongoing">Ongoing work on agentic RL and self-reflection for long-horizon deep-search agents.</li>
        </ul>
        <p class="jc-domain">Physical world</p>
        <ul>
          <li class="jc-ongoing">Ongoing work on spatial reasoning in 3D scenes for multimodal models.</li>
        </ul>
      </div>
    </details>
  </div>

  <div class="jc-right">
    <figure class="jc-figure">
      <svg viewBox="0 0 120 98" role="img" aria-label="One round of recursive self-improvement: the solver runs tasks, its experience goes to the improver, the improver proposes candidates, verification decides what is kept, and accepted updates are written back to the solver and, in RSI, to the improver itself.">
        <defs>
          <marker id="jc-h-gray" viewBox="0 0 10 10" refX="8" refY="5" markerWidth="4" markerHeight="4" orient="auto-start-reverse"><path d="M0 0L10 5L0 10z" class="h-gray"></path></marker>
          <marker id="jc-h-solver" viewBox="0 0 10 10" refX="8" refY="5" markerWidth="3.6" markerHeight="3.6" orient="auto-start-reverse"><path d="M0 0L10 5L0 10z" class="h-solver"></path></marker>
          <marker id="jc-h-improver" viewBox="0 0 10 10" refX="8" refY="5" markerWidth="3.6" markerHeight="3.6" orient="auto-start-reverse"><path d="M0 0L10 5L0 10z" class="h-improver"></path></marker>
        </defs>
        <rect x="3" y="6" width="46" height="22" rx="3" class="box-solver"></rect>
        <text x="26" y="16" text-anchor="middle" class="t-light t-title">Solver S<tspan dy="1.2" font-size="3.4">t</tspan></text>
        <text x="26" y="22.5" text-anchor="middle" class="t-light t-sub">solves tasks</text>
        <rect x="71" y="6" width="46" height="22" rx="3" class="box-neutral"></rect>
        <text x="94" y="16" text-anchor="middle" class="t-dark t-title">Experience E<tspan dy="1.2" font-size="3.4">t</tspan></text>
        <text x="94" y="22.5" text-anchor="middle" class="t-dark t-sub">traces · scores · probes</text>
        <rect x="71" y="60" width="46" height="24" rx="3" class="box-improver"></rect>
        <text x="94" y="70.5" text-anchor="middle" class="t-light t-title">Improver I<tspan dy="1.2" font-size="3.4">t</tspan></text>
        <text x="94" y="77" text-anchor="middle" class="t-light t-sub">proposes updates</text>
        <rect x="3" y="60" width="46" height="24" rx="3" class="box-retain"></rect>
        <text x="26" y="70.5" text-anchor="middle" class="t-dark t-title">Verify &amp; retain</text>
        <text x="26" y="77" text-anchor="middle" class="t-dark t-sub">accept or reject</text>
        <line x1="49.5" y1="17" x2="70" y2="17" class="a-gray" marker-end="url(#jc-h-gray)"></line>
        <text x="60" y="14" text-anchor="middle" class="t-label">run</text>
        <line x1="94" y1="28.5" x2="94" y2="59" class="a-gray" marker-end="url(#jc-h-gray)"></line>
        <text x="96" y="45" class="t-label">experience</text>
        <line x1="70.5" y1="66" x2="50" y2="66" class="a-gray" marker-end="url(#jc-h-gray)"></line>
        <text x="60" y="63.5" text-anchor="middle" class="t-label">candidates</text>
        <line x1="18" y1="59.5" x2="18" y2="29" class="a-solver" marker-end="url(#jc-h-solver)"></line>
        <text x="20.5" y="43" class="t-solver">update</text>
        <text x="20.5" y="47.2" class="t-solver">solver</text>
        <line x1="49.5" y1="79" x2="70" y2="79" class="a-improver" marker-end="url(#jc-h-improver)"></line>
        <text x="60" y="92" text-anchor="middle" class="t-improver">update improver (RSI)</text>
      </svg>
      <figcaption>
        One round of improvement. <span class="c-solver">Solid</span>: accepted updates are written back to the solver, as in ordinary self-improvement. <span class="c-improver">Dashed</span>: in RSI they are also written back to the improver, so the next round is produced by a better improver. Adapted from <a href="https://www.preprints.org/manuscript/202609.2680" target="_blank" rel="noopener">Wu et al., Recursive Self-Improvement in AI: A Survey (2026)</a>.
      </figcaption>
    </figure>
  </div>
</div>

<script>
  (function () {
    var fig = document.querySelector(".profile figure");
    var base = fig && fig.querySelector("img");
    if (!base) return;
    var hover = new Image();
    hover.src = "/assets/img/prof_pic_hover.jpg";
    hover.alt = "";
    hover.setAttribute("aria-hidden", "true");
    hover.className = "jc-hover-img " + base.className;
    fig.classList.add("jc-swap");
    fig.appendChild(hover);
    // touch screens have no hover: tap to switch between the two photos
    fig.addEventListener("click", function () {
      if (window.matchMedia("(hover: none)").matches) fig.classList.toggle("jc-on");
    });
  })();
</script>

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

My earlier work focused on **information retrieval**, including recommender systems, graph learning and the robustness of recommenders (e.g., [KGAttack](https://arxiv.org/abs/2207.10307), KDD 2022), with papers at KDD, SIGIR, WWW and CIKM.

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
