---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

**Fields:** Natural Language Processing, Computational Linguistics, Deep Learning

**Topics**: Question Answering, Natural Language Understanding, Natural Language Generation

**Publications**:

1. **Ngo Quang Huy**, Tu Minh Phuong, Ngo Xuan Bach. Autoencoding Language Model Based Ensemble Learning for Commonsense Validation and Explanation.  