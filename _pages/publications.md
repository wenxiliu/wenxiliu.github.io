---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


* Feigege Wang, Yue Gu, **Wenxi Liu***, Yuanlong Yu, Shengfeng He, Jia Pan: Context-aware Spatio-recurrent Curvilinear Structure Segmentation. CVPR 2019

* Qiang Wen, Yinjie Tan, Jing Qin, **Wenxi Liu**, Guoqiang Han, Shengfeng He: Single Image Reflection Removal Beyond Linearity. CVPR 2019
