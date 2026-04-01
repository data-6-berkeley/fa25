---
layout: page
title: "&#x1F4C5; Calendar"
description: Class schedule.
nav_order: 2
---

{: .warning }
⚠️ This content is archived as of March 2026 and is retained exclusively for reference. [Find current offerings.](https://data6.org/)

# Weekly Calendar

{% for calendar in site.calendars %}
  {{ calendar }}
{% endfor %}
