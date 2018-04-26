---
layout: page
title: Blog
permalink: /blog/
---

Please click [CSDN](https://blog.csdn.net/windows_peng)

**News!**

2018-04-10 new blog is released[看DCGAN源代码 记录遇到的好玩的事情](https://blog.csdn.net/windows_peng/article/details/79871948)

2018-04-12 new blog is released[Future Frame Prediction for Anomaly Detection 代码学习](https://blog.csdn.net/windows_peng/article/details/79905075)

2018-04-26  About PCA (Principal Component Analysis), I highly recommend this [Ufldl(Chinese)](http://ufldl.stanford.edu/wiki/index.php/%E4%B8%BB%E6%88%90%E5%88%86%E5%88%86%E6%9E%90) &[Ufldl](http://ufldl.stanford.edu/wiki/index.php/PCA)



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
