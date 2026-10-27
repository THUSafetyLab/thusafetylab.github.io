---
layout: page
permalink: /teaching/
title: Courses
description: Course materials, schedules, and resources for classes taught.
nav: true
nav_order: 3
calendar: true
---

<style>
/* Teaching page: course list */

.teaching-custom {
  width: 100%;
  margin: 0 auto;
}

.teaching-custom .teaching-year {
  margin: 24px 0 26px;
  padding-bottom: 10px;
  border-bottom: 1px solid var(--global-divider-color, #ddd);
  font-size: 1.65rem;
  font-weight: 650;
  color: var(--global-text-color, #222);
}

.teaching-custom .course-item {
  margin-bottom: 30px;
  padding-bottom: 26px;
  border-bottom: 1px solid var(--global-divider-color, #e5e5e5);
}

.teaching-custom .course-item:last-child {
  border-bottom: none;
}

.teaching-custom .course-title {
  margin: 0 0 10px;
  font-size: 1.22rem;
  font-weight: 650;
  line-height: 1.4;
}

.teaching-custom .course-title a {
  color: var(--global-text-color, #222);
  text-decoration: none;
}

.teaching-custom .course-title a:hover {
  color: #5c2983;
}

/* Purple outlined tags */

.teaching-custom .course-tags {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  gap: 8px;
  margin: 8px 0 12px;
}

.teaching-custom .course-tag {
  display: inline-block;
  padding: 5px 14px;
  border: 1px solid #ded1ed;
  border-radius: 999px;
  background: transparent;
  color: #4f2275;
  font-size: 0.82rem;
  font-weight: 600;
  line-height: 1.5;
  white-space: nowrap;
}

/* Semester and instructor */

.teaching-custom .course-meta {
  margin: 0 0 12px;
  font-size: 0.91rem;
  line-height: 1.65;
  color: var(--global-text-color-light, #666);
}

.teaching-custom .course-description {
  margin: 0;
  font-size: 0.95rem;
  line-height: 1.75;
  color: var(--global-text-color, #333);
}

@media (max-width: 600px) {
  .teaching-custom .course-tags {
    gap: 6px;
  }

  .teaching-custom .course-tag {
    padding: 4px 10px;
    font-size: 0.75rem;
    white-space: normal;
  }

  .teaching-custom .course-title {
    font-size: 1.1rem;
  }
}
</style>

{% assign course_titles = "Fundamentals of Automotive Crash Safety|Vehicle Safety|Safety of Intelligent Vehicle|First-Year Orientation Course" | split: "|" %}

<div class="teaching-custom">

  <h2 class="teaching-year">2026</h2>

  {% for target_title in course_titles %}

    {% assign matching_courses = site.teachings | where: "title", target_title %}

    {% for course in matching_courses %}

      <article class="course-item">

        <!-- Course title -->
        <h3 class="course-title">
          <a href="{{ course.url | relative_url }}">
            {{ course.title }}
          </a>
        </h3>

        
        <!-- Course tags -->
        {% case course.title %}
        
          {% when "Fundamentals of Automotive Crash Safety" %}
            <div class="course-tags">
              <span class="course-tag">National First-Class Course</span>
              <span class="course-tag">THU Excellent Course</span>
            </div>
        
          {% when "Vehicle Safety" %}
            <div class="course-tags">
              <span class="course-tag">Restricted Elective</span>
              <span class="course-tag">THU Excellent Course</span>
            </div>
        
          {% when "Safety of Intelligent Vehicle" %}
            <div class="course-tags">
              <span class="course-tag">Science General Education</span>
              <span class="course-tag">Curriculum Ideology &amp; Politics Model Course</span>
            </div>
        
        {% endcase %}


        <!-- Semester and instructors -->
        <div class="course-meta">
          {{ course.term }} · {{ course.instructor }}
        </div>

        <!-- Course description -->
        <p class="course-description">
          {{ course.description }}
        </p>

      </article>

    {% endfor %}

  {% endfor %}

</div>
