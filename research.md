---
layout: page
permalink: /research/
title: Research
pubs:

    - title:   "'Double complete D-LBP with extreme learning machine auto-encoder and cascade forest for facial expression analysis"
      author:  "F. Sheng, J. Liu and P. Wu"
      conference: "ICIP"
      note:    "(presented at Oz)"
      year:    "2018"
      url:     "http://publish-more-stuff.org"
      doi:     "http://dx.doi.org"
      image:   "https://images.duckduckgo.com/iu/?u=http%3A%2F%2Fimages.moviepostershop.com%2Fthe-matrix-movie-poster-1999-1020518087.jpg&f=1"
      media:
        - name: "IMDB"
          url:  "http://www.imdb.com/title/tt0133093/"

pros:

    - title:   "行人密度估计系统"
      author:  "P. Wu, J. Liu"
      note:    "适用于人流量大的公共场所"
      year:    "【2017】"
      url:     "http://publish-more-stuff.org"
      image:   "https://i.loli.net/2018/04/09/5acb04297f1e5.bmp"
      media:
        - name: "Demo"
          url:  "https://i.loli.net/2018/04/09/5acb04297f1e5.bmp"

    - title:   "车辆检测和计数系统"
      author:  "P. Wu, Q. S. Qian, F. Shen, J. Liu"
      note:    "适用于交通部门"
      year:    "【2018】"
      url:     "http://publish-more-stuff.org"
      image:   ""
      media:
        - name: "Demo"
          url:  ""



---

## Publications (peer reviewed)

- #### 2 papers [*under review*]

  


{% assign thumbnail="left" %}

{% for pub in page.pubs %}
{% if pub.image %}
{% include image.html url=pub.image caption="" height="100px" align=thumbnail %}
{% endif %}
[**{{pub.title}}**]({% if pub.internal %}{{pub.url | prepend: site.baseurl}}{% else %}{{pub.url}}{% endif %})<br />
{{pub.author}}<br />
*{{pub.journal}}*
{% if pub.note %} *({{pub.note}})*
{% endif %} *{{pub.year}}* {% if pub.doi %}[[doi]({{pub.doi}})]{% endif %}
{% if pub.media %}<br />Media: {% for article in pub.media %}[[{{article.name}}]({{article.url}})]{% endfor %}{% endif %}

{% endfor %}

---

## Projects(practiced)

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

