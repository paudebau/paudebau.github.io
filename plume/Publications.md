---
title: Publications - Publications
ubject: Une vue sur l'ensemble des publications connues de Hal.
suthor: Plume Webmaster
timestamp: 2012-02-12 07:21:38 +0200
embedded: true
tags: 
---

## Publications

<p>Information available as <img src="img/feed-14x14.png" /> {{ "RSS feed" | links_to "http://hal.archives-ouvertes.fr/rss.php?tampon=LIP_PLUME" | safe }}</p>

<p></p>
{% load_hal publications %}
<div>
{% for item in publications %}
<h3>{{ item.title | links_to item.link | safe }}</h3>
 <div>{{ item.description | safe }}</div>
    {% endfor %}
</div>

[RSS feed]: http://feed2js.org//feed2js.php?src=http%3A%2F%2Fhal.archives-ouvertes.fr%2Frss.php%3Ftampon%3DLIP_PLUME&chan=title&num=0&desc=1&date=y&targ=y&html=y

