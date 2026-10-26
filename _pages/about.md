---
layout: about
title: About
permalink: /
subtitle: Tsinghua University · Beijing · China

profile:
  align: right
  images:
    - lab_photo/lab_photo_0.jpg
    - lab_photo/lab_photo_1.jpg
    - lab_photo/lab_photo_91.jpg
    - lab_photo/lab_photo_92.jpg
    - lab_photo/lab_photo_93.jpg
    - lab_photo/lab_photo_94.jpg
  image_circular: false

selected_papers: true
social: false

announcements:
  enabled: true
  scrollable: true
  limit: 7

latest_posts:
  enabled: false
  scrollable: true
  limit: 3
---


<div class="section-title">
OUR RESEARCH AREAS
</div>

{% include research_cards.liquid %}


<div class="bottom-grid">

  {% if page.announcements and page.announcements.enabled %}

  <div class="home-news-column">

    <h2>
      <a href="{{ '/news/' | relative_url }}" style="color: inherit; text-decoration: none;">
        Latest News
      </a>
    </h2>

    {% include news.liquid limit=true %}

  </div>

  {% endif %}


  {% if page.selected_papers %}

  <div class="home-papers-column">

    <h2>
      <a href="{{ '/publications/' | relative_url }}" style="color: inherit; text-decoration: none;">
        Recent Papers
      </a>
    </h2>

    {% include selected_papers.liquid %}

  </div>

  {% endif %}

</div>
