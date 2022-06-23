---
layout: page
title: Blog
permalink: /blog/
---

Please click [CSDN](https://blog.csdn.net/windows_peng)

**News!**
2022-06-22 [国奖人物](https://news.xidian.edu.cn/info/2106/221061.htm)

2018-04-10 new blog is released [看DCGAN源代码 记录遇到的好玩的事情](https://blog.csdn.net/windows_peng/article/details/79871948)

2018-04-12 new blog is released [Future Frame Prediction for Anomaly Detection 代码学习](https://blog.csdn.net/windows_peng/article/details/79905075)

2018-04-26  About PCA (Principal Component Analysis), I highly recommend this [Ufldl(Chinese)](http://ufldl.stanford.edu/wiki/index.php/%E4%B8%BB%E6%88%90%E5%88%86%E5%88%86%E6%9E%90) &[Ufldl](http://ufldl.stanford.edu/wiki/index.php/PCA)

2018-04-27  I implement PCA (Principal Component Analysis) using python [code](https://blog.csdn.net/windows_peng/article/details/80099666)

2018-05-02  new blog is released [YOLOv1 YOLOv2 个人解读和部分代码注释 ](https://blog.csdn.net/windows_peng/article/details/80168327)

2018-06-02 New blog [GPU版本光流算法](https://blog.csdn.net/windows_peng/article/details/80568114#commentsedit)

2018-07-30 New blog [Pyinstaller 打包遇到的一系列问题的解决方案](https://mp.csdn.net/mdeditor/81285658#)

2018-09-10 [pytorch 之坑持续更新](https://mp.csdn.net/postedit/82596459)

2018-10-25 [Tensorflow Data API](https://mp.csdn.net/postedit/83376618)

2018-11-05 [【Temporal Segment Networks】 pytorch代码总结](https://mp.csdn.net/postedit/83751283)

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
