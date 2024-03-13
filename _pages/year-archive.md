---
title: "MLIS Student Learning Goals and Outcomes"
permalink: /posts/
layout: posts
author_profile: false
---




{% for goal in goals %}
- {{ goal }}
{% endfor %}



{% for outcome in outcomes %}
- {{ outcome }}
{% endfor %}

<!-- Text that appears after dynamically generated content -->
Testing