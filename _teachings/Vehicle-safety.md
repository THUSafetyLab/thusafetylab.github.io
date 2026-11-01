---
layout: course
title: Vehicle Safety
description: This course provides a comprehensive introduction to the scientific foundations, research methods, and emerging technologies of automotive safety. It covers interdisciplinary topics including vehicle engineering, numerical computation, artificial intelligence, and data analysis, with an emphasis on vehicle engineering.
instructor: Bingbing Nie, Qing Zhou
year: 2026
term: Fall
course_id: 40150762-0
# Weekly plan rendered by this page (named "syllabus" so the default layout does not add its own schedule table)
syllabus:
  - week: 1
    topic: Introduction
    description: Course information, the current state of road traffic safety, and the research subjects and methods of automotive safety.

  - week: 2
    topic: Fundamental Concepts and Technologies of Automotive Safety
    description: An introduction to active and passive automotive safety technologies through events related to automotive safety.

  - week: 3
    topic: Occupant Restraint Systems
    description: Fundamental concepts of occupant restraint systems, occupant collision dynamics, restraint system design principles, recent research on intelligent vehicle safety technologies, and future trends in automotive safety.

  - week: 4
    topic: System Safety, Operational Safety, and Intelligent Protection
    description: Fundamental concepts and guiding principles, safety decision-making for intelligent vehicles, system safety, operational safety, and intelligent protection.

  - week: 5
    topic: Dimensional Analysis, Experimental Techniques, and Numerical Methods
    description: Dimensional analysis, experimental techniques and methods, virtual reality and accelerated sampling of rare hazardous scenarios, numerical research methods, and virtual simulation data collection.

  - week: 6
    topic: "Injury Biomechanics: Theories and Methods"
    description: Injury mechanisms and tolerance, injury risk assessment methods, human surrogates in automotive safety, injury protection in multiple fields, and the concepts and applications of active human response.

  - week: 7
    topic: Safety Protection for Different Population Groups
    description: Child occupant protection, occupant restraint system design, pedestrian protection, and related discussions and review.

  - week: 8
    topic: Case Studies and Discussion
    description: Case studies of severe high-speed rear-end collisions and battery safety, with an extended introduction to passive safety in formula racing.

  - week: 9
    topic: Automotive Safety Testing and Evaluation
    description: Test scenarios and tools, regulations and consumer-oriented assessment methods, safety testing under the four transformations of the automotive industry, and battery safety evaluation.

  - week: 10
    topic: Machine Learning Methods and Applications in Automotive Safety
    description: Fundamental concepts of artificial intelligence, commonly used machine learning algorithms, applications of machine learning in automotive safety, and related discussion and review.

  - week: 11
    topic: Future Crash Scenarios and Risk Quantification
    description: Future road traffic crash scenarios, intelligent vehicle risk prediction, prediction-based active hood systems, autonomous vehicle decision-making with ethical intervention, and safety and trust.
---

<style>
/* Course page layout (identical block in all course pages) */
.post-description { display: none !important; }
.course > .course-info { display: none; }

.course-page {
  --cp-purple: #5b21b6;
  --cp-purple-dark: #351063;
  --cp-purple-soft: #f4efff;
  --cp-purple-line: #ded2f6;
  --cp-text: #202033;
  --cp-muted: #67677a;
  --cp-border: #e7e4ee;
  color: var(--cp-text);
}

