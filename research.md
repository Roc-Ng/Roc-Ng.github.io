---
layout: page
permalink: /research/
title: Research
pubs:
    - title:   "Bidirectional Retrospective Generation Adversarial Network for Anomaly Detection in Videos"
      author:  "Zhiwei Yang, Jing Liu, **Peng Wu**"
      conference: "IEEE Access"
      note:    "(presented at Oz)"
      year:    "2021"
      url:     "https://ieeexplore.ieee.org/abstract/document/9499069/"
      doi:     "http://dx.doi.org"
      image:   "https://images.duckduckgo.com/iu/?u=http%3A%2F%2Fimages.moviepostershop.com%2Fthe-matrix-movie-poster-1999-1020518087.jpg&f=1"
    
    - title:   "HANet: Hierarchical Alignment Networks for Video-Text Retrieval"
      author:  "**Peng Wu**, Xiangteng He, Mingqian Tang, Yiliang Lv, Jing Liu"
      conference: "ACM Multimedia conference (ACM-MM)"
      note:    "(presented at Oz)"
      year:    "2021 [CCF-A]"
      url:     "https://arxiv.org/abs/2107.12059"
      doi:     "http://dx.doi.org"
      image:   "https://images.duckduckgo.com/iu/?u=http%3A%2F%2Fimages.moviepostershop.com%2Fthe-matrix-movie-poster-1999-1020518087.jpg&f=1"
      
    - title:   "Learning Causal Temporal Relation and Feature Discrimination for Anomaly Detection"
      author:  "**Peng Wu**, Jing Liu"
      conference: "IEEE Transactions on Image Processing (TIP)"
      note:    "(presented at Oz)"
      year:    "2021 [CCF-A, IF:9.34]"
      url:     "https://doi.org/10.1109/TIP.2021.3062192"
      doi:     "http://dx.doi.org"
      image:   "https://images.duckduckgo.com/iu/?u=http%3A%2F%2Fimages.moviepostershop.com%2Fthe-matrix-movie-poster-1999-1020518087.jpg&f=1"

    - title:   "Not only Look, but also Listen: Learning Multimodal Violence Detection under Weak Supervision"
      author:  "**Peng Wu**, Jing Liu, Yujia Shi, Yujia Sun, Fangtao Shao, Zhaoyang Wu, Zhi Wei Yang"
      conference: "European Conference on Computer Vision (ECCV)"
      note:    "(presented at Oz)"
      year:    "2020 [Top Conference]"
      url:     "https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123750324.pdf"
      doi:     "http://dx.doi.org"
      image:   "https://images.duckduckgo.com/iu/?u=http%3A%2F%2Fimages.moviepostershop.com%2Fthe-matrix-movie-poster-1999-1020518087.jpg&f=1"
     
    - title:   "Fast Sparse Coding Networks for Anomaly Detection in Videos"
      author:  "**Peng Wu**, Jing Liu, Mingming Li, Yujia Sun, Fang Shen"
      conference: "Pattern Recognition (PR)"
      note:    "(presented at Oz)"
      year:    "2020 [IF:7.196]"
      url:     "https://www.sciencedirect.com/science/article/abs/pii/S0031320320303186"
      doi:     "http://dx.doi.org"
      image:   "https://images.duckduckgo.com/iu/?u=http%3A%2F%2Fimages.moviepostershop.com%2Fthe-matrix-movie-poster-1999-1020518087.jpg&f=1"

    - title:   "A Deep One-Class Neural Network for Anomalous Event Detection in Complex Scenes"
      author:  "**Peng Wu**, Jing Liu, Fang Shen"
      conference: "IEEE Transactions on Neural Networks and Learning Systems (TNNLS)"
      note:    "(presented at Oz)"
      year:    "2019 [IF:11.683]"
      url:     "https://ieeexplore.ieee.org/abstract/document/8825555/"
      doi:     "http://dx.doi.org"
      image:   "https://images.duckduckgo.com/iu/?u=http%3A%2F%2Fimages.moviepostershop.com%2Fthe-matrix-movie-poster-1999-1020518087.jpg&f=1"

    - title:   "Double complete D-LBP with extreme learning machine auto-encoder and cascade forest for facial expression analysis"
      author:  "Fang Shen, Jing Liu, **Peng Wu**"
      conference: "IEEE International Conference on Image Processing (ICIP)"
      note:    "(presented at Oz)"
      year:    "2018"
      url:     "https://2018.ieeeicip.org/Papers/ViewPapers_MS.asp?PaperNum=1984"
      doi:     "http://dx.doi.org"
      image:   "https://images.duckduckgo.com/iu/?u=http%3A%2F%2Fimages.moviepostershop.com%2Fthe-matrix-movie-poster-1999-1020518087.jpg&f=1"

    - title:   "Hyperspectral Unmixing via Deep Convolutional Neural Networks"
      author:  "Xiangrong Zhang, Yujia Sun, Jingyan Zhang, **Peng Wu**, Licheng Jiao"
      conference: "IEEE Transcations on Geoscience and Remote Sensing Letters (TGRSL)"
      note:    "(presented at Oz)"
      year:    "2018 [IF:3.534]"
      url:     "https://ieeexplore.ieee.org/document/8432512"
      doi:     "http://dx.doi.org"
      image:   "https://images.duckduckgo.com/iu/?u=http%3A%2F%2Fimages.moviepostershop.com%2Fthe-matrix-movie-poster-1999-1020518087.jpg&f=1"

pros:

    - title:   "行人密度估计系统"
      author:  "**Peng Wu**, Jing Liu"
      note:    "适用于人流量大的公共场所"
      year:    "【2017】"
      url:     "http://publish-more-stuff.org"
      image:   "https://i.loli.net/2018/04/09/5acb04297f1e5.bmp"
      media:
        - name: "Demo"
          url:  "https://i.loli.net/2018/04/09/5acb04297f1e5.bmp"

    - title:   "车辆检测和计数系统"
      author:  "**Peng Wu**, Qiansheng Yang, Jiahao Liu, Jing Liu"
      note:    "上线于市政部门"
      year:    "【2018】"
      url:     "http://publish-more-stuff.org"
      image:   ""
      media:
        - name: "Demo"
          url:  ""

---

## Publications


  {% assign thumbnail="left" %}

  {% for pub in page.pubs %}

  [**{{pub.title}}**]({% if pub.internal %}{{pub.url | prepend: site.baseurl}}{% else %}{{pub.url}}{% endif %})<br />
  {{pub.author}}<br />
  *{{pub.conference}}*
   *{{pub.year}}* 
  {% if pub.link %}<br />Link: {% for article in pub.link %}[[{{article.name}}]({{article.url}})]{% endfor %}{% endif %}

  {% endfor %}

  

---

## Projects

{% assign thumbnail="left" %}

{% for pro in page.pros %}
{% if pro.image %}
{% include image.html url=pro.image caption="" height="100px" align=thumbnail %}
{% endif %}
[**{{pro.title}}**]({% if pub.internal %}{{pub.url | prepend: site.baseurl}}{% else %}{{pub.url}}{% endif %})<br />
{{pro.author}}<br />
*{{pro.note}}*
 *{{pro.year}}* 
{% if pro.media %}<br />Media: {% for article in pro.media %}[[{{article.name}}]({{article.url}})]{% endfor %}{% endif %}

{% endfor %}

