---
permalink: /
title: "Jiajun Yu - 余佳骏"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
Hi! I am currently pursuing a master's degree in the [FastLab](http://zju-fast.com/) (Fire Group) at the College of Control Science and Engineering, Zhejiang University, under the guidance of [Yanjun Cao](http://zju-fast.com/research-group/yanjun-cao/) and [Chao Xu](http://zju-fast.com/research-group/chao-xu/).
Currently, I’m preparing to apply for PhD research program. If you're interested in discussing my work or potential collaborations, feel free to email me at jjyu@zju.edu.cn.

Research Interests
------
My current focus is on utilizing deep reinforcement learning to enhance traditional optimization methods.
- Motion Planning
- Parallel Trajectory Optimization  
- Deep Reinforcement Learning

Publications
------
{% for post in site.publications reversed %}
  {% include archive-single.html type="grid" %}
{% endfor %}

