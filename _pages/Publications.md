---
layout: archive
title: "Publications"
permalink: /Publications/
author_profile: true
---

{% include base_path %}


## Book Chapters

{% for pub in site.data.publications.books %}
<p>[B{{ forloop.index }}] {{ pub.text | markdownify | remove: '<p>' | remove: '</p>' }}</p>
{% if pub.extra_html %}
{{ pub.extra_html }}
{% endif %}
{% endfor %}

---

## Journal Articles

{% for pub in site.data.publications.journals %}
<p>[J{{ forloop.index }}] {{ pub.text | markdownify | remove: '<p>' | remove: '</p>' }}</p>
{% endfor %}

---

## Conference Papers

{% for pub in site.data.publications.conferences %}
<p>[C{{ forloop.index }}] {{ pub.text | markdownify | remove: '<p>' | remove: '</p>' }}</p>
{% endfor %}

---

## Theses

{% for pub in site.data.publications.theses %}
<p>[T{{ forloop.index }}] {{ pub.text | markdownify | remove: '<p>' | remove: '</p>' }}</p>
{% endfor %}
