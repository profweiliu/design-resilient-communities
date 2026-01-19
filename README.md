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

Communities today face an array of interconnected challenges, including climate change, social inequity, economic uncertainty, and environmental stress. In this context, resilience, the capacity of a community to adapt, recover, and thrive in the face of natural or human-made disruptions, has become a critical framework for contemporary environmental design practice. Designing Resilient Communities introduces students to theories, principles, and strategies of community resilience, with a particular emphasis on public space as a form of critical social, environmental, and civic infrastructure.

The course combines lectures, discussions, and labs with applied, experiential learning. Students will engage in a time-intensive design charrette with professional design experts and community partners, develop hands-on responses to a real-world challenge in a local context, and deliver student-led presentations based on resilient cities reports to build comparative and international perspectives.

Offered in partnership with the [Institute for Quality Communities (IQC)](https://iqc.ou.edu), the course centers on a real community-based project in the City of Durant, Oklahoma. By the end of the semester, students will synthesize research, community engagement, and design thinking to produce actionable design recommendations that support long-term social, environmental, and spatial resilience for the community.

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

