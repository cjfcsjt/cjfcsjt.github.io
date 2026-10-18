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

  .jc-costfig{clear:both;position:relative;width:min(1240px,calc(100vw - 48px));left:50%;transform:translateX(-50%);margin:1.6rem 0 .4rem;border-radius:14px;overflow:hidden;box-shadow:0 2px 10px rgba(0,0,0,.08)}
  .jc-costfig-inner{width:1552px;height:1336px;transform-origin:0 0}
  .jc-costfig-cap{font-size:.85rem;opacity:.85;margin:.4rem 0 1.2rem}
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
  .jc-tags{display:flex;flex-wrap:wrap;gap:.35rem;margin:.1rem 0 .5rem}
  .jc-tags span{font-size:.78rem;padding:.12rem .6rem;border:1px solid var(--global-divider-color);border-radius:999px;color:var(--global-theme-color)}

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

My research focuses on **Efficient LLM Agents**, **Agentic Computer Use** and **Recursive Self-Improvement (RSI)**.

<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=IBM+Plex+Sans:wght@400;600&amp;family=IBM+Plex+Serif:wght@600&amp;display=swap" rel="stylesheet">
<div class="jc-costfig" id="jc-costfig">
<div class="jc-costfig-inner">
<div style="position: relative; width: 1552px; height: 1336px; background: #F7F7F5; color: #1C1C1A; font-family: 'IBM Plex Sans', 'Helvetica Neue', sans-serif; overflow: hidden">
<div style="position: absolute; left: 64px; top: 416px; width: 1424px; height: 320px; background: #F0EEE9; border-radius: 16px"></div>
<div style="position: absolute; left: 64px; top: 792px; width: 1424px; height: 184px; background: #F0EEE9; border-radius: 16px"></div>
<svg aria-hidden="true" width="288" height="192" viewBox="0 0 288 192" style="position: absolute; left: 1184px; top: 72px; width: 288px; height: 192px; overflow: visible"><path d="M 0 0 L 0 192 L 288 192" fill="none" stroke="#3D3C38" stroke-width="1.5"></path><path d="M 6 182 C 40 70, 120 28, 284 14" fill="none" stroke="#B8B5AC" stroke-width="2" stroke-dasharray="5 5"></path><defs><marker id="dc-arrow-head-filled-1" orient="auto" markerWidth="5" markerHeight="5" refX="2" refY="2" overflow="visible"><path d="M0 0 L4 2 L0 4 Z" fill="#1C1C1A" stroke="none" style="stroke: none; fill: #1C1C1A; fill: context-stroke"/></marker></defs><path d="M 205 107 L 110 66" fill="none" stroke="#1C1C1A" stroke-width="2" stroke-linecap="round" marker-end="url(#dc-arrow-head-filled-1)"></path><circle cx="214" cy="112" r="7" fill="#8A8378"></circle><circle cx="96" cy="58" r="8" fill="#1C1C1A"></circle></svg>
<svg aria-hidden="true" width="120" height="8" viewBox="0 0 120 8" preserveAspectRatio="none" style="position: absolute; left: 552px; top: 572px; width: 120px; height: 8px; overflow: visible; fill: none; stroke: #1F5F8B; stroke-width: 3; stroke-linecap: round; stroke-linejoin: round"><path d="M 0 4 L 120 4"></path></svg>
<svg aria-hidden="true" width="120" height="8" viewBox="0 0 120 8" preserveAspectRatio="none" style="position: absolute; left: 1048px; top: 468px; width: 120px; height: 8px; overflow: visible; fill: none; stroke: #B45309; stroke-width: 3; stroke-linecap: round; stroke-linejoin: round"><path d="M 0 4 L 120 4"></path></svg>
<svg aria-hidden="true" width="8" height="39" viewBox="0 0 8 39" preserveAspectRatio="none" style="position: absolute; left: 1324px; top: 504px; width: 8px; height: 39px; overflow: visible; fill: none; stroke: #B45309; stroke-width: 2; stroke-linecap: round; stroke-linejoin: round"><defs><marker id="dc-arrow-head-filled-2" orient="auto" markerWidth="5" markerHeight="5" refX="2" refY="2" overflow="visible"><path d="M0 0 L4 2 L0 4 Z" fill="#B45309" stroke="none" style="stroke: none; fill: #B45309; fill: context-stroke"/></marker></defs><path d="M 4 0 L 4 35" marker-end="url(#dc-arrow-head-filled-2)"></path></svg>
<svg aria-hidden="true" width="8" height="39" viewBox="0 0 8 39" preserveAspectRatio="none" style="position: absolute; left: 1324px; top: 608px; width: 8px; height: 39px; overflow: visible; fill: none; stroke: #B45309; stroke-width: 2; stroke-linecap: round; stroke-linejoin: round"><defs><marker id="dc-arrow-head-filled-3" orient="auto" markerWidth="5" markerHeight="5" refX="2" refY="2" overflow="visible"><path d="M0 0 L4 2 L0 4 Z" fill="#B45309" stroke="none" style="stroke: none; fill: #B45309; fill: context-stroke"/></marker></defs><path d="M 4 0 L 4 35" marker-end="url(#dc-arrow-head-filled-3)"></path></svg>
<svg aria-hidden="true" width="119" height="8" viewBox="0 0 119 8" preserveAspectRatio="none" style="position: absolute; left: 1049px; top: 676px; width: 119px; height: 8px; overflow: visible; fill: none; stroke: #7A3A05; stroke-width: 2.5; stroke-linecap: round; stroke-linejoin: round"><defs><marker id="dc-arrow-head-filled-4" orient="auto" markerWidth="5" markerHeight="5" refX="2" refY="2" overflow="visible"><path d="M0 0 L4 2 L0 4 Z" fill="#7A3A05" stroke="none" style="stroke: none; fill: #7A3A05; fill: context-stroke"/></marker></defs><path d="M 119 4 L 5 4" marker-end="url(#dc-arrow-head-filled-4)"></path></svg>
<svg aria-hidden="true" width="8" height="95" viewBox="0 0 8 95" preserveAspectRatio="none" style="position: absolute; left: 856px; top: 712px; width: 8px; height: 95px; overflow: visible; fill: none; stroke: #8A8378; stroke-width: 2; stroke-linecap: round; stroke-linejoin: round"><defs><marker id="dc-arrow-head-filled-5" orient="auto" markerWidth="5" markerHeight="5" refX="2" refY="2" overflow="visible"><path d="M0 0 L4 2 L0 4 Z" fill="#8A8378" stroke="none" style="stroke: none; fill: #8A8378; fill: context-stroke"/></marker></defs><path d="M 4 0 L 4 91" marker-end="url(#dc-arrow-head-filled-5)"></path></svg>
<svg aria-hidden="true" width="120" height="8" viewBox="0 0 120 8" preserveAspectRatio="none" style="position: absolute; left: 552px; top: 876px; width: 120px; height: 8px; overflow: visible; fill: none; stroke: #1F5F8B; stroke-width: 3; stroke-linecap: round; stroke-linejoin: round"><path d="M 0 4 L 120 4"></path></svg>
<svg aria-hidden="true" width="120" height="8" viewBox="0 0 120 8" preserveAspectRatio="none" style="position: absolute; left: 1048px; top: 876px; width: 120px; height: 8px; overflow: visible; fill: none; stroke: #B45309; stroke-width: 3; stroke-linecap: round; stroke-linejoin: round"><path d="M 0 4 L 120 4"></path></svg>
<div style="position: absolute; left: 64px; top: 56px; width: 1000px; font-family: 'IBM Plex Serif', Georgia, serif; font-size: 40px; line-height: 48px; font-weight: 600">Efficient Agentic Systems</div>
<div style="position: absolute; left: 64px; top: 112px; width: 1000px; font-size: 18px; line-height: 26px; color: #5F5E5A">An agent pays for every interaction with its environment and for every computation it runs, while it learns and after it is deployed.</div>
<div style="position: absolute; left: 64px; top: 200px; width: 1000px; height: 96px; box-sizing: border-box; padding: 16px 28px; display: flex; align-items: center; background: #1C1C1A; border-radius: 12px; font-size: 15px; line-height: 24px; color: #D9D7D0"><span><b style="font-size: 20px; line-height: 30px; color: #FAFAF7">Objective: the same or better accuracy at a lower cost</b><br>amortized cost per task = per-task deployment cost + one-time learning cost ÷ N  ·  N = number of tasks served</span></div>
<div style="position: absolute; left: 1136px; top: 40px; width: 352px; text-align: center; font-size: 15px; line-height: 20px; font-weight: 600; color: #1C1C1A">The goal, at a glance</div>
<div style="position: absolute; left: 1192px; top: 72px; width: 80px; font-size: 12px; line-height: 16px; color: #5F5E5A">accuracy</div>
<div style="position: absolute; left: 1416px; top: 270px; width: 56px; text-align: right; font-size: 12px; line-height: 16px; color: #5F5E5A">cost</div>
<div style="position: absolute; left: 1350px; top: 196px; width: 96px; text-align: center; font-size: 12px; line-height: 16px; color: #5F5E5A">fixed budget</div>
<div style="position: absolute; left: 1196px; top: 124px; width: 72px; text-align: right; font-size: 12px; line-height: 16px; font-weight: 600; color: #1C1C1A">efficient</div>
<div style="position: absolute; left: 1136px; top: 296px; width: 352px; text-align: center; font-size: 14px; line-height: 20px; color: #1C1C1A">Move up and to the left</div>
<div style="position: absolute; left: 304px; top: 344px; width: 248px; height: 56px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; text-align: center; font-size: 13px; line-height: 18px; color: #5F5E5A"><span><b style="font-size: 28px; line-height: 34px; color: #1F5F8B">Interaction</b><br>cost charged by the environment</span></div>
<div style="position: absolute; left: 672px; top: 344px; width: 376px; height: 56px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; text-align: center; font-size: 13px; line-height: 18px; color: #8A8378"><span><b style="font-size: 16px; line-height: 22px; color: #5F5E5A">Agent system</b><br>decides what to request and what to compute</span></div>
<div style="position: absolute; left: 1168px; top: 344px; width: 320px; height: 56px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; text-align: center; font-size: 13px; line-height: 18px; color: #5F5E5A"><span><b style="font-size: 28px; line-height: 34px; color: #9A4A07">Computation</b><br>cost charged by the infrastructure</span></div>
<div style="position: absolute; left: 80px; top: 440px; width: 192px; height: 272px; box-sizing: border-box; padding: 16px; display: flex; align-items: center; font-size: 13px; line-height: 18px; color: #8A8378"><span><b style="font-size: 48px; line-height: 56px; color: #1C1C1A">×1</b><br><b style="font-size: 20px; line-height: 28px; color: #1C1C1A">Learning</b><br>paid once</span></div>
<div style="position: absolute; left: 80px; top: 808px; width: 192px; height: 152px; box-sizing: border-box; padding: 16px; display: flex; align-items: center; font-size: 13px; line-height: 18px; color: #8A8378"><span><b style="font-size: 48px; line-height: 56px; color: #1C1C1A">×N</b><br><b style="font-size: 20px; line-height: 28px; color: #1C1C1A">Deployment</b><br>paid for every task</span></div>
<div style="position: absolute; left: 304px; top: 440px; width: 248px; height: 272px; box-sizing: border-box; padding: 16px; display: flex; flex-direction: column; align-items: center; justify-content: center; gap: 6px; text-align: center; background: #DCEAF4; border: 2px solid #1F5F8B; border-radius: 12px; font-size: 14px; line-height: 20px; color: #1F4E70"><svg aria-hidden="true" width="28" height="28" viewBox="0 0 24 24" fill="none" stroke="#1F5F8B" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="9"></circle><path d="M3 12h18"></path><path d="M12 3c2.8 2.6 4.2 5.6 4.2 9s-1.4 6.4-4.2 9c-2.8-2.6-4.2-5.6-4.2-9s1.4-6.4 4.2-9z"></path><path d="M5 7.5h14M5 16.5h14"></path></svg><span><b style="font-size: 19px; line-height: 26px; color: #164A6E">Interaction cost</b><br>rollout steps, rewards, verifier queries</span></div>
<div style="position: absolute; left: 672px; top: 440px; width: 376px; height: 272px; box-sizing: border-box; padding: 16px; display: flex; align-items: center; justify-content: center; text-align: center; background: #FFFFFF; border: 1px solid #DDDAD2; border-radius: 12px; font-size: 14px; line-height: 20px; color: #8A8378"><span><b style="font-size: 17px; line-height: 24px; color: #5F5E5A">Agent system, learning</b><br>harness + model</span></div>
<div style="position: absolute; left: 1168px; top: 440px; width: 320px; height: 64px; box-sizing: border-box; padding: 0 48px 0 16px; display: flex; align-items: center; background: #FAE3C8; border: 2px solid #B45309; border-radius: 12px; font-size: 13px; line-height: 18px; color: #7A3A05"><span><b style="font-size: 16px; line-height: 22px">Rollout inference</b><br>generating trajectories</span></div>
<div style="position: absolute; left: 1168px; top: 544px; width: 320px; height: 64px; box-sizing: border-box; padding: 0 48px 0 16px; display: flex; align-items: center; background: #FAE3C8; border: 2px solid #B45309; border-radius: 12px; font-size: 13px; line-height: 18px; color: #7A3A05"><span><b style="font-size: 16px; line-height: 22px">Experience</b><br>stored trajectories and rewards</span></div>
<div style="position: absolute; left: 1168px; top: 648px; width: 320px; height: 64px; box-sizing: border-box; padding: 0 48px 0 16px; display: flex; align-items: center; background: #B45309; border: 2px solid #7A3A05; border-radius: 12px; font-size: 13px; line-height: 18px; color: #FDEBDD"><span><b style="font-size: 19px; line-height: 24px; color: #FFFFFF">Internalize</b><br>weight updates, rewriting code and prompts</span></div>
<div style="position: absolute; left: 288px; top: 824px; width: 248px; height: 144px; box-sizing: border-box; background: #EEF4F9; border: 1.5px solid #9DBCD2; border-radius: 12px"></div>
<div style="position: absolute; left: 656px; top: 824px; width: 376px; height: 144px; box-sizing: border-box; background: #FFFFFF; border: 1px solid #E6E3DB; border-radius: 12px"></div>
<div style="position: absolute; left: 1152px; top: 824px; width: 320px; height: 144px; box-sizing: border-box; background: #FDF1E3; border: 1.5px solid #E2AD7A; border-radius: 12px"></div>
<div style="position: absolute; left: 296px; top: 816px; width: 248px; height: 144px; box-sizing: border-box; background: #E5EFF6; border: 1.5px solid #5F8FB2; border-radius: 12px"></div>
<div style="position: absolute; left: 664px; top: 816px; width: 376px; height: 144px; box-sizing: border-box; background: #FFFFFF; border: 1px solid #E0DDD5; border-radius: 12px"></div>
<div style="position: absolute; left: 1160px; top: 816px; width: 320px; height: 144px; box-sizing: border-box; background: #FBEAD6; border: 1.5px solid #CC8040; border-radius: 12px"></div>
<div style="position: absolute; left: 304px; top: 808px; width: 248px; height: 144px; box-sizing: border-box; padding: 16px; display: flex; flex-direction: column; align-items: center; justify-content: center; gap: 6px; text-align: center; background: #DCEAF4; border: 2px solid #1F5F8B; border-radius: 12px; font-size: 14px; line-height: 20px; color: #1F4E70"><svg aria-hidden="true" width="28" height="28" viewBox="0 0 24 24" fill="none" stroke="#1F5F8B" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="9"></circle><path d="M3 12h18"></path><path d="M12 3c2.8 2.6 4.2 5.6 4.2 9s-1.4 6.4-4.2 9c-2.8-2.6-4.2-5.6-4.2-9s1.4-6.4 4.2-9z"></path><path d="M5 7.5h14M5 16.5h14"></path></svg><span><b style="font-size: 19px; line-height: 26px; color: #164A6E">Interaction cost</b><br>observations, tool calls, document reads</span></div>
<div style="position: absolute; left: 672px; top: 808px; width: 376px; height: 144px; box-sizing: border-box; padding: 16px; display: flex; align-items: center; justify-content: center; text-align: center; background: #FFFFFF; border: 1px solid #DDDAD2; border-radius: 12px; font-size: 14px; line-height: 20px; color: #8A8378"><span><b style="font-size: 17px; line-height: 24px; color: #5F5E5A">Agent system, deployed</b><br>harness + model</span></div>
<div style="position: absolute; left: 1168px; top: 808px; width: 320px; height: 144px; box-sizing: border-box; padding: 16px; display: flex; flex-direction: column; align-items: center; justify-content: center; gap: 6px; text-align: center; background: #FAE3C8; border: 2px solid #B45309; border-radius: 12px; font-size: 14px; line-height: 20px; color: #7A3A05"><svg aria-hidden="true" width="28" height="28" viewBox="0 0 24 24" fill="none" stroke="#B45309" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="4" width="18" height="7" rx="1.5"></rect><rect x="3" y="13" width="18" height="7" rx="1.5"></rect><path d="M7 7.5h.01M7 16.5h.01"></path><path d="M11 7.5h6M11 16.5h6"></path></svg><span><b style="font-size: 19px; line-height: 26px; color: #7A3A05">Inference cost</b><br>generated tokens, context, KV cache</span></div>
<div style="position: absolute; left: 516px; top: 452px; width: 24px; height: 24px; border-radius: 12px; background: #1F5F8B; color: #FFFFFF; font-size: 14px; line-height: 24px; font-weight: 600; text-align: center">$</div>
<div style="position: absolute; left: 1452px; top: 460px; width: 24px; height: 24px; border-radius: 12px; background: #B45309; color: #FFFFFF; font-size: 14px; line-height: 24px; font-weight: 600; text-align: center">$</div>
<div style="position: absolute; left: 1452px; top: 564px; width: 24px; height: 24px; border-radius: 12px; background: #B45309; color: #FFFFFF; font-size: 14px; line-height: 24px; font-weight: 600; text-align: center">$</div>
<div style="position: absolute; left: 1452px; top: 668px; width: 24px; height: 24px; border-radius: 12px; background: #FFFFFF; color: #B45309; font-size: 14px; line-height: 24px; font-weight: 600; text-align: center">$</div>
<div style="position: absolute; left: 484px; top: 820px; width: 56px; height: 24px; border-radius: 12px; background: #1F5F8B; color: #FFFFFF; font-size: 13px; line-height: 24px; font-weight: 600; text-align: center">$ ×N</div>
<div style="position: absolute; left: 1420px; top: 820px; width: 56px; height: 24px; border-radius: 12px; background: #B45309; color: #FFFFFF; font-size: 13px; line-height: 24px; font-weight: 600; text-align: center">$ ×N</div>
<div style="position: absolute; left: 1060px; top: 652px; width: 96px; text-align: center; font-size: 13px; line-height: 16px; font-weight: 600; color: #7A3A05">update</div>
<div style="position: absolute; left: 876px; top: 752px; width: 220px; font-size: 13px; line-height: 16px; color: #8A8378">deploy the learned system</div>
<div style="position: absolute; left: 64px; top: 1008px; width: 1424px; height: 1px; background: #DDDAD2"></div>
<div style="position: absolute; left: 64px; top: 1024px; width: 1424px; font-size: 13px; line-height: 20px; color: #8A8378"><b style="font-size: 16px; color: #1C1C1A">Existing methods, placed where they cut cost</b>   rows and columns match the diagram above</div>
<div style="position: absolute; left: 80px; top: 1064px; width: 192px; font-size: 13px; line-height: 18px; color: #8A8378"><b style="font-size: 18px; line-height: 24px; color: #1C1C1A">×1</b>  Learning</div>
<div style="position: absolute; left: 80px; top: 1160px; width: 192px; font-size: 13px; line-height: 18px; color: #8A8378"><b style="font-size: 18px; line-height: 24px; color: #1C1C1A">×N</b>  Deployment</div>
<div style="position: absolute; left: 80px; top: 1256px; width: 192px; font-size: 13px; line-height: 18px; color: #8A8378"><b style="font-size: 15px; line-height: 24px; color: #1C1C1A">Shift cost</b><br>between cells</div>
<div style="position: absolute; left: 304px; top: 1064px; width: 248px; display: flex; flex-direction: column; align-items: flex-start; gap: 6px; font-size: 12px; line-height: 16px">
<span style="padding: 4px 10px; border-radius: 12px; background: #E8F0F7; color: #164A6E">sample-efficient RL</span>
<span style="padding: 4px 10px; border-radius: 12px; background: #E8F0F7; color: #164A6E">data selection and curricula</span>
<span style="padding: 4px 10px; border-radius: 12px; background: #E8F0F7; color: #164A6E">cheaper rewards: rules, small verifiers</span>
</div>
<div style="position: absolute; left: 672px; top: 1064px; width: 376px; display: flex; flex-direction: column; align-items: flex-start; gap: 6px; font-size: 12px; line-height: 16px">
<span style="padding: 4px 10px; border-radius: 12px; background: #EFEDE6; color: #3D3C38">better credit assignment</span>
<span style="padding: 4px 10px; border-radius: 12px; background: #EFEDE6; color: #3D3C38">off-policy and replay reuse</span>
<span style="padding: 4px 10px; border-radius: 12px; background: #EFEDE6; color: #3D3C38">early stopping and warm starts</span>
</div>
<div style="position: absolute; left: 1168px; top: 1064px; width: 320px; display: flex; flex-direction: column; align-items: flex-start; gap: 6px; font-size: 12px; line-height: 16px">
<span style="padding: 4px 10px; border-radius: 12px; background: #FBEFE2; color: #7A3A05">LoRA and parameter-efficient updates</span>
<span style="padding: 4px 10px; border-radius: 12px; background: #FBEFE2; color: #7A3A05">asynchronous rollout and training</span>
<span style="padding: 4px 10px; border-radius: 12px; background: #FBEFE2; color: #7A3A05">mixed precision, sequence packing</span>
</div>
<div style="position: absolute; left: 304px; top: 1160px; width: 248px; display: flex; flex-direction: column; align-items: flex-start; gap: 6px; font-size: 12px; line-height: 16px">
<span style="padding: 4px 10px; border-radius: 12px; background: #E8F0F7; color: #164A6E">adaptive retrieval</span>
<span style="padding: 4px 10px; border-radius: 12px; background: #E8F0F7; color: #164A6E">tool-call budgets</span>
<span style="padding: 4px 10px; border-radius: 12px; background: #E8F0F7; color: #164A6E">active perception, look on demand</span>
</div>
<div style="position: absolute; left: 672px; top: 1160px; width: 376px; display: flex; flex-direction: column; align-items: flex-start; gap: 6px; font-size: 12px; line-height: 16px">
<span style="padding: 4px 10px; border-radius: 12px; background: #EFEDE6; color: #3D3C38">context and memory management</span>
<span style="padding: 4px 10px; border-radius: 12px; background: #EFEDE6; color: #3D3C38">adaptive thinking budgets, early exit</span>
<span style="padding: 4px 10px; border-radius: 12px; background: #EFEDE6; color: #3D3C38">model routing and cascades</span>
</div>
<div style="position: absolute; left: 1168px; top: 1160px; width: 320px; display: flex; flex-direction: column; align-items: flex-start; gap: 6px; font-size: 12px; line-height: 16px">
<span style="padding: 4px 10px; border-radius: 12px; background: #FBEFE2; color: #7A3A05">quantization, pruning, distillation</span>
<span style="padding: 4px 10px; border-radius: 12px; background: #FBEFE2; color: #7A3A05">visual and text token compression</span>
<span style="padding: 4px 10px; border-radius: 12px; background: #FBEFE2; color: #7A3A05">KV-cache reuse, speculative decoding</span>
</div>
<div style="position: absolute; left: 304px; top: 1256px; width: 1184px; display: flex; flex-wrap: wrap; align-items: center; gap: 12px; font-size: 13px; line-height: 16px">
<span style="display: inline-flex; align-items: center; height: 28px; padding: 0 12px; border-radius: 14px; background: #B45309; color: #FFFFFF"><b>Internalize</b>  · per task → once: distilled behavior, skill libraries, self-evolving code</span>
<span style="display: inline-flex; align-items: center; height: 28px; padding: 0 12px; border-radius: 14px; background: #E8E6DF; color: #3D3C38"><b>Imagine</b>  · interaction → computation: world models, simulators</span>
<span style="display: inline-flex; align-items: center; height: 28px; padding: 0 12px; border-radius: 14px; background: #E8E6DF; color: #3D3C38"><b>Precompute</b>  · per task → once: indexes, caches, pre-built graphs</span>
</div>
</div>
</div>
</div>
<p class="jc-costfig-cap">Where an agent's cost comes from, and how to move it. <a href="/assets/html/cost-framework.html" target="_blank" rel="noopener">View full size</a></p>

