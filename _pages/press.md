---
layout: archive
title: "Press"
permalink: /press/
author_profile: true
---
### Video 1: NASA News Story

<iframe width="560" height="315" src="https://www.youtube.com/embed/UbX1JVADu-8" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Description:  
Local San Francisco news story about solar flares.

---

### Video 2: Science Outreach Interview

<iframe width="560" height="315" src="https://www.youtube.com/embed/M3Lrjj7djyU" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Description:  
Student spotlight interview regarding my research an life as a student.

{% include base_path %}

{% for post in site.press %}
  {% include archive-single.html %}
{% endfor %}
