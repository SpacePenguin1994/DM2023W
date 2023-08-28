---
layout: home
title: Home
nav_exclude: true
seo:
  type: Course
  name: Discrete Mathematics, SHNU
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

<!-- {% if site.announcements %}
{{ site.announcements.last }}
[Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %} -->

## About the Class

To be continued.

See the [Syllabus page](syllabus.md) for more details on course policies.

## General Information

**Instructor:** [Qizhe Yang](https://basics.sjtu.edu.cn/~yangqizhe/), qzyang(at)shnu.edu.cn

**Time and Location:** &ensp;&nbsp;8:00 a.m.- 9:30 a.m. &nbsp;Every Monday in Week 1-16, 奉贤3教楼309
 <br/>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp;8:00 a.m.- 9:30 a.m. &emsp;Every Friday in Week 1-16，奉贤3教楼312

 For more details about the class, see the [Schedule page](schedule.md).


# Announcements

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}