/* Overview card: tags and key facts */
.course-hero {
  margin: 6px 0 36px;
  padding: 24px;
  border: 1px solid var(--cp-border);
  border-radius: 18px;
  background: linear-gradient(135deg, #fff 0%, #f7f3ff 100%);
}

.course-tags { display: flex; flex-wrap: wrap; gap: 8px; margin-bottom: 18px; }
.course-tags span {
  padding: 5px 11px;
  border: 1px solid var(--cp-purple-line);
  border-radius: 999px;
  background: #fff;
  color: var(--cp-purple);
  font-size: 12px;
  font-weight: 700;
}

.course-facts { display: grid; grid-template-columns: repeat(3, minmax(0, 1fr)); gap: 14px 20px; margin: 0; }
.course-facts > div { min-width: 0; }
.course-facts .wide { grid-column: span 2; }
.course-facts dt {
  margin-bottom: 3px;
  color: var(--cp-muted);
  font-size: 11.5px;
  font-weight: 700;
  letter-spacing: 0.06em;
  text-transform: uppercase;
}
.course-facts dd { margin: 0; color: var(--cp-text); font-size: 14.5px; font-weight: 600; line-height: 1.45; }

.course-photo { margin: 0; }
.course-photo img {
  display: block;
  width: 100%;
  height: auto;
  border-radius: 12px;
  box-shadow: 0 8px 24px rgba(33, 25, 48, 0.10);
}
.course-photo figcaption { margin-top: 8px; color: #858394; font-size: 12px; line-height: 1.45; text-align: center; }

/* Course Overview: text on the left, classroom photo on the right */
.course-overview { display: grid; grid-template-columns: minmax(0, 1.25fr) minmax(0, 1fr); gap: 28px; align-items: start; }
.course-overview-text > p:last-child { margin-bottom: 0; }

/* Sections */
.course-section { margin: 0 0 34px; }
.course-section h2 {
  margin: 0 0 14px;
  padding-bottom: 8px;
  border-bottom: 1px solid var(--cp-border);
  color: var(--cp-purple-dark);
  font-size: 23px;
  font-weight: 750;
}
.course-section p,
.course-section li { color: var(--cp-muted); font-size: 15.5px; line-height: 1.75; }
.course-section strong { color: var(--cp-text); }
.course-section a { font-weight: 600; }

/* Cards for course content, modules or class formats */
.course-cards { display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); gap: 14px; margin-top: 14px; }
.course-card {
  padding: 16px 18px;
  border: 1px solid var(--cp-border);
  border-left: 4px solid var(--cp-purple);
  border-radius: 12px;
  background: #fff;
}
/* A card alone in its row spans the full width of the card grid */
.course-card.full-row { grid-column: 1 / -1; }
.course-card h3 { margin: 0 0 6px; color: var(--cp-purple-dark); font-size: 16px; font-weight: 700; }
.course-card p { margin: 0; font-size: 14.5px; line-height: 1.65; }

/* Learning objectives with check marks */
.course-checklist { margin: 0; padding-left: 0; list-style: none; }
.course-checklist li { position: relative; margin-bottom: 6px; padding-left: 26px; }
.course-checklist li::before { content: "✓"; position: absolute; top: 0; left: 0; color: var(--cp-purple); font-weight: 800; }

/* Prerequisites as chips */
.course-chips { display: flex; flex-wrap: wrap; gap: 8px; margin: 0; padding: 0; list-style: none; }
.course-section .course-chips li {
  padding: 6px 12px;
  border: 1px solid var(--cp-purple-line);
  border-radius: 999px;
  background: var(--cp-purple-soft);
  color: var(--cp-purple-dark);
  font-size: 13.5px;
  font-weight: 600;
  line-height: 1.4;
}

/* Schedule */
.course-note { font-size: 14px !important; }
.course-module { margin: 22px 0 8px; color: var(--cp-purple); font-size: 13px; font-weight: 800; letter-spacing: 0.06em; text-transform: uppercase; }
.course-schedule { margin: 0; padding: 0; overflow: hidden; border: 1px solid var(--cp-border); border-radius: 12px; background: #fff; list-style: none; }
.course-schedule li { display: grid; grid-template-columns: 76px minmax(0, 1fr); gap: 14px; padding: 13px 16px; border-bottom: 1px solid #efedf3; }
.course-schedule li:last-child { border-bottom: none; }
.schedule-no {
  align-self: start;
  padding: 4px 0;
  border-radius: 8px;
  background: var(--cp-purple-soft);
  color: var(--cp-purple-dark);
  font-size: 12.5px;
  font-weight: 700;
  text-align: center;
}
.schedule-topic { display: block; color: var(--cp-text); font-size: 15px; font-weight: 700; line-height: 1.5; }
.schedule-desc { display: block; margin-top: 3px; color: var(--cp-muted); font-size: 14px; line-height: 1.6; }
.schedule-optional {
  margin-left: 6px;
  padding: 1px 7px;
  border: 1px solid var(--cp-purple-line);
  border-radius: 999px;
  color: var(--cp-purple);
  font-size: 11px;
  font-weight: 700;
  vertical-align: middle;
}

@media (max-width: 900px) {
  .course-overview { grid-template-columns: 1fr; }
  .course-facts { grid-template-columns: repeat(2, minmax(0, 1fr)); }
}
@media (max-width: 640px) {
  .course-hero { padding: 18px; }
  .course-facts { grid-template-columns: 1fr; }
  .course-facts .wide { grid-column: auto; }
  .course-schedule li { grid-template-columns: 1fr; gap: 6px; }
  .schedule-no { justify-self: start; padding: 3px 10px; }
}
</style>

<div class="course-page">

<section class="course-hero">
<div class="course-hero-text">
<div class="course-tags"><span>Restricted Elective</span><span>THU Excellent Course</span></div>
<dl class="course-facts">
<div><dt>Instructors</dt><dd>{{ page.instructor }}</dd></div>
<div><dt>Term</dt><dd>{{ page.term }}</dd></div>
<div><dt>Course No.</dt><dd>{{ page.course_id }}</dd></div>
<div><dt>Duration</dt><dd>{{ page.syllabus.size }} weeks</dd></div>
<div class="wide"><dt>Focus</dt><dd>Human–vehicle–road safety, from fundamental theory to intelligent protection</dd></div>
</dl>
</div>
</section>

<section class="course-section">
<h2>Course Overview</h2>
<div class="course-overview">
<div class="course-overview-text">
<p>This course addresses the safety needs of the human–vehicle–road system. Students will study the fundamental theories of automotive safety, learn protection methods and design applications, and develop interdisciplinary analytical skills. Course content includes:</p>
<div class="course-cards">
<div class="course-card"><h3>Concepts and Frameworks</h3><p>Fundamental concepts and frameworks of automotive safety</p></div>
<div class="course-card"><h3>Methods</h3><p>Classical methods and their recent developments</p></div>
<div class="course-card"><h3>Research Topics</h3><p>Specialized research topics in automotive safety</p></div>
<div class="course-card"><h3>Interdisciplinary Research</h3><p>Vehicle engineering, numerical computation, artificial intelligence, and data analysis</p></div>
</div>
</div>
<figure class="course-photo">
<img src="{{ '/assets/img/courses/VS-1.jpg' | relative_url }}" alt="Classroom photo from Vehicle Safety" loading="lazy">
<figcaption>Classroom photo</figcaption>
</figure>
</div>
</section>

<section class="course-section">
<h2>Prerequisites</h2>
<ul class="course-chips">
<li>Calculus</li>
<li>University Physics</li>
<li>Mechanics of Materials</li>
<li>Vehicle theory and control theory (recommended)</li>
</ul>
</section>

<section class="course-section">
<h2>Course Schedule</h2>
<ul class="course-schedule">
{%- for item in page.syllabus %}
<li><span class="schedule-no">Week {{ item.week }}</span><div><span class="schedule-topic">{{ item.topic | escape }}</span><span class="schedule-desc">{{ item.description | escape }}</span></div></li>
{%- endfor %}
</ul>
</section>

</div>
