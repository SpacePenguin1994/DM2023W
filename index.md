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

Discrete Mathematics is the mathematical foundation of computer science. Within this course, students will acquire a specific collection of mathematical principles and learn how to apply them. Significantly, the course will cultivate logical and mathematical thinking abilities among students. To accomplish these objectives, the course will cover the following topics: Logic, Set Theory, Algebraic Structures, Combinatorics, Graph Theory, and Elementary Number Theory. 
Upon completing this course, students will have obtained a solid grasp of all the requisite mathematical foundations necessary for their future studies in computer science.

Enjoy the class!

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