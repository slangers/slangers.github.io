---
layout: page
title: Design & Illustration
permalink: /illustration/
images:
  - image_path: /images/1.png
    title: Honi Soit cover
  - image_path: /images/1.png
    title: Honi Soit cover
  - image_path: /images/1.png
    title: Honi Soit cover
  - image_path: /images/1.png
    title: Honi Soit cover
---

# Design & Illustration


<ul class="folio">
  {% for image in page.images %}
    <li class="folio_item"><img src="{{ image.image_path }}" alt="{{ image.title}}"/></li>
  {% endfor %}
</ul>
