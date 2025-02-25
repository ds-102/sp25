---
layout: page
title: Home
nav_order: 1
description: A week-to-week description of the content covered in the course.
---

# Data 102: Data, Inference, and Decisions

## UC Berkeley, Spring 2025 
{: .mb-2 .fs-6 .text-grey-dk-000 style="margin-top: 0;"  }

<div>
{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
  <div class="role">
    {% for staffer in instructors %}
    {{ staffer }}
    {% endfor %}
  </div>
</div>

{% assign announcement = site.announcements | where: 'week', site.current_week %}
{{ announcement }}


## Schedule
[**Jump to current week**](#week-{{ site.current_week }}){: .btn }

{% for module in site.modules %}
{{ module }}
{% endfor %}