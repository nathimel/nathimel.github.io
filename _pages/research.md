---
layout: archive
title: ""
permalink: /research/
author_profile: true
---


Peer-reviewed publications
======

<ul>{% for post in site.publications %}
{% include archive-single-cv.html %}
{% endfor %}</ul>
  

Works in progress
======

<ul>{% for post in site.wips reversed %}
    {% include archive-single-cv.html %}
{% endfor %}</ul>

<!-- idea: list the badge types in an html, then include them somehow, and maybe specify just the pair of urls somehow? not clear to me how to do this. Maybe the thing to do is straight up list every publication in a plain html file. you can still link the posts using the urls probably. -->
