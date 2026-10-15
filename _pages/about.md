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
      <a href="/cv/" title="CV"><i class="ai ai-cv"></i></a>
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
  .jc-logos{display:flex;flex-wrap:wrap;align-items:center;gap:1.2rem;margin:.1rem 0 1.3rem}
  .jc-logos a{display:inline-flex;line-height:0;transition:transform .15s}
  .jc-logos a:hover{transform:translateY(-2px)}
  .jc-logos img{height:46px;width:auto}
  html[data-theme="dark"] .jc-logos img,html[data-theme="dark"] .jc-exp img{background:#fff;border-radius:6px;padding:3px}
  .jc-profile-icons{font-size:1.6rem;text-align:center;margin-top:.4rem}
  .jc-profile-icons a{margin:0 .35rem}
  .jc-profile-note{text-align:center;font-size:.85rem;opacity:.75;margin:.2rem 0 0}

  .jc-wrap{clear:both;display:grid;grid-template-columns:minmax(0,1.15fr) minmax(0,1fr);gap:1.25rem;align-items:start;margin:1.4rem 0 1.8rem;font-size:.95rem}
  .jc-left{min-width:0}
  .jc-right{position:sticky;top:80px;min-width:0}
  @media (max-width:820px){.jc-wrap{grid-template-columns:1fr}.jc-right{position:static;order:-1}}

  .jc-diagram{position:relative;width:100%;max-width:370px;aspect-ratio:1/1;margin:0 auto}
  .jc-diagram svg{position:absolute;inset:0;width:100%;height:100%;z-index:0}
  .jc-spoke{stroke:var(--global-theme-color);stroke-width:.6;stroke-dasharray:1.5 1.5;opacity:.45}
  .jc-loop{stroke:var(--global-theme-color);stroke-width:.9;fill:none;stroke-linecap:round}
  .jc-arrow{fill:var(--global-theme-color)}
  .jc-diagram text{fill:var(--global-theme-color);font-size:3.2px;font-style:italic;font-weight:500;letter-spacing:.1px}
  .jc-node{position:absolute;z-index:1;box-sizing:border-box;border-radius:50%;display:flex;flex-direction:column;align-items:center;justify-content:center;text-align:center;padding:.35rem;text-decoration:none!important;transform:translate(-50%,-50%);transition:transform .15s,box-shadow .15s,border-color .15s;cursor:pointer}
  .jc-node:hover{transform:translate(-50%,-50%) scale(1.06)}
  .jc-center{top:50%;left:50%;width:32%;height:32%;background:var(--global-theme-color);border:3px solid var(--global-theme-color);box-shadow:0 5px 14px rgba(0,0,0,.18)}
  .jc-center strong{color:#fff;font-size:.9rem;line-height:1.12;font-weight:700}
  .jc-center span{color:#fff;font-size:.62rem;opacity:.92;margin-top:.25rem;white-space:nowrap}
  .jc-orbit{width:24%;height:24%;border:1.5px solid var(--global-divider-color);background:var(--global-card-bg-color)}
  .jc-orbit:hover{border-color:var(--global-theme-color);box-shadow:0 4px 12px rgba(0,0,0,.1)}
  .jc-orbit strong{color:var(--global-theme-color);font-size:.78rem;line-height:1.1;font-weight:600}
  .jc-orbit span{color:var(--global-text-color);font-size:.56rem;opacity:.8;margin-top:.15rem;line-height:1.15}
  .jc-n1{top:18%;left:50%}.jc-n2{top:66%;left:78%}.jc-n3{top:66%;left:22%}
  @media (max-width:520px){.jc-center strong{font-size:.76rem}.jc-orbit strong{font-size:.66rem}.jc-orbit span,.jc-center span{font-size:.5rem}}

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
  .jc-ongoing{opacity:.75;font-style:italic}

  .jc-exp{display:grid;grid-template-columns:72px minmax(0,1fr);gap:1rem 1.1rem;align-items:start;margin:.6rem 0 1.6rem}
  .jc-exp img{width:72px;max-height:44px;object-fit:contain;margin-top:.15rem}
  .jc-exp .jc-when{float:right;font-size:.85rem;opacity:.7;margin-left:.6rem}
  .jc-exp p{margin:.15rem 0 0;font-size:.92rem}
</style>

<div class="jc-logos">
  <a href="https://www.polyu.edu.hk/" title="The Hong Kong Polytechnic University" target="_blank" rel="noopener"><img src="/assets/img/logos/polyu.png" alt="The Hong Kong Polytechnic University"></a>
  <a href="http://www.ia.cas.cn/" title="Institute of Automation, Chinese Academy of Sciences" target="_blank" rel="noopener"><img src="/assets/img/logos/casia.png" alt="Institute of Automation, Chinese Academy of Sciences"></a>
  <a href="https://www.nju.edu.cn/" title="Nanjing University" target="_blank" rel="noopener"><img src="/assets/img/logos/nju.png" alt="Nanjing University"></a>
  <a href="https://www.sdu.edu.cn/" title="Shandong University" target="_blank" rel="noopener"><img src="/assets/img/logos/sdu.png" alt="Shandong University"></a>
</div>

I am a Ph.D. student at [The Hong Kong Polytechnic University](https://www.polyu.edu.hk/) (PolyU), advised by [Prof. Qing Li](https://www4.comp.polyu.edu.hk/~csqli/) (IEEE Fellow), [Prof. Zhen Lei](http://www.cbsr.ia.ac.cn/users/zlei/) (IEEE Fellow) and [Prof. Zhaoxiang Zhang](https://zhaoxiangzhang.net/). Before that, I received my M.S. in Computer Science from [Nanjing University](https://www.nju.edu.cn/) under the supervision of Prof. Yihua Huang, and my B.S. in Software Engineering from [Shandong University](https://www.sdu.edu.cn/). I have also been a research intern on the post-training team at [Shanghai AI Laboratory](https://www.shlab.org.cn/) and at Tencent Game AI Lab.

My research focuses on **self-improving computer-use agents**: multimodal agents that read a screen, act in real software, and keep getting better from their own experience, at a cost that makes them practical. I follow one line of work from reliable _perception and grounding_, to reliable _reasoning_, to reliable _action_ in long-horizon agentic settings, and most of my methods are built on on-policy reinforcement learning. For more, see my [CV](/cv/).

<div class="jc-wrap">
  <div class="jc-left">
    <details class="jc-card" id="rf-cua" open>
      <summary><span>Computer-Use Agents <small>— perceive &amp; act on real software</small></span></summary>
      <div class="jc-body">
        <h4>Research Questions</h4>
        <ul>
          <li><strong>How</strong> can an agent find the right element on a dense, high-resolution screen without paying for every pixel?</li>
          <li><strong>How</strong> can we scale GUI data and unify action spaces across platforms without human labels?</li>
        </ul>
        <h4>Representative Works</h4>
        <ul>
          <li><a href="/publications/#chen2026foveaui">FoveaUI: Foveated On-demand Visual Evidence Acquisition for GUI Grounding</a> <span class="jc-venue">(ACM MM 2026)</span></li>
          <li><a href="https://arxiv.org/abs/2509.17328" target="_blank" rel="noopener">UIPro: Unleashing Superior Interaction Capability For GUI Agents</a> <span class="jc-venue">(ICCV 2025)</span></li>
          <li><a href="https://aclanthology.org/2025.acl-long.510" target="_blank" rel="noopener">AutoGUI: Scaling GUI Grounding with Automatic Functionality Annotations from LLMs</a> <span class="jc-venue">(ACL 2025)</span></li>
        </ul>
      </div>
    </details>
    <details class="jc-card" id="rf-wm">
      <summary><span>World Models <small>— predict what happens next</small></span></summary>
      <div class="jc-body">
        <h4>Research Questions</h4>
        <ul>
          <li><strong>Can</strong> an agent predict how a GUI or a 3D scene will change after it acts?</li>
          <li><strong>How</strong> should an explicit model of space or interface state support planning and self-checking?</li>
        </ul>
        <h4>Representative Works</h4>
        <ul>
          <li class="jc-ongoing">Ongoing work on spatial world modeling for multimodal reasoning. Stay tuned.</li>
        </ul>
      </div>
    </details>
    <details class="jc-card" id="rf-rsi">
      <summary><span>Recursive Self-Improvement <small>— learn from own experience</small></span></summary>
      <div class="jc-body">
        <h4>Research Questions</h4>
        <ul>
          <li><strong>How</strong> can a model turn its own rollouts and failures into a better training signal?</li>
          <li><strong>How</strong> do we keep exploration alive while a model keeps improving itself?</li>
        </ul>
        <h4>Representative Works</h4>
        <ul>
          <li><a href="/publications/#chen2026warmup">Warm Up with a Rubric, Then Merge: Decoupling Grounding Gains from Reasoning Costs in Vision-Language Models</a> <span class="jc-venue">(EMNLP 2026)</span></li>
          <li class="jc-ongoing">Ongoing work on on-policy reflection for deep-search agents and on-policy self-revision for safe reasoning.</li>
        </ul>
      </div>
    </details>
    <details class="jc-card" id="rf-eff">
      <summary><span>Agentic Efficiency <small>— compute where it matters</small></span></summary>
      <div class="jc-body">
        <h4>Research Questions</h4>
        <ul>
          <li><strong>When</strong> does an agent need to look closer, and when is a glance enough?</li>
          <li><strong>Can</strong> we keep the benefit of expensive supervision while paying for it only once?</li>
        </ul>
        <h4>Representative Works</h4>
        <ul>
          <li><a href="/publications/#chen2026foveaui">FoveaUI: Foveated On-demand Visual Evidence Acquisition for GUI Grounding</a> <span class="jc-venue">(ACM MM 2026)</span></li>
          <li><a href="/publications/#chen2026warmup">Warm Up with a Rubric, Then Merge</a> <span class="jc-venue">(EMNLP 2026)</span></li>
        </ul>
      </div>
    </details>
  </div>

  <div class="jc-right">
    <div class="jc-diagram" aria-label="Research focus diagram">
      <svg viewBox="0 0 100 100" preserveAspectRatio="xMidYMid meet" aria-hidden="true">
        <defs>
          <marker id="jc-head" viewBox="0 0 10 10" refX="8" refY="5" markerWidth="5" markerHeight="5" orient="auto-start-reverse">
            <path d="M 0 0 L 10 5 L 0 10 z" class="jc-arrow"></path>
          </marker>
        </defs>
        <line class="jc-spoke" x1="50" y1="50" x2="50" y2="18"></line>
        <line class="jc-spoke" x1="50" y1="50" x2="78" y2="66"></line>
        <line class="jc-spoke" x1="50" y1="50" x2="22" y2="66"></line>
        <path class="jc-loop" d="M 63.28 18.70 A 34 34 0 0 1 75.27 27.25"></path>
        <path class="jc-loop" d="M 82.34 39.49 A 34 34 0 0 1 83.77 53.97" marker-end="url(#jc-head)"></path>
        <text x="79.4" y="32.2" text-anchor="middle"><tspan x="79.4" dy="0">imagined</tspan><tspan x="79.4" dy="3.6">rollouts</tspan></text>
        <path class="jc-loop" d="M 70.60 77.05 A 34 34 0 0 1 57.07 83.26"></path>
        <path class="jc-loop" d="M 42.93 83.26 A 34 34 0 0 1 29.40 77.05" marker-end="url(#jc-head)"></path>
        <text x="50" y="83.2" text-anchor="middle"><tspan x="50" dy="0">learn to</tspan><tspan x="50" dy="3.6">act cheaply</tspan></text>
        <path class="jc-loop" d="M 16.23 53.97 A 34 34 0 0 1 17.66 39.49"></path>
        <path class="jc-loop" d="M 24.73 27.25 A 34 34 0 0 1 36.72 18.70" marker-end="url(#jc-head)"></path>
        <text x="20.6" y="32.2" text-anchor="middle"><tspan x="20.6" dy="0">budget the</tspan><tspan x="20.6" dy="3.6">lookahead</tspan></text>
      </svg>
      <a class="jc-node jc-center" data-target="rf-cua" href="#rf-cua"><strong>Computer-Use<br>Agents</strong><span>perceive ⇆ act</span></a>
      <a class="jc-node jc-orbit jc-n1" data-target="rf-wm" href="#rf-wm"><strong>World Models</strong><span>predict what's next</span></a>
      <a class="jc-node jc-orbit jc-n2" data-target="rf-rsi" href="#rf-rsi"><strong>Self-Improvement</strong><span>learn from own rollouts</span></a>
      <a class="jc-node jc-orbit jc-n3" data-target="rf-eff" href="#rf-eff"><strong>Efficiency</strong><span>compute where it matters</span></a>
    </div>
  </div>
</div>

<script>
  (function () {
    document.querySelectorAll(".jc-node[data-target]").forEach(function (el) {
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
