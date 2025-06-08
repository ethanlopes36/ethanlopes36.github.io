---
layout: archive
title: "Press"
permalink: /press/
author_profile: true
---
### Video 1: Student Spotlight

<iframe width="560" height="315" src="https://www.youtube.com/embed/UbX1JVADu-8" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Student spotlight interview regarding my research and life as a student.


---

### Video 2: Sci Comm Interview

<iframe width="560" height="315" src="https://www.youtube.com/embed/M3Lrjj7djyU" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Local Bay Area news story about solar flares.

{% include base_path %}

{% for post in site.press %}
  {% include archive-single.html %}
{% endfor %}
