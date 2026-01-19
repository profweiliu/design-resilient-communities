---
layout: minimal
title: Environmental Design Capstone
nav_exclude: True
permalink: /:path/
seo:
  type: Course
  name: Just the Class
search_enabled: true
---

{% include course_header.html %}


Course Description

--- 

{% assign latest = site.announcements | sort: "date" | last %}

<div class="announcement">
  <div class="announcement-left">
    <p>{{ latest.date | date: "%B %d, %Y" }}</p>
    <p class="all-announcements">
      <a href="{{site.baseurl}}/announcements/">All announcements →</a>
    </p>
  </div>
  <div class="announcement-right announcement-body">
    <div style="text-transform: uppercase; font-weight: 600;"> {{ latest.title }} </div>
    {{ latest.content | markdownify }}
  </div>
</div>

--- 

## Schedules
<a href="#recent"><i class="fa-solid fa-square-arrow-up-right" style="color: #000000;"></i> **Go to the recent section**.</a> This schedule is subject to change, and please check back regularly for updates. All readings and materials can be directly accessed via the links below, although some may require a OU NetID login. Please give us any anonymous suggestions about the lectures, discussion, design progress, or anything using the **[anonymous suggestions box](https://freesuggestionbox.com/pub/uzxbkym)**.

{% for module in site.modules %}
{{ module }}
{% endfor %}

{% include course_footer.html %}

