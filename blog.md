---
layout: page
title: Blog
permalink: /blog/
---

Please click [CSDN](https://blog.csdn.net/windows_peng)

**News!**

2018-04-10 new blog is released[看DCGAN源代码 记录遇到的好玩的事情](https://blog.csdn.net/windows_peng/article/details/79871948)

2018-04-12 new blog is released[Future Frame Prediction for Anomaly Detection 代码学习](https://blog.csdn.net/windows_peng/article/details/79905075)

<ul class="listing">
{% for post in site.posts %}
  {% capture y %}{{post.date | date:"%Y"}}{% endcapture %}
  {% if year != y %}
    {% assign year = y %}
    <li class="listing-seperator">{{ y }}</li>
  {% endif %}
  <li class="listing-item">
    <time datetime="{{ post.date | date:"%Y-%m-%d" }}">{{ post.date | date:"%Y-%m-%d" }}</time>
    <a href="{{ post.url | prepend: site.baseurl }}" title="{{ post.title }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>
