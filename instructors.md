---
layout: page
title: Instructors
description: A listing of all the course staff members.
---

# Instructors

Instructor information is stored in the `_instructors` directory and rendered according to the layout file, `_layouts/instructors.html`.

## Instructors

{% assign instructors = site.instructors | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign teaching_assistants = site.instructors | where: 'role', 'Teaching Assistant' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}
## Teaching Assistants

{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}
