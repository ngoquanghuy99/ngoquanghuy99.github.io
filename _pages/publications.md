---
layout: archive
title: "Research"
permalink: /research/
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

**Topics**: Knowledge Reasoning, Language Modeling, Phonetics

**Publications**:

1. **Ngo Quang Huy**, Tu Minh Phuong and Ngo Xuan Bach. **2021**. Autoencoding Language Model Based Ensemble Learning for Commonsense Validation and Explanation. [paper](https://arxiv.org/abs/2204.03324)
2. **Ngo Quang Huy**, Nguyen Duc Manh Tuan, Nguyen Anh Duong and Pham Quang Nhat Minh. **2021**. AimeLaw at ALQAC 2021: Enriching Neural Network Models with Legal-Domain Knowledge. In *Proceedings of the 13th IEEE International Conference on Knowledge and Systems Engineering* (KSE). [paper](https://ieeexplore.ieee.org/document/9648636/)
3. Nguyen Nguyen Xuan Vu, **Ngo Quang Huy**, and Pham Quang Nhat Minh. **2023**. Automatic Transcript Generation from Presentation Slides. In *Proceedings of the 37th Pacific Asia Conference on Language, Information and Computation* (PACLIC), pages 670-678, Hong Kong, China. [paper](https://aclanthology.org/2023.paclic-1.67/)