<script>
  (function () {
    var wrap = document.getElementById("jc-costfig");
    if (!wrap) return;
    var inner = wrap.firstElementChild;
    function fit() {
      var s = Math.min(1, wrap.clientWidth / 1552);
      inner.style.transform = "scale(" + s + ")";
      wrap.style.height = Math.round(1336 * s) + "px";
    }
    fit();
    if (window.ResizeObserver) new ResizeObserver(fit).observe(wrap);
    else window.addEventListener("resize", fit);
  })();
</script>

<div class="jc-flow">
  <a class="jc-step" data-target="rf-eff" href="#rf-eff"><span class="jc-num">01</span><strong>Efficient LLM Agents</strong><small>from SI to RSI</small></a>
  <span class="jc-flow-arrow" aria-hidden="true">→</span>
  <a class="jc-step" data-target="rf-cu" href="#rf-cu"><span class="jc-num">02</span><strong>Computer Use</strong><small>GUI · CLI</small></a>
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
          <li><a href="/publications/#chen2026warmup">Warm Up with a Rubric, Then Merge: Decoupling Grounding Gains from Reasoning Costs in Vision-Language Models</a> <span class="jc-venue">(EMNLP 2026)</span></li>
          <li><a href="/publications/#chen2026foveaui">FoveaUI: Foveated On-demand Visual Evidence Acquisition for GUI Grounding</a> <span class="jc-venue">(ACM MM 2026)</span></li>
          <li class="jc-ongoing">Ongoing work on recursive self-improvement for agents.</li>
        </ul>
      </div>
    </details>
    <details class="jc-card" id="rf-cu">
      <summary><span>Computer Use <small>— GUI · CLI</small></span></summary>
      <div class="jc-body">
        <h4>Research Questions</h4>
        <ul>
          <li><strong>How</strong> can agents ground instructions and act reliably on real software, through graphical interfaces and the command line?</li>
          <li><strong>How</strong> can GUI data and action spaces scale across platforms without human labels?</li>
        </ul>
        <h4>Representative Works</h4>
        <ul>
          <li><a href="https://arxiv.org/abs/2509.17328" target="_blank" rel="noopener">UIPro: Unleashing Superior Interaction Capability For GUI Agents</a> <span class="jc-venue">(ICCV 2025)</span></li>
          <li><a href="https://aclanthology.org/2025.acl-long.510" target="_blank" rel="noopener">AutoGUI: Scaling GUI Grounding with Automatic Functionality Annotations from LLMs</a> <span class="jc-venue">(ACL 2025)</span></li>
          <li><a href="/publications/#chen2026foveaui">FoveaUI: Foveated On-demand Visual Evidence Acquisition for GUI Grounding</a> <span class="jc-venue">(ACM MM 2026)</span></li>
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
          <li><a href="https://x.com/XGEN_labs/article/2103137462008844442" target="_blank" rel="noopener">Dual Exam: Controlled Evaluation of Multimodal Agents and World Models</a> <span class="jc-venue">(XGEN Labs Tech Report 2026, as core contributor)</span></li>
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

My earlier work focused on **information retrieval**.

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
