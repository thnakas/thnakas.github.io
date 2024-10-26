---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

<div align="justify">

  <h2> <u>Classical Mechanics I (33)</u> </h2>
  
  Academic years: <i class="fa fa-fw fa-calendar"></i> 2018-2019, <i class="fa fa-fw fa-calendar"></i> 2019-2020, <i class="fa fa-fw fa-calendar"></i> 2020-2021
  
  <ul>
    <li> <a href="https://physics.uoi.gr/en/"> <span style="color: skyblue"> University of Ioannina, Greece </span> 
    </a> </li>
    <li> Core undergraduate course </li>
    <li> Taught jointly with Prof. Panagiota Kanti for three consecutive years </li>
  </ul>
</div>


{% include base_path %}

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}