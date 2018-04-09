---
layout: page
permalink: /research/
title: Research
pubs:

    - title:   "To be continued"
      author:  "P. Wu, J. Liu"
      journal: "Transactions on XXX"
      note:    "(presented at Oz)"
      year:    "201x"
      url:     "http://publish-more-stuff.org"
      doi:     "http://dx.doi.org"
      image:   "https://images.duckduckgo.com/iu/?u=http%3A%2F%2Fimages.moviepostershop.com%2Fthe-matrix-movie-poster-1999-1020518087.jpg&f=1"
      media:
        - name: "IMDB"
          url:  "http://www.imdb.com/title/tt0133093/"

pros:

    - title:   "To be continued"
      author:  "P. Wu, J. Liu"
      note:    "presented at Oz"
      year:    "2017"
      url:     "http://publish-more-stuff.org"
      image:   "https://i.loli.net/2018/04/09/5acac4de8f0fc.bmp"
      media:
        - name: "IMDB"
          url:  "http://www.imdb.com/title/tt0133093/"



---

## Publications (peer reviewed)

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

