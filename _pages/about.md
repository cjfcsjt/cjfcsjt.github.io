---
layout: about
title: about
permalink: /
subtitle: Ph.D. Student · Department of Computing, <a href='https://www.polyu.edu.hk/comp/'>The Hong Kong Polytechnic University</a>

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>Hong Kong SAR, China</p>
    <p>jingfan.chen [at] connect.polyu.hk</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 6 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
---

I am a Ph.D. student in the [Department of Computing](https://www.polyu.edu.hk/comp/) at The Hong Kong Polytechnic University (PolyU),
advised by [Prof. Qing Li](https://www4.comp.polyu.edu.hk/~csqli/) (PolyU), [Prof. Zhen Lei](http://www.cbsr.ia.ac.cn/users/zlei/) (CASIA)
and [Dr. Wenqi Fan](https://wenqifan03.github.io). Before PolyU, I received my M.S. from Nanjing University and my B.S. from Shandong University.

My research goal is to build **computer-use agents that keep getting better on their own, at a cost people can afford**. I currently work on:

- **Computer-Use Agents.** Agents that read screens and operate real software through GUIs. I have worked on scaling GUI grounding with
  automatically annotated functionality data ([AutoGUI](https://autogui-project.github.io/), ACL 2025) and on generalist GUI agents with a
  unified cross-platform action space ([UIPro](https://arxiv.org/abs/2509.17328), ICCV 2025).
- **World Models for Agents.** Learning how digital environments respond to actions, so an agent can predict the next screen, plan with
  imagined rollouts, and practice without touching the real environment.
- **Recursive Self-Improvement (RSI).** Agents that propose their own tasks, generate and verify their own training signal, and use it to
  improve the next version of themselves, with checks that keep the loop from drifting.
- **Agentic Efficiency.** Making agents cheaper and faster per task: fewer steps, tokens and model calls, lower latency, and smarter
  allocation of test-time compute.

These threads fit together: a world model gives an agent a cheap place to practice, self-improvement turns that practice into a better
policy, and efficiency decides whether the result is usable in practice.

Earlier in my Ph.D. and during my master's, I worked on recommender systems, graph neural networks, trustworthy AI and Bayesian
optimization, with papers at KDD, SIGIR, CIKM and WWW.